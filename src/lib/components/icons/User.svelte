<script lang="ts">
	interface Props {
		className?: string;
	}

	let { className = 'size-5' }: Props = $props();
</script>

<svg xmlns="http://www.w3.org/2000/svg" class={className} viewBox="0 0 20 20" fill="currentColor">
	<path
		fill-rule="evenodd"
		d="M10 9a3 3 0 100-6 3 3 0 000 6zm-7 9a7 7 0 1114 0H3z"
		clip-rule="evenodd"
	/>
</svg>
