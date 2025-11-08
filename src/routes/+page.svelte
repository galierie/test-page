<script lang="ts">
	import { asset } from '$app/paths';

	import nutshellBudget from '$lib/assets/graphs/nutshell_budget.jpg';

	const background = asset('$lib/assets/flood.jpg');
</script>

<img src={background} alt="" class="h-auto w-full" />
<img src={asset(nutshellBudget)} alt="" class="h-auto w-full" />
