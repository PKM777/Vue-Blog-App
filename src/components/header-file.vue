<template>
    <div>
    
        <ul class="nav_list">
            <a href="#"><li class="list_items">Logo</li></a>
            <a href="#"><li class="list_items">Home</li></a>
            <a href="#"><li class="list_items">Catagories</li></a>
            <a href="#"><li class="list_items">Trends</li></a>
            <a href="#"><li class="list_items">Contact</li></a>
        </ul>
    
    </div>
</template>

<script>
    export default {
        name: 'Head_file',
        //dataline
    data(){
        return{
            logoColor: 'red',
        }
    },
    //method-line
    methods:{
        
    }
    }
</script>

<style>
a{
    text-decoration: none;
}
.nav_list{
    display: flex;
    list-style: none;
    width: 100%;
    height: 10vh;
    margin: 0;
    padding: 0;
    align-items: center;
    justify-content: space-around;
    background-color: blueviolet;
    
    
}
.list_items{
    font-weight: 600;
    width: 10vw;
    text-align: center;
    color: white;
}
ul :first-child{
    margin-right: auto;
}
</style>