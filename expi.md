🎀
``` html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>fourth attempt</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="expi.css" />
  </head>
  <body>
    <!--up most-->
    <nav id="navibar">
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
    </nav>
    <div id="vidcon">
      <video
        id="videoo"
        src="akonalangplease.mp4"
        loop
        autoplay
        controls
      ></video>
    </div>
  </body>
</html>

```


``` css
.upper {
    display: flex;
    justify-content: center;
    font-family: 'Courier New', Courier, monospace;
    color: rgb(0, 0, 0);

}

.fa-solid-fa-paw {
    color: rgb(20, 7, 7);
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

#navibar {
    background-color: transparent;
    padding: 1rem;
    position: fixed;
    width: 100%;
    z-index: 10;
    padding: 10px 20px;
    box-sizing: border-box;
}

#navibar ul {
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
    color: rgb(255, 255, 255);
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

#vidcon {
    position: relative;
    height: 100vh;
    overflow: hidden;
    z-index: 1;
}

#videoo {
    width: 100%;
    height: auto;
    display: block;
    object-fit: cover;
    object-fit: fill;
}

#videoo::-webkit-media-controls-panel {
    background-color: rgba(75, 75, 75, 0);
    border-radius: 5px;
}
```
