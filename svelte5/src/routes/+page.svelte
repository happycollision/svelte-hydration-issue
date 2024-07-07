<script>
	import { browser } from "$app/environment"
	const renderLocation = browser ? "In browser" : "On server"
</script>

<h1>Welcome to SvelteKit</h1>

Standard: {renderLocation}
<br />
@html: {@html renderLocation}
