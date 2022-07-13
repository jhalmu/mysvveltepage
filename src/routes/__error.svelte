<script context="module">
	export function load({ error, status }) {
		return {
			props: {
				title: `${status}: ${error.message}`
			}
		};
	}
</script>

<script>
	export let title;
</script>

<h1 class="badge-info p-10 m-10 flex rounded border-spacing-1 shadow-xl">{title}</h1>
