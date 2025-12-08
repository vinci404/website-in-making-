🎀
``` html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>visayas</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="islandsVisayas.css" />
  </head>
  <body class="islabg">
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

    <nav class="island-nav">
      <details class="dropdown navii">
        <!--how can i make this place to other end???? justify-content: flex-end dont work-->
        <summary>Choose Island</summary>
        <p><a href="islandsLuzon.html">Luzon</a></p>
        <p><a href="islandsVisayas.html">Visayas</a></p>
        <p><a href="islandsMinda.html">Mindanao</a></p>
      </details>

      <span class="btnn">
        <button><a href="moree.html">WHAT'S MORE</a></button>
        <button><a href="map.html">MAPS</a></button>
      </span>
    </nav>

    <div class="main-container">
      <!-- decsription box -->
      <div class="descbox">
        <h2>Visayas</h2>
        <p>
          The Visayas, or the Visayan Islands, are one of the three main
          geographical divisions of the Philippines, along with Luzon and
          Mindanao. Located in the central part of the archipelago, it consists
          of several islands, primarily surrounding the Visayan Sea. It consists
          of seven large and several hundred smaller islands clustered around
          the Visayan, Samar, and Camotes seas. The seven main islands are
          Bohol, Cebu, Leyte, Masbate, Negros, Panay, and Samar. These islands
          and their smaller neighbours make up the central group of the
          Philippine archipelago. High mountains characterize most of the
          Visayan Islands with the exception of Samar and Masbate, which are
          exceedingly hilly. Panay has extensive eastern plains where sugarcane
          and rice are farmed. Negros has large western plains on which
          sugarcane is grown. Corn (maize), coconuts, bananas, tobacco, abaca,
          and root crops also are widely grown, and fishing is also important in
          the Visayas.
        </p>
      </div>
    </div>
    <!--CLOSE THIS AND ADJUST THE WIDTH FOR CAROUSELLLL kahiya sa kanila nagtanong pa ko-->

    <div class="carousel">
      <div class="group">
        <div class="card"><img src="luzon.jpg" /></div>
        <div class="card"><img src="visayas.jpg" /></div>
        <div class="card"><img src="mindanao.jpg" /></div>
        <div class="card"><img src="cebu.webp" /></div>
        <div class="card"><img src="fort.jpg" /></div>
        <div class="card"><img src="intra.jpg" /></div>
        <div class="card"><img src="intramuros.jpg" /></div>
        <div class="card"><img src="jeep.jpg" /></div>
        <div class="card"><img src="isla.jpg" /></div>
        <div class="card"><img src="manila-298.jpg" /></div>
        <div class="card"><img src="museo.png" /></div>
        <div class="card"><img src="night.jpg" /></div>
        <div class="card"><img src="ricee.jpg" /></div>
        <div class="card"><img src="siar.jpg" /></div>
        <div class="card"><img src="sunst.jpg" /></div>
      </div>
      <div aria-hidden class="group">
        <div class="card"><img src="luzon.jpg" /></div>
        <div class="card"><img src="visayas.jpg" /></div>
        <div class="card"><img src="mindanao.jpg" /></div>
        <div class="card"><img src="cebu.webp" /></div>
        <div class="card"><img src="fort.jpg" /></div>
        <div class="card"><img src="intra.jpg" /></div>
        <div class="card"><img src="intramuros.jpg" /></div>
        <div class="card"><img src="jeep.jpg" /></div>
        <div class="card"><img src="isla.jpg" /></div>
        <div class="card"><img src="manila-298.jpg" /></div>
        <div class="card"><img src="museo.png" /></div>
        <div class="card"><img src="night.jpg" /></div>
        <div class="card"><img src="ricee.jpg" /></div>
        <div class="card"><img src="siar.jpg" /></div>
        <div class="card"><img src="sunst.jpg" /></div>
      </div>
    </div>
    <!--wow the carouselll actually workssss, thanks to that one guy on yt, finally yt did good something to me-->
    <!--now i have to figure out how can i make the image fit and move the carousel on the right part a bit-->
    <div class="baba">
      <button><a href="islandsLuzon.html">Back</a></button>
    </div>
  </body>
</html>

```


``` css
.islabg {
    background: -webkit-linear-gradient(to bottom, rgba(7, 7, 7, 0.762), transparent), url('download.jpg');
    background: linear-gradient(to bottom, rgba(8, 8, 8, 0.766), transparent), url('download.jpg');
    background-size: cover;
    background-attachment: fixed;
    background-position: center;
    height: 500px;
    width: auto;
}

.islaupper {
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

.island-nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.nav-dropdown {
    justify-content: flex-start;
    background-color: rgb(242, 2, 234);
    padding: 1rem;
    position: relative;
}

.dropdown {
    font-size: 15px;
    background: rgb(96, 1, 88);
    color: white;
    width: 200px;
    padding: 10px;
    top: 20%;
    right: 20;
    box-shadow: 0 4px 8px rgba(254, 254, 254, 0.2);
}

nav details a {
    color: white;
    text-decoration: none;
}

.descbox {
    background-color: rgb(122, 65, 117);
    width: 40%;
    padding: 10px;
    border-radius: 30px;
    height: 300px;
}

.main-container {
    display: flex;
    justify-content: center;
    padding: 10px;
    color: rgb(255, 255, 255);
    position: relative;
}

nav .btnn {
    display: inline;
    justify-content: center;
    background-color: transparent;
    margin: 0px;
    padding: 5px;
}

nav span button {
    background-color: transparent;
    border: none;
}

nav span button a {
    text-decoration: none;
    display: inline-block;
    background-color: rgba(135, 3, 102, 0.611);
    color: white;
    padding: 0.5rem 1rem;
    display: block;
}

nav span button a:hover {
    text-decoration: none;
    padding: 5px;
    margin: 5px;
}

.carousel {


    margin: 20px 0 0 0;
    padding: 1%;
    position: relative;
    display: flex;
    overflow-x: auto;
    gap: 1em;
    display: flex;
}

.carousel::-webkit-scrollbar {
    display: none;
}

.group {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 1em;
    animation: spin 30s infinite linear;

}

.card {
    flex: 0 0 200px;

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
    object-fit: contain;
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
