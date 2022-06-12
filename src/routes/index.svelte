<div class="navigation">
    <ul>
        <li><a class="active" href="#Home">Home</a></li>
        <li><a href="#about">About</a></li>
       <li><a href="#projects">Projects</a></li>
    </ul>
</div>

<h1>Welcome to SvelteKit</h1>
<p>
    Hi! Welcome to my personal website. I'm Shashwot KC. You can call me KC if you like :). This website shows my personal projects and what I get up to in a regular basis. It is also me learning
    a frontend framework to become a full stack engineer. I'm currently a backend engineer with some server skills to boot. This website was made with svelte.
    
    Blog under construction.
</p>
<a href='https://www.freepik.com/vectors/software-background'>Software background</a>
<button on:click|once={handleClick}>Click me</button>

<div class ="footer">
    <p> Footer </p>
</div>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@600&display=swap');
    :global(body) {
        background-image: url('/Background.jpg');
        background-size: cover;
        font-family: 'Comfortaa', cursive;
    }
    p {
        color:white;
        align-items: center;
    }
    h1 {
        color: white;
        text-align: center;
    }
    .navigation{
        height: 3.5em;
        text-align: center;
    }
    .navigation ul {
        display: inline-block;
        list-style-type: none;  
        overflow: hidden;
        background-color: transparent;
    }

    .navigation li {
        color: white;
        float: center;
        display :inline;
    }

    .navigation ul li a {
        padding: 0 30px;
        float: left;
        display: block;
        color: white;
        text-decoration: none;
    }
    .footer {
        position: fixed;
        left: 0;
        bottom: 0; 
        width: 100%;
        text-align: center;
    }
</style>

<script>
    function handleClick() {
        alert('stop clicking');
    }
</script>