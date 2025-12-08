🎀
``` html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>fifth attempt</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="discover1.css" />
  </head>
  <body class="backg">
    <!--up most-->
    <section class="upper">
      <i class="fa-solid-fa-paw"> <img src="paw-solid-full.svg" />POSA</i>
    </section>
    <nav>
      <!--upper navi-->
      <ul>
        <li><a href="islandsLuzon.html">Islands</a></li>
        <li><a href="disccover1.html">Discover</a></li>
        <li><a href="expi.html">Experience</a></li>
      </ul>
    </nav>
    <div class="carousel">
      <div class="group">
        <div class="card"><img src="BALUARTE.jpg"/></div>
        <div class="card"><img src="BINONDO.jpg" /></div>
        <div class="card"><img src="CATHEDRAL.jpg" /></div>
        <div class="card"><img src="CHOCO H.jpg" /></div>
        <div class="card"><img src="COVE.jpg" /></div>
        <div class="card"><img src="FINK B.jpg" /></div>
        <div class="card"><img src="FORTSAN.jpg" /></div>
        <div class="card"><img src="HINADAN.jpg" /></div>
        <div class="card"><img src="FINK M.jpg" /></div>
        <div class="card"><img src="KAWASAN.jpg" /></div>
        <div class="card"><img src="LAKE SEB.jpg" /></div>
        <div class="card"><img src="MANILA BAY.jpg" /></div>
        <div class="card"><img src="MARIA.jpg" /></div>
        <div class="card"><img src="MUSEUMM.jpg" /></div>
        <div class="card"><img src="NATURE P.jpg" /></div>
        <div class="card"><img src="RICE TERRE.jpg" /></div>
        <div class="card"><img src="SAMBAWA.jpg" /></div>
        <div class="card"><img src="TINU F.jpg" /></div>
        <div class="card"><img src="WAG ECOPARK.jpg" /></div>
        <div class="card"><img src="WHITE.jpg" /></div>
      </div>
      <div aria-hidden class="group">
        <div class="card"><img src="BALUARTE.jpg"/></div>
        <div class="card"><img src="BINONDO.jpg" /></div>
        <div class="card"><img src="CATHEDRAL.jpg" /></div>
        <div class="card"><img src="CHOCO H.jpg" /></div>
        <div class="card"><img src="COVE.jpg" /></div>
        <div class="card"><img src="FINK B.jpg" /></div>
        <div class="card"><img src="FORTSAN.jpg" /></div>
        <div class="card"><img src="HINADAN.jpg" /></div>
        <div class="card"><img src="FINK M.jpg" /></div>
        <div class="card"><img src="KAWASAN.jpg" /></div>
        <div class="card"><img src="LAKE SEB.jpg" /></div>
        <div class="card"><img src="MANILA BAY.jpg" /></div>
        <div class="card"><img src="MARIA.jpg" /></div>
        <div class="card"><img src="MUSEUMM.jpg" /></div>
        <div class="card"><img src="NATURE P.jpg" /></div>
        <div class="card"><img src="RICE TERRE.jpg" /></div>
        <div class="card"><img src="SAMBAWA.jpg" /></div>
        <div class="card"><img src="TINU F.jpg" /></div>
        <div class="card"><img src="WAG ECOPARK.jpg" /></div>
        <div class="card"><img src="WHITE.jpg" /></div>
    </div>

    <div class="baba">
      <button><a href="tryy3.html">Back</a></button>
    </div>
  </body>
</html>

```


``` css
.backg {
    background: -webkit-linear-gradient(to bottom, rgba(51, 50, 50, 0.762), transparent), url('download.jpg');
    background: linear-gradient(to bottom, rgba(54, 53, 53, 0.766), transparent), url('download.jpg');
    background-size: cover;
    background-attachment: fixed;
    background-position: center;
    height: 500px;
    width: auto;
}

.upper {
    display: flex;
    justify-content: center;
    font-family: 'Courier New', Courier, monospace;
    color: white;

}

.fa-solid-fa-paw {
    color: white;
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
    padding: 1rem;
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
    color: white;
    text-decoration: none;
    padding: 0.5rem 1rem;
    display: block;
}

nav ul li a:hover {
    background-color: rgba(131, 2, 114, 0.873);
    border-radius: 10%;
    padding: 5px;
    margin: 5px;
    scale: 1;
}

.carousel {

    margin: 20px 0 0 0;
    padding: 1%;
    position: relative;
    display: flex;
    overflow-x: auto;
    gap: 1em;
}

.carousel::-webkit-scrollbar {
    display: none;
}

.group {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 1em;
    animation: spin 70s infinite linear;

}

.card {
    flex: 0 0 500px;

    padding: 1em;
    background: transparent;
    border-radius: 10px;
    display: flex;
    align-content: center;
    justify-content: center;
    overflow: hidden;

}


@keyframes spin {
    from {
        transform: translateX(0);
    }

    to {
        transform: translateX(-100%);
    }
}

.card img {
    object-fit: cover;
    height: 200px;
    width: 10%;
    height: 100%;
    width: 100%;
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
