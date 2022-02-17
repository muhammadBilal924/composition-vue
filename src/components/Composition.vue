<template>
    <div>
    <h1>Composition Componenet</h1>
    <Users />
    <Products />
    <Products />
    </div>
</template>

<script>
import Users from './Users'
import Products from './Products'
    export default {
     name:"Composition",
    
     components: {
         Users,
         Products,
     },  
    }
</script>

<style scoped>
div{
    background-color: aqua;
    height: 500px;
}
</style>