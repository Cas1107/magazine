<DOCtype html>
    <html>

    <head>
        <title>Website voor magazine.</title>

        <link rel="stylesheet" href="css/style.css">
        <!-- <link rel="htmlsheet" href="pitch.html"> -->
        <script>
            function toggle() {
                var x = document.getElementById("myTopnav");
                var t = document.getElementById("hamburger");
                if (x.className === "topnav") {
                    x.className += "responsive";
                    t.className = "icon open";

                } else {
                    x.className = "topnav";
                    t.className = "icon close";
                }
            }
        </script>
    </head>

    <body>

        <nav>
            <ul class="topnav" id="myTopnav">
                <li><a class="logo" href="auteursrecht">LooptyLoop</a></li>
                <li><a href="informeren">informeren</a></li>
                <li><a href="tutorial">tutorial</a></li>
                <li><a href="betogend">betogend</a></li>
                <li><a href="auteursrecht">auteursrecht</a></li>
            </ul>
        </nav>

        <div class="icon" id="myIcon">
            <a href="#" onclick="toggle()">&#9776</a>
        </div>


        <article class="art0">
            <main><img id="img" src="..." alt="Artikel 1"></main>
            <aside>Extra info</aside>
        </article>
        <table>
            <tr>
                <td>
                    <a>
                        <article class="art1">
                            <a href="Artikel 1">
                                <main><img id="img" src="..." alt="Artikel 2"></main>
                                <aside>Extra info</aside>
                            </a>
                        </article>
                    </a>
                </td>
                <td>
                    <a>
                        <article class="art1">
                            <a href="Artikel 2">
                                <main><img id="img" src="..." alt="Artikel 3"></main>
                                <aside>Extra info</aside>
                            </a>
                        </article>
                    </a>
                </td>
                </tr>
            <tr>
                <td>
                    <a>
                        <article class="art1">
                            <a href="Artikel 3">
                                <main><img id="img" src="..." alt="Artikel 4"></main>
                                <aside>Extra info</aside>
                            </a>
                        </article>
                    </a>
                </td>
                <td>
                    <a>
                        <article class="art1">
                            <a href="Artikel 4">
                                <main><img id="img" src="..." alt="Artikel 5"></main>
                                <aside>Extra info</aside>
                            </a>
                        </article>
                    </a>
                </td>
            <tr>
                <td>
                    <a>
                        <article class="art6">
                            <a href="Artikel 1">
                                <main><img id="img" src="..." alt="Artikel 6"></main>
                                <aside>Extra info</aside>
                            </a>
                        </article>
                    </a>
                </td>
            </tr>
            <tr>
                <td>
                    <a>
                        <article class="art6">
                            <a href="Artikel 2">
                                <main><img id="img" src="..." alt="Artikel 7"></main>
                                <aside>Extra info</aside>
                            </a>
                        </article>
                    </a>
                </td>
                <td>
                    <a>
                        <article class="art6">
                            <a href="Artikel 3">
                                <main><img id="img" src="..." alt="Artikel 8"></main>
                                <aside>Extra info</aside>
                            </a>
                        </article>
                    </a>
                </td>
                <td>
                    <a>
                        <article class="art6">
                            <a href="Artikel 4">
                                <main><img id="img" src="..." alt="Artikel 9"></main>
                                <aside>Extra info</aside>
                            </a>
                        </article>
                    </a>
                </td>
                <td>
                    <a>
                        <article class="art6">
                            <a href="Artikel 1">
                                <main><img id="img" src="..." alt="Artikel 10"></main>
                                <aside>Extra info</aside>
                            </a>
                        </article>
                </td>
                <td>
                    <a>
                        <article class="art6">
                            <a href="Artikel 2">
                                <main><img id="img" src="..." alt="Artikel 11"></main>
                                <aside>Extra info</aside>
                            </a>
                        </article>
                </td>
                <td>
                    <a>
                        <article class="art6">
                            <a href="Artikel 3">
                                <main><img id="img" src="..." alt="Artikel 12"></main>
                                <aside>Extra info</aside>
                            </a>
                        </article>
                    </a>
                </td>
            </tr>

        </table>

    </body>

    </html>



STYLE/////


    table{
  margin: 0;
}
article a{
  text-decoration: none;
  color: black;
}
article {
  box-shadow: 0px 0px 5px black;
  width: 550px;
  margin: 30;
  margin-right: 0;
  padding: 0;
  display: block;
  border-radius: 8px ;
}

main {
  width: 100%;
  height: 350px;
}

aside {
  width: 100%;
  height: 80px;
  background-color: rgb(189, 189, 189);
}

.art1{
 width: 200px;
 float: left;
}

.art1 main{
  height: 120px;
 }

 .art1 aside{
  height: 50px;
}

.art6{
  width: 200px;
 }
 
.art6 main{
   height: 200px;
  }
 
.art6 aside{
  height: 100px;
 }

.art6 {
  float: left;
}

button {
width: 300px;;
}

body {
  margin: 0;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

img {
  max-width: 100%;
}

.art0 {
  float: left;
}

nav{
  margin-bottom: 30px;
 } 

ul.topnav {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #db3304;
}

ul.topnav li {
  float: left;
  width: 18%;
  text-align: center;
}

ul.topnav li a{
display: block;
color: #ffffff;
padding: 14px 16px;
text-decoration: none;
font-size: 17px;
}

.icon{
  display: none;
}

.logo{
  color:white;
  float: left;
  font-family: Georgia, 'Times New Roman', Times, serif;
}
@media screen and (max-width: 600px) {
  ul.topnav {
      display: none;
  }
  div.icon {
      display: inline-block;
      padding: 5px;
      font-size: 18px
  }
  div.icon {
      display: inline-block;
      padding: 5px;
      font-size: 18px
  }

  ul.topnav.responsive li {
  display: block;
  }
  ul.topnav.responsive li {
      width: 100%;
      clear:both;
      text-align: center;
  }
}

