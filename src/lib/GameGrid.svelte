<script>
	import GridCell from "./GridCell.svelte";

	//incluir una variable para el tamano (puede cambiar)
	//entre valores como 3rem, 5rem o 10rem
</script>

<div class="board">
	<div class="row top-row">
		<GridCell isMiddle={false} />
		<GridCell isMiddle={true} />
		<GridCell isMiddle={false} />
	</div>
	<div class="row middle-row">
		<GridCell isMiddle={false} />
		<GridCell isMiddle={true} />
		<GridCell isMiddle={false} />
	</div>
	<div class="row bottom-row">
		<GridCell isMiddle={false} />
		<GridCell isMiddle={true} />
		<GridCell isMiddle={false} />
	</div>
</div>

<style>
	.row {
		display: flex;
		flex-direction: row;
	}

	.middle-row {
		border-top: solid;
		border-bottom: solid;
	}
</style>
