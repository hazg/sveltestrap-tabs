<script>
	import { Nav } from 'sveltestrap';
	export let id = 'svelte'
</script>

<Nav tabs {id} role="tablist" {...$$props}>
	<slot />
</Nav>
