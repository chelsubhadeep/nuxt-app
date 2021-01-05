<template>
	<div>
		<h1>{{ slug.post }}</h1>
	</div>
</template>

<script>
	export default{
		validate({ params }){
			return /^\d+$/.test(params.post)
		},
		data(){
			return{
				slug: this.$nuxt.$route.params
			}
		}
		//created(){
		//	console.log(this.$route.paramas)
		//}
	}//cause problem 
</script>
