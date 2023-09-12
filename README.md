<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <title>MOVIES APP</title>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <script defer src="https://use.fontawesome.com/releases/v5.1.0/js/all.js" integrity="sha384-3LK/3kTpDE/Pkp8gTNp2gR/2gOiwQ6QaO7Td0zV76UFJVhqLl4Vl3KL1We6q6wR9" crossorigin="anonymous"></script>
    <script src="main.js"></script>
</head>

<body>
    <!-- HEADER -->
    <div class="wrapper">
        <header>
            <div class="netflixLogo">
            <center>    <a id="logo" href="#home"><img src="https://res.cloudinary.com/do4qwwms8/image/upload/v1635419613/website-logo_qwpc3c.png" alt="Logo Image" /></a></center>
            </div>
            <nav class="main-nav">
                <a href="#home">Home</a>
                <a href="#tvShows">TV Shows</a>
                <a href="#movies">Movies</a>
                <a href="#originals">Originals</a>
                <a href="#">Recently Added</a>
            </nav>
            <nav class="sub-nav">
                <a href="#"><i class="fas fa-search sub-nav-logo"></i></a>
                <a href="#"><i class="fas fa-bell sub-nav-logo"></i></a>
                <a href="#">Account</a>
            </nav>
        </header>
    </div>
    <!-- END OF HEADER -->
    <!-- DISPLAY -->
    <div class="home-container" style="background-image: url('https://assets.ccbp.in/frontend/react-js/movies-app/avatar-theatrical-movie-background-v0.png'); background-size: cover; height: 52vh; background-repeat: no-repeat;">
        <div class="home-movie-details-container">
            <h1 class="home-movie-heading">Avatar</h1>
            <p class="home-movie-description">Avatar is a 2009 American epic science fiction film directed, written, produced, and co-edited by James Cameron</p>
            <button type="button" class="home-movie-play-button">
                Play
            </button>
        </div>
    </div>

    <!-- END OF DISPLAY -->
    <!-- MAIN CONTAINER -->
    <section class="main-container">
        <div class="location" id="home">
            <h1 id="home">Popular on Movies App</h1>
            <div class="box">
                <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/no-time-to-die-movie-poster.png" alt="" /></a>
                <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/shang-chi-and-the-legend-of-the-ten-rings-movie-poster.png" alt="" /></a>
                <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/dune-movie-poster.png" alt="" /></a>
                <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/the-suicide-squad-movie-poster.png" alt="" /></a>
                <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/venom-let-there-be-carnage-movie-poster.png" alt="" /></a>
                <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/eternals-movie-poster.png" alt="" /></a>

                <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/army-of-thieves-movie-poster.png" alt="" /></a>
                <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/the-harder-they-fall-movie-poster.png" alt="" /></a>
                <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/halloween-kills-movie-poster.png" alt="" /></a>
                <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/twilight-movie-poster.png" alt="" /></a>
                <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/squid-game-south-korean-movie-poster.png" alt="" /></a>
                <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/the-pursuit-of-happyness-movie-poster.png" alt="" /></a>
            </div>
        </div>

        <h1 id="myList">Trending Now</h1>
        <div class="box">
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/grindhouse-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/clifford-the-big-red-dog-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/titanic-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/avatar-theatrical-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/a-few-good-men-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/king-richard-movie-poster.png" alt="" /></a>
        </div>

        <h1 id="tvShows">TV Shows</h1>
        <div class="box">
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/dexter-new-blood-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/riverdale-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/the-boss-baby-family-business-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/the-protege-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/godzilla-vs-kong-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/demonic-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/cosmic-sin-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/infinite-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/zack-snyders-justice-league-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/the-tomorrow-war-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/the-vault-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/mortal-kombat-international-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/spider-man-advance-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/gunpowder-milkshake-british-movie-poster.png" alt="" /></a>
        </div>

        <h1 id="originals">Originals</h1>
        <div class="box">
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/spider-man-far-from-home-international-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/venom-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/snake-eyes-gi-joe-origins-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/the-addams-family-2-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/luca-movie-poster.png" alt="" /></a>
            <a href=""><img src="https://assets.ccbp.in/frontend/react-js/movies-app/the-amazing-spider-man-movie-poster.png" alt="" /></a>
        </div>
    </section>
    <!-- FOOTER -->
    <footer>
        <div class="logos">
            <a href="#"><i class="fab fa-facebook-square fa-2x logo"></i></a>
            <a href="#"><i class="fab fa-instagram fa-2x logo"></i></a>
            <a href="#"><i class="fab fa-twitter fa-2x logo"></i></a>
            <a href="#"><i class="fab fa-youtube fa-2x logo"></i></a>
        </div>
        <p>Contact US</p>
        <p>Help center</p>
    </footer>
</body>

</html>
