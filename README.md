# my-first
this is my first repository
<!DOCTYPE html>
<html lang="eng">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<style>
    * {
    margin: 0;
    padding: 0;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

body {

    background-color: black;
    overflow-x: hidden;
}

.main {
    background-image: url("background.jpg");
    background-repeat: no-repeat;
    background-position: center;
    background-size: max(1400px, 100vw);
    height: 97vh;
    width: 100vw;

}

.main .container {
    height: 97vh;
    width: 100vw;
    background-color: black;
    opacity: 0.69;
    position: absolute;
    top: 0;
}

nav {
    position: relative;
    top: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 62px;

    width: 80vw;
    margin: auto;
    position: relative;
    z-index: 10;


}

nav img {
    width: 114px;
}

nav button {
    border: 1px solid white;
    background: transparent;
    color: white;
    height: 40px;
    width: 140px;
    border-radius: 10px;
    font-weight: 400;
    font-size: 15px;
}

.sign {
    background-color: red;
    border: none;
    width: 100px;
    margin-left: 20px;
}

.hero {
    color: white;
    display: flex;
    justify-content: center;
     height:100%; 
    align-items: center;
    flex-direction: column;
    position: relative;
    z-index: 1;
    gap: 25px;
    text-align: center;
}

.hero> :nth-child(1) {
    font-size: 48px;
    font-weight: bolder;
}

.hero> :nth-child(2) {
    font-size: 25px;
    font-weight: bolder;
}

.hero> :nth-child(3) {
    font-size: 17px;
    font-weight: bolder;
}

.email input {

    padding: 7px 101px 8px 14px;
    font-size: 12px;
    border-radius: 4px;
    background-color: rgba(23,23,23,0.7);
    border: 1px solid rgba(235, 231, 231, 0.5);
}

.email button {
    border-radius: 4px;
    background-color: red;
    color: white;
    border: none;
    font-size: 20px;
    font-weight: bold;
    padding: 3px 24px;
}
.seperation{
    height: 11px;
    background-color: gray;
}
.first{
    display: flex;
    justify-content: center;
    color: white;
    max-width: 70vw;
    margin: auto;
    align-items: center;

}

.firstimg img{
    width: 30vw;
}
.firstimg{
    position: relative;
}
.firstimg video{
    position: absolute;
    top: 51px;
    right: 0;
    width: 405px;

}
.first> div{
    display: flex;
    flex-direction: column;
}
section img{
    position: relative;
    z-index: 10;
}
.first> div :nth-child(1){
    font-size: 48px;
    font-weight: bolder;
}
.first> div:nth-child(2){
    font-size: 24px;
    }
</style>

<body>
    <div class="main">
        <nav>
            <span><img width="53" src="hh.svg" alt=""></span>
            <div>
                <button>English</button>
                <button class="sign">Sign In</button>
            </div>
        </nav>
        <div class="container"></div>
        <div class="hero">
            <span>Unlimited movies, TV shows and more</span>
            <span>Watch anywhere. Cancel anytime.</span>
            <span>Ready to watch? Enter your email to create or restart your membership.</span>
            <div class="email"> <input type="email" placeholder="Email address">
                <button>Get Started &gt;</button></div>
        </div>
    </div>
    <div class="seperation"></div>
    <section class="first">
        <div>
           <span> Enjoy on your TV</span>
        <span>Watch on smart TVs, PlayStation, Xbox, Chromecast, Apple TV, Blu-ray players and more.</span>
        </div>
        <div class="firstimg">
            <img src="tv.png" alt="">
            <video src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/video-tv-in-0819.m4v" autoplay loop muted></video>
        </div>
    </section>


</body>

</html>
