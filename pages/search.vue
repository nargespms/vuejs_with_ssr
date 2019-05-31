<template>
	  <div>
	    
	    <searchList/>
	    <searchForm/>
	  </div>
	</template>
	
	<script>
	import searchList from '../components/elements/searchList.vue'
	import searchForm from '../components/elements/searchForm.vue'
	
	export default {
	   components: {
	        searchList,
	        searchForm,
	    },
	}
	</script>