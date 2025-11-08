<script lang="ts">
	import { asset } from '$app/paths';
	import unresolvedBackground from '$lib/assets/flood.jpg';
	import unresolvedNutshellBudget from '$lib/assets/graphs/nutshell_budget.jpg';

	const background = asset(unresolvedBackground);
	const nutshellBudget = asset(unresolvedNutshellBudget);
</script>

<img src={background} alt="" class="h-auto w-full" />
<img src={nutshellBudget} alt="" class="h-auto w-full" />
