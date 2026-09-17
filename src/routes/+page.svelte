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