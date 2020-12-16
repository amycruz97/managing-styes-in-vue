<template>
    <div class="navbar">
        
        <div class="navLink">
            <a href="#">About</a>
            <a href="#">Services</a>
            <a href="#">Contact</a>

        </div>

    </div>
</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style scoped>
.navbar{
    width: 100%;
    background: #f44336;
    padding: 1rem ;
    font-size: 1.5rem;
    

}
.navLink{

text-align: center;
}
a{
    text-decoration: none;
    padding: 1rem;
    color:#fff;
    text-align: center;
}

@media only screen and (max-width: 600px) {
    .navLink{
        display: flex;
        flex-direction: column;
    }
}
</style>