<template>

        <footer :style="[footerStyles1, textColor]">
        <p>	&copy; 2020</p>

        </footer>
</template>

<script>
export default {
    data(){
        return{
            footerStyles1:{
                backgroundColor: 'black',
                height: '200px',
                textAlign: 'center',
                padding: '5rem'
            },
            textColor:{
                color: 'red',
            }
            
        }
    }
}
</script>

<style>


</style>