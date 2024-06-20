<script>
	let cellClassName;
	export let isMiddle;

	isMiddle ? (cellClassName = "middle-cell") : (cellClassName = "");
</script>

<div class={`grid-cell ${cellClassName}`}>X</div>

<style>
	.grid-cell {
		display: flex;
		align-items: center;
		justify-content: center;

		font-family: cursive;
		font-size: 5rem;

		width: 6rem;
		height: 6rem;
	}

	.middle-cell {
		border-left: solid;
		border-right: solid;
	}
</style>
