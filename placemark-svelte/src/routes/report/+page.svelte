<script>
    import Header from '$lib/Header.svelte';
    import PlacemarkList from '$lib/PlacemarkList.svelte';
    import MainNavigator from '$lib/MainNavigator.svelte';
</script>

<Header>
	<MainNavigator />
</Header>

<div class="columns">
    <div class="column has-text-centered">
    
    </div>
    <div class="column box has-text-centered">
        <h1 class="title is-4">Placemarks to date</h1>
        <PlacemarkList />
    </div>
</div>
