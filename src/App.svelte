<script lang="ts">
  const seahorses = "assets/seahorses.png"
</script>

<main>
    <div class="part-1">
        <h1>Hello World !</h1>
        <img src={seahorses} alt="Seahorses">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A adipisci asperiores atque, consequatur dolor
            dolore, doloribus dolorum, enim fugit id iure laudantium magni numquam pariatur provident quisquam repellat
            repellendus sed.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A adipisci asperiores atque, consequatur dolor
            dolore, doloribus dolorum, enim fugit id iure laudantium magni numquam pariatur provident quisquam repellat
            repellendus sed.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A adipisci asperiores atque, consequatur dolor
            dolore, doloribus dolorum, enim fugit id iure laudantium magni numquam pariatur provident quisquam repellat
            repellendus sed.</p>
    </div>
</main>

<style>
    main {
        min-height: 100vh;
        max-width: 100vw;
        background-image: url("/assets/starfishes_seashells_bg.jpg");
        background-size: cover;
    }

    .part-1 {
        width: 45%;
    }

    img[alt=Seahorses] {
        width: 200px;
    }
</style>
