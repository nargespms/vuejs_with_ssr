<template>
	  <div>
	    <posts/>
	    <photos/>
	  </div>
	</template>
	
	<script>
	import posts from '../components/elements/posts.vue'
	import photos from '../components/elements/photos.vue'
	
	export default {
	   components: {
	     
	      posts,
	      photos
	    },
	
	}
	</script>