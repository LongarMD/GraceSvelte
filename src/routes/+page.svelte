<script lang="ts">
	import { Button } from '$lib/components/ui/button';

	let x = 0;

	function onClick() {
		x = x + 1;
	}
</script>

<h1 class="text-3xl font-bold underline">Hello world!</h1>

<Button on:click={onClick}>
	Kliknil si me {x}-krat
</Button>
