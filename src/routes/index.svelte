<div class="navigation">
    <ul id="nav-bar">>
        <li><a class="active" href="#Home">Home</a></li>
        <li><a href="#about">About</a></li>
       <li><a href="#projects">Projects</a></li>
    </ul>
</div>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<a href='https://www.freepik.com/vectors/software-background'>Software background</a>
<button on:click|once={handleClick}>Click me</button>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@600&display=swap');
    :global(body) {
        background-image: url('/Background.jpg');
        background-size: cover;
        font-family: 'Comfortaa', cursive;
    }
    p {
        color:white;
    }
    h1 {
        color: white;
        text-align: center;
    }
    .navigation ul {
        list-style-type: none;
        margin: 0;
        padding: 0;
        overflow: hidden;
        background-color: transparent;
    }

    .navigation li {
        color: white;
        float:center;
    }

    .navigation ul li a {
        display: block;
        color: white;
        text-align: center;
        vertical-align: middle;
        padding: 14px;
        text-decoration: none;
    }
</style>

<script>
    function handleClick() {
        alert('stop clicking');
    }
</script>