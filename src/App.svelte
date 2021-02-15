<script>
	import CharityList from "./CharityList.svelte";

	let title="Charity";
	setTimeout(function(){
		title='indonesia';
	},5000)
</script>

<div>
	<h1>{title}</h1>
	<CharityList/>
</div>

<style>
	h1{
		font-size: 3rem;
		color:red
	}
	div{
		border:red 1px solid
	}
</style>