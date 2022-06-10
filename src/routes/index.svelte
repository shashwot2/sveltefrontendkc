<div class="navigation">
    <ul id="nav-bar">
        <li><a class="active" href="">Home</a></li>
        <li><a href="#about">About</a></li>
       <li><a href="#projects">Projects</a></li>
    </ul>
</div>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<a href='https://www.freepik.com/vectors/software-background'>Software background</a>
<button on:click|once={handleClick}>Click me</button>
<style>
    :global(body) {
        background-image: url('/Background.jpg');
        background-size: cover;
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
        float:left;
    }

    .navigation ul li a {
        display: block;
        color: black;
        text-align: center;
        padding: 14px 16px;
    }
</style>

<script>
    function handleClick() {
        alert('stop clicking');
    }
</script>