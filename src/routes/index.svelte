<nav class="navigation">
    <ul>
        <li><a class="active" href="#Home">Home</a></li>
        <li><a href="#about">About</a></li>
       <li><a href="#projects">Projects</a></li>
    </ul>
</nav>
<div class = "paragraph">
<p>

    Hi! Welcome to my personal website. I'm Shashwot KC. This website shows my personal projects and what I get up to in a regular basis. It is also me learning
    a frontend framework to become a full stack engineer. I'm currently a backend engineer with some server skills to boot. This website was made with svelte.
    
    Blog under construction.
</p>
</div>
<img src = "/Dexter.jpg" alt = "Dexter" class = "dexter">

<div class ="footer">
    <a href="https://github.com/shashwot2"><img class= "footer-links" src = "/git.png" alt = "github"></a>
    <a href="https://www.linkedin.com/in/shashwot-kc-b9a8b917b/"><img class= "footer-links" src = "/linkedin.png" alt = "linkedin"></a>
    <p> Footer </p>
</div>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@600&display=swap');
    :global(body) {
        background-size: cover;
        /* background-image: url('/Dexter.jpg'); */
        font-family: 'Comfortaa', cursive;
        background-color: #e2e2e2;
    }
    .dexter{
        width: 100%;
        height: 50%;
        display: block;
        align-items: center;
        opacity: 0.5;
    }
    .paragraph{
        display: flex;
        align-items: center;
        text-align: center;
        width: 65%;
        font-size: large;
        height: 200px;
        line-height: 1.2;
        margin: auto;
        
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
        color: black;
        float: center;
        display :inline;
    }

    .navigation ul li a {
        padding: 0 30px;
        float: left;
        display: block;
        color: black;
        font-size: large;
        text-decoration: none;
    }
    .footer {
        /* position: fixed; */
        left: 0;
        bottom: 0; 
        width: 100%;
        text-align: center;
    }
    .footer .footer-links{
        width: 40px;
    }
</style>
