<script setup>
import WelcomeItem from './WelcomeItem.vue'
</script>
 
<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template> 
    <template #heading>Activities</template>

   
    <a href="#">Table</a><br /><br />
    <a href="#">Subscript</a><br /><br />
    <a href="#">Facebook</a><br /><br />
    <a href="#">Building</a><br /><br />
    <a href="#">Javascript1</a><br /><br />
    <a href="#">Javascript2</a>
    
  </WelcomeItem>

</template>
