<template>

    <div>
        <h2>Match number : {{book.match_no}}</h2>
         <h4>Map : {{book.map}}</h4>
     <h4>Date : {{book.date}}</h4>
    <h4>Time : {{book.time}}</h4>
    <h4>Entrance Fee : {{book.entrance_fee}}</h4>
        
    </div>

</template>

<script>




export default{
    name: 'BookItem',
    props:{
        book: Array
    }
}


</script>

<style scoped>

h2{
    text-align: center;
}
h4{
    margin: 2px;
    text-align: center;
}
h1{
    text-align: center;
}
#nameof{
    background-color: #b1ff9e;
    color: black;
    padding: 1em;

}
div{
    background-color: #ffb89e;
    color: black;
    padding: 1em;
}

.red{
background-color: orangered !important;

}
.green{
    color: white;
}


</style>
