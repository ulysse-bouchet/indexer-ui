<script lang="ts">
	// Properties
	let { className = 'size-5 stroke-2' }: { className?: string } = $props();
</script>

<svg
	xmlns="http://www.w3.org/2000/svg"
	viewBox="0 0 24 24"
	class={className}
	fill="none"
	stroke="currentColor"
	stroke-linecap="round"
	stroke-linejoin="round"
>
	<path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"></path>
	<polyline points="17 8 12 3 7 8"></polyline>
	<line x1="12" y1="3" x2="12" y2="15"></line>
</svg>
