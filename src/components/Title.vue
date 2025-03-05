<template>
    <h3 class="title"><slot/></h3>
    {{ y[0] }}
    {{ y[1] }}
    {{ y[2] }}
</template>

<script setup>
var x = "Rahim"
var y = ['rahim', 'karim', 'jadu', 'modhu']
y[0]
for(var i= 0; i<5; i++){
    console.log(i);
    y[i]
    
}
</script>