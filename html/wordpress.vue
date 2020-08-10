<template>
<div class="container-basico">
    <label for="input1" class="input-label"> Probando html basico</label>
    <input type="text" name="entrada" id="input1" class="input-class">
</div>
</template>

<style>
    .container-basico {
        display: flex;
        flex-flow: column;
        width: 100%;

        
    }

    .container-basico > .input-label {
        margin-left: 50px;
        font-style: italic;
        color: #667722;
        transition: 0.3s all ease;

    }

    .container-basico > .input-label:hover {
        transform: scale(1.05);
        font-style: italic;
        color: #4a5718;
               
    }
</style>