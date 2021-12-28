<template>
    <div>
        <b-navbar toggleable="lg" type="dark" variant="info">
            <b-navbar-brand href="#">
                <img src="~/static/kafin.png" alt=""/>
            </b-navbar-brand>

            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

            <b-collapse id="nav-collapse" is-nav>
                <b-navbar-nav>
                    <b-nav-item href="#">About</b-nav-item>

                    <b-nav-item-dropdown text="Shop" right>
                        <b-dropdown-item href="#">Coffee</b-dropdown-item>
                        <b-dropdown-item href="#">Tea</b-dropdown-item>
                        <b-dropdown-item href="#">Subscription</b-dropdown-item>
                    </b-nav-item-dropdown>
                    <b-nav-item href="#">Contact</b-nav-item>
                </b-navbar-nav>
            </b-collapse>
        </b-navbar>
    </div>  
</template>

<script>
export default {
  name: 'Header'
}
</script>