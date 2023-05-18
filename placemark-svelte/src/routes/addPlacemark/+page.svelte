<script>
    import Header from '$lib/Header.svelte';
    import PlaceMarkForm from '$lib/PlaceMarkForm.svelte';
    import MainNavigator from '$lib/MainNavigator.svelte';
</script>

<Header>
	<MainNavigator />
</Header>

<div class="columns is-vcentered">
    <div class="column has-text-centered">
        
    </div>
    <div class="column box has-text-centered">
        <h1 class="title is-4">Add PlaceMark!</h1>
        <PlaceMarkForm />
    </div>
</div>
