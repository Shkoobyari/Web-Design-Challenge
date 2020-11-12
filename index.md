<!DOCTYPE html>
<html lang="en">
  <head>
    <head>
      <meta charset="utf-8" />
      <meta
        name="viewport"
        content="width=device-width, initial-scale=1, shrink-to-fit=no"
      />
      <!-- <meta name="description" content="" /> -->
      <!-- <meta name="author" content="" /> -->
      <!-- <link rel="icon" href="../../../../favicon.ico" /> -->

      <title>Latitude</title>

      <script
        src="https://code.jquery.com/jquery-3.1.1.slim.js"
        integrity="sha256-5i/mQ300M779N2OVDrl16lbohwXNUdzL/R2aVUXyXWA="
        crossorigin="anonymous"
      ></script>

      <link
        href="https://fonts.googleapis.com/css2?family=Merriweather:wght@300&display=swap"
        rel="stylesheet"
      />
      <!-- Bootstrap core CSS -->
      <link href="./bootstrap/css/bootstrap.min.css" rel="stylesheet" />

      <!-- Custom styles for this template -->
      <link href="style.css" rel="stylesheet" />
    </head>
  </head>
  <body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a
        class="navbar-brand latitude-font latitude-brand"
        href="landing-page.html"
        >Latitude</a
      >
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              id="navbarDropdown"
              role="button"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              Plots
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
              <a class="dropdown-item" href="vis-max-temp.html"
                >Max Temperature</a
              >
              <a class="dropdown-item" href="vis-humidity.html">Humidity</a>
              <a class="dropdown-item" href="vis-cloudiness.html">Cloudiness</a>
              <a class="dropdown-item" href="vis-wind-speed.html">Wind Speed</a>
            </div>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="comparisons.html"
              >Comparison <span class="sr-only">(current)</span></a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link" href="data.html">Data</a>
          </li>
        </ul>
      </div>
    </nav>
    <div class="container">
      <div class="row">
        <div class="col-md-8">
          <p class="page-header latitude-font">Summary: Latitude vs. X</p>
          <hr class="header-divider" />
          <p class="landing-text">
            This project aims to explain the relationship between latitude and
            four different environmental factors. In other words, as you go from
            the southern points on the earth to the northern points, is there a
            noticable relationship between the latitude and these four weather
            points. <br />
            <br />
            The four factors I study are humidity, cloudiness, wind speed, and
            temperature. The dataset is taken from the OpenWeatherAPI and
            contains data for over 500 cities at different latitudes. The
            dataset is plotted using Matplotlib.
          </p>
        </div>
        <div class="col-md-4">
          <p class="page-header latitude-font">Visualizations</p>
          <hr class="header-divider" />
          <a href="vis-max-temp.html">
            <img
              src="assets/Fig1.png"
              alt="Lat vs Temp Graph"
              class="landing-graph"
            />
          </a>
          <a href="vis-humidity.html">
            <img
              src="assets/Fig2.png"
              alt="Lat vs Temp Graph"
              class="landing-graph"
            />
          </a>
          <a href="vis-cloudiness.html">
            <img
              src="assets/Fig3.png"
              alt="Lat vs Temp Graph"
              class="landing-graph"
            />
          </a>
          <a href="vis-wind-speed.html">
            <img
              src="assets/Fig4.png"
              alt="Lat vs Temp Graph"
              class="landing-graph"
            />
          </a>
        </div>
      </div>
    </div>
    <script
      src="https://code.jquery.com/jquery-3.2.1.slim.min.js"
      integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN"
      crossorigin="anonymous"
    ></script>
    <script>
      window.jQuery ||
        document.write(
          '<script src="/bootstrap/js/jquery-slim.min.js"><\/script>'
        );
    </script>
    <script src="bootstrap/js/popper.min.js"></script>
    <script src="bootstrap/js/bootstrap.min.js"></script>
    <script src="bootstrap/js/vendor/holder.min.js"></script>
  </body>
</html>
