<section class="card">
</section>
section.card {
    /* display: flex; */
    height: 500px;
    width: 250px;
    background: darkblue;
    color: antiquewhite;
    justify-self: center;
    padding: 2em 4.5em 4.5em 4.5em;
    margin: 0 5em 0 5em;
    gap: 1em; 
section {   
    
    position: relative;

    img.left-top {
        position: absolute;
        top: 0;
        left:-7.5em;
    }

        img.left-mid {
        position: absolute;
        top: 6em;
        left:-7.5em;
    }

        img.left-bottom {
        position: absolute;
        top: 12em;
        left:-7.5em;
    }

        img.right-top {
        position: absolute;
        top: 0;
        right:-7.5em;
    }

        img.right-mid {
        position: absolute;
        top: 6em;
        right:-7.5em;
    }

        img.right-bottom {
        position: absolute;
        top: 12em;
        right:-7.5em;
    }
}
<script>

	import { onMount } from 'svelte';

	const { data } = $props();
	const persons = data.persons;

</script>