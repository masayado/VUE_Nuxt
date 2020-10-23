<template>
    <div>
        <div class="footer">
            <p class="footer__paragraph">Rick & Morty Characters</p>
        </div>
        
    </div>
</template>

<script>
export default {
    name: 'component-name',
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
    .footer{
        width:100%;
        height:80px;
        background-color:#14AFC3;
        color:black;
        display:flex;
        justify-content: center;
        align-items: center;
    }

    p{
        margin:0;
        padding:0;
    }
</style>