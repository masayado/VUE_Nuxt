<template>
    <b-navbar toggleable="sm" type="dark" variant="dark">
        <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>

        <b-navbar-brand variant="faded" type="light">Mi App</b-navbar-brand>

        <b-collapse id="nav-text-collapse" is-nav>
        <b-navbar-nav>
            <b-nav-text>Rick & Morty</b-nav-text>
            <b-nav-item href="#">Inicio</b-nav-item>
            <b-nav-item href="#">Buscar</b-nav-item>
            <b-nav-item href="#">Acerca de</b-nav-item>
        </b-navbar-nav>
        </b-collapse>
  </b-navbar>
</template>

<script>
export default {
    name: 'navbar-component',
    // props: {},
    data: function(){
        return {}
    },
    // computed: {},
    methods: {
        // -- Metodos
    },
    //components: {},
}
</script>

<style scoped>
    
</style>