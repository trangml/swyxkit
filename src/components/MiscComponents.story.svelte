<!-- https://histoire.dev/guide/svelte3/stories.html -->
<!-- https://histoire.dev/guide/svelte3/controls.html -->
<script>
	import IndexCard from './IndexCard.svelte';
	// import Newsletter from './Newsletter.svelte';
	// import Nav from './Nav.svelte'; // for some reason importing this breaks histoire with a ReferenceError: __SVELTEKIT_APP_VERSION_POLL_INTERVAL__ is not defined. why?
	export let Hst;
</script>

<Hst.Story title="Misc Components" layout={{ type: 'grid', width: '100%' }}>
	<!-- <Hst.Variant title="Nav">
		<Nav />
	</Hst.Variant> -->
	<Hst.Variant title="Index page cards">
		<IndexCard href="/finally-making-a-blog" title="Finally Making a Blog">
			This is Matthew Trang's Blog!
		</IndexCard>
	</Hst.Variant>
	<!-- <Hst.Variant title="Newsletter">
		<Newsletter />
	</Hst.Variant> -->
</Hst.Story>
