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
                    <article class="art1">
                        <main><img id="img" src="..." alt="Artikel 2"></main>
                        <aside>Extra info</aside>
                    </article>
                </td>
                <td>
                    <article class="art1">
                        <main><img id="img" src="..." alt="Artikel 3"></main>
                        <aside>Extra info</aside>
                    </article>
                </td>
            <tr>
                <td>
                    <article class="art1">
                        <main><img id="img" src="..." alt="Artikel 4"></main>
                        <aside>Extra info</aside>
                    </article>
                </td>
                <td>
                    <a><article class="art1">
                        <a href="Artikel 1">
                        <main><img id="img" src="..." alt="Artikel 5"></main>
                        <aside>Extra info</aside>
                        </a></article>
                </td>
            </a>
            </tr>
            </tr>
        </table>
        
    </body>

    </html>
