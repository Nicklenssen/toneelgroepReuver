# toneelgroepReuver
try-out site acting group 
<!--bootstrap framework setup oefening -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Nick's travels</title>
    <link rel="stylesheet" href="../css/reizen.css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
</head>
<body>
    <!--Eerst de header met een navigatie-bar-->
    <header class="container">
        <div class="row">
            <h1 class="col-sm-4 text-center">NICK's WORLD of TRAVEL</h1>
            <nav class="col-sm-8 text-right" >
                <a href="../html/personal.html">Persoonlijk</a>
          <a href="../html/portofolio.html">Portfolio</a>
          <a href="../html/designsystem.html">Design</a>
          <a href="../html/reizen.html">Reizen</a>
          <a href="../html/cv.html">CV</a>
          <a href="../index.html">Start</a>
            </nav>
        </div>
    </header>
    <!--Jumbotron als eye-catcher. het plaatje wordt in CSS toegevoegd-->
    <section class="jumbotron">
        <div class="container">
            <div class="row text-center">
                <h2>Japan</h2>
                <h3>A journey to the far East</h3>
            </div>
        </div>
    </section>
    <!--een sectie aanvullende informatie -->
    <section class="container">
        <div class="row">
            <figure class="col-sm-4">plaatje GREECE</figure>
            <figure class="col-sm-4">plaatje Portugal</figure>
            <figure class="col-sm-4">plaatje Italy</figure>
        </div>
        <div class="row">
            <figure class="col-sm-4">plaatje Egypte</figure>
            <figure class="col-sm-4">plaatje Germany</figure>
            <figure class="col-sm-4">Other</figure>
        </div>
    </section>
    <!--buttons maken-->
    <div class="row text-center">
        <a class="btn btn-primary" href="../html/personal.html">Personal-page</a>
        <a class="btn btn-secondary" href="../index.html">Home</a>
    </div>
<!--footer-->
    <footer class="container">
        <div class="row">
            <p class="col-sm-4">Nicks World</p>

            <ul class="col-sm-8">
                <li class="col-sm-1">
                    <img src="https://s3.amazonaws.com/codecademy-content/projects/make-a-website/lesson-4/facebook-grey.svg" alt="facebook">
                </li>
                <li class="col-sm-1">
                    <img src="https://s3.amazonaws.com/codecademy-content/projects/make-a-website/lesson-4/twitter-grey.svg" alt="">
                </li>
                <li class="col-sm-1">
                    <img src="https://s3.amazonaws.com/codecademy-content/projects/make-a-website/lesson-4/instagram-grey.svg" alt="">
                </li>
                <li class="col-sm-1">
                    <img src="https://s3.amazonaws.com/codecademy-content/projects/make-a-website/lesson-4/medium-grey.svg" alt="">
                </li>
            </ul>
        </div>

    </footer>
</body>
</html>
