<template>
    <b-navbar toggleable="sm" type="light" variant="info">
        <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>

        <b-navbar-brand variant="faded" type="light">Rick & Morty</b-navbar-brand>

        <b-collapse id="nav-text-collapse" is-nav>
        <b-navbar-nav>
            <b-nav-item to="/">Inicio</b-nav-item>
            <b-nav-item to="/characters">Personajes</b-nav-item>
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