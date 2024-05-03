<template>
    <Carousel/>
    <projects class="flex flex-col">
      <div class="flex flex-row">
      <Bucket src="CPP.png" title=""/>
      <Bucket src="" title="C Plus Plus"/>
      <Bucket src="CSharp.png" title=""/>
      <Bucket src="" title="CSharp"/>
    </div>
    <div class="flex flex-row">
      <Bucket src="" title="HTML"/>
      <Bucket src="HTML.png" title=""/>
      <Bucket src="" title="SQL"/>
      <Bucket src="SQL.png" title=""/>
    </div>  
    </projects>
    
    
</template>
<script setup>
useHead ({
    title: 'Tomorrow Coding',
    meta: [
    { name: 'About, projects, and more', content: 'Home of Tomorrow Coding' }
  ],
});
</script>