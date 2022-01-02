<template>
  <div>
    <a  class="kf__btn" :class="[type, color]" v-if="type === 'link'">
      {{ text }}
    </a>
    <button  class="kf__btn" :class="[type, color]"  v-else>
      {{ text }}
    </button>
  </div>
</template>
<script>
export default {
  props: {
    text: String,
    type: String,
    btnStyle: "",
    color: "",
    url: String
  },
  data() {
    return {
      isHover: false
    };
  }
};
</script>
