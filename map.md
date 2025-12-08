🎀
``` html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>mapa</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="map.css" />
  </head>
  <body class="mappic">
    <section class="islaupper">
      <i class="fa-solid-fa-paw"> <img src="paw-solid-full.svg" />POSA</i>
    </section>
    <nav>
      <ul>
        <li><a href="islandsLuzon.html">Islands</a></li>
        <li><a href="disccover1.html">Discover</a></li>
        <li><a href="expi.html">Experience</a></li>
      </ul>
    </nav>
    <br />
    <div class="baba">
      <button><a href="tryy3.html">Back</a></button>
    </div>
  </body>
</html>

```


``` css
.islaupper {
    display: flex;
    justify-content: center;
    font-family: 'Courier New', Courier, monospace;
}

.fa-solid-fa-paw {
    color: black;
    display: inline-flex;
    justify-content: center;
    margin: 1px;
    padding: 2px;
}

section .upper i .upper .fa-solid-fa-paw {
    flex-direction: row;
    display: inline-flex;
    margin: 1px;
    padding: 2px;
}

nav {
    background-color: transparent;
    padding: 1rem
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 2;
    display: flex;
    justify-content: space-around;
}

nav ul li {
    display: inline;
}

nav ul li a {
    color: black;
    text-decoration: none;
    padding: 0.5rem 1rem;
    display: block;
    border: 2px solid black;
}

nav ul li a:hover {
    background-color: rgba(131, 2, 114, 0.873);
    border-radius: 10%;
    padding: 5px;
    margin: 5px;
    scale: 1;
}


body {
    margin: 0;
    font-family: Arial, sans-serif;
    scroll-behavior: smooth;
}

.mappic {
    height: 300vh;
    scroll-snap-type: y mandatory;
    background-image: url("ph\ map.jpg");
    object-fit: cover;
    background-repeat: no-repeat;
    background-size: cover;
}

.baba {
    position: fixed;
    bottom: 0;
    left: 50%;
    gap: 50px;
    padding: 10px;
    background-color: transparent;
    transform: translateX(-50%);

}

.baba button {
    background-color: transparent;
    border: none;
    cursor: pointer;
    color: white;
}

button a {
    text-decoration: none;
    display: flex;
    background-color: rgb(118, 4, 89);
    color: white;
    padding: 0.5rem 1rem;
    display: block;
}

button a:hover {
    text-decoration: none;
    padding: 5px;
    margin: 5px;
}
```
