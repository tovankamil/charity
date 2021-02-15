<script>
	import CharityList from "./CharityList.svelte";

	let title="Charity";
	setTimeout(function(){
		title='indonesia';
	},5000)
</script>

<h1>{title}</h1>
<CharityList/>
<style>
	h1{
		font-size: 3rem;
		color:red
	}
</style>