

<section class="card">

    <h2>
        TOASTERBATH0758
    </h2>



    <section class="profile-photo-wrapper">
    <img hidden class="profile-photo" src="src/lib/assets/mememefish-dithered-black-white.png" width="200" alt="">
        <img class="profile-photo" src="src/lib/assets/mememefish-dithered-green.png" width="200" alt="">
        <img class="img-border" src="src/lib/assets/imgborder2.png" height="300" alt="">
    </section>

    <section>
        <img class="left-top" src="src/lib/assets/chinesetext1.png" width="100" alt="">
        <img class="left-mid" src="src/lib/assets/chinesetext2.png" width="100" alt="">
        <img class="left-bottom" src="src/lib/assets/chinesetext3.png" width="100" alt="">
    </section>

    <section>
        <img class="right-top" src="src/lib/assets/4evrluv.png" width="100" alt="">
        <img class="right-mid" src="src/lib/assets/fairys.png" width="100" alt="">
        <img class="right-bottom" src="src/lib/assets/fire.png" width="100" height="100" alt="">
    </section>



    <p>
        IK BEN {persons.name} IK STUDEER FDND FRONTEND DEVELOPING
    </p>
    <p>

    </p>

    <section class="sideways-title">
        <h3 class="top-left">
            hoi hallo
        </h3>
         <!-- <h3 class="bottom-right">
            welkom
         </h3> -->
        <!-- <p>welkom</p> -->
    </section>

</section>




<style>

/* applies to <body> */
:global(body) {
    margin: 0;
    width: 100vw;
    justify-content: center;
    background: lightgreen;
    background-image: url("src/lib/assets/background1.jpg");

    h2 {
        /* font-family:src/lib/assets/ManufacturingConsent-Regular.ttf; */
        justify-self: center;
        font-size: 2.5em;
        background: darkblue;
        margin: 0 0 0.5em 0;
        padding: 0.5em 1em 0.5em 1em;
        background-image: url("src/lib/assets/banner1.jpg");
        object-fit: fill;
    }
}

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

    section.sideways-title {
        display: flex;
        position: absolute;

        h3.top-left {
            margin: 0;
            writing-mode: vertical-rl;
            text-orientation: upright;
            background: black;
            left: -1em;
        }
    }

    section.profile-photo-wrapper {
        justify-content: center;
        align-content: center;
        top: 5em;

        img.img-border {
            position: absolute;
  
            }

        img.profile-photo {
                position: absolute;
                top: 1em;
                left: 1em; 
                
            &:hover {
                display: none;
            } 


            }
        }
}   


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

 /* {
    position: absolute;
    left: 0;
} */


</style>

<script>

	import { onMount } from 'svelte';

	const { data } = $props();
	const persons = data.persons;

</script>