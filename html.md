<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="css/style.css" />
    <link
      rel="stylesheet"
      href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
      integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm"
      crossorigin="anonymous"
    />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
    />
    <title>Document</title>
  </head>
  <body>
    <header id="header">
      <div class="container fluid">
        <div class="logo">
          <img class="applicationLogo" src="assets/appIcon.png" alt="" />
        </div>
        <div class="login">
          <button id="loginButtonID">LOGIN</button>
        </div>
      </div>
    </header>
    <main class="main" id="main">
      <section  onscroll="scrollFunc()" class="visual-welcome-background" id="visual-welcome-background">
        <div  class="container">
          <div  class="slime-caption">
            <h1 class="bold m-16 white new-title">
              CREATE YOUR CV  ONLINE
            </h1>
            <h2 class=" bold m-16 h2-subtitle hide-mobile white">
              Online CV builder, easy to use
            </h2>
            <span class="only-mobile mt-30"></span>
            <ul class="tick-list m-16 white hide-mobile">
              <li>
                <i class="fa fa-check white"></i> Wide variety of CV templates
              </li>
              <li>
                <i class="fa fa-check white"></i> Unique, impressive CV in
                minutes
              </li>
              <li>
                <i class="fa fa-check white"></i> A downloadable and printable CV available in
                PDF.
              </li>
              <li><i class="fa fa-check white"></i> Quick easy formatting</li>
            </ul>

            <div class="row registration-buttons">
              <div class="col-md-12 no-pl-pr col-no-pr mobile-button-create-cv">
                <button
                  
                  class="
                    bold btn button-create-cv-mobile main-register btn-green btn-danger text-uppercase"
                  >Create your CV online
                  </button>
              </div>
            </div>
           
          </div>

          <img style="height: 400px;" class="hidden-mobile image-cv d-none d-sm-block" data-src="https://assets.expresscv.com/images/cv.png" alt="Image de CVs" src="https://assets.expresscv.com/images/cv.png" style="display: inline;">
          
        </div>
        
      </section>
      <section class="home-background">
         <div class="howto">
              <div class="title-section">
                <h2 class="h2">Online CV Builder</h2>
                <p class="subtitle">
                  Write a perfect CV in a few clicks with our templates.
                </p>
              </div>

              <div class="howto-steps">
                <div class="howto-steps-item">
                  <div class="card">
                    <div class="card-header">
                      <img
                        src="https://altresume.com/images/choice.jpg"
                        alt="Choose an exclusive template"
                      />
                    </div>
                    <div class="card-title-it">
                      <span class="number">1</span>
                      <p><strong>Choose an exclusive template</strong></p>
                    </div>
                    <div class="card-text">
                      <p>
                        Altresume offers a wide selection of CV templates that
                        you can easily customise.
                      </p>
                    </div>
                  </div>
                </div>

                <div class="howto-steps-item">
                  <div class="card">
                    <div class="card-header">
                      <img
                        src="https://altresume.com/images/choice-edit.jpg"
                        alt="Build your professional CV"
                      />
                    </div>
                    <div class="card-title-it">
                      <span class="number">2</span>
                      <p><strong>Build your professional CV</strong></p>
                    </div>
                    <div class="card-text">
                      <p>
                        Edit your CV in just a few minutes with our online
                        creation platform.
                      </p>
                    </div>
                  </div>
                </div>

                <div class="howto-steps-item">
                  <div class="card">
                    <div class="card-header">
                      <img
                        src="https://altresume.com/images/choice-download.jpg"
                        alt="Download the perfect CV"
                      />
                    </div>
                    <div class="card-title-it">
                      <span class="number">3</span>
                      <p><strong>Download the perfect CV</strong></p>
                    </div>
                    <div class="card-text">
                      <p>
                        Download your CV in PDF or TXT format, in one click, and
                        finally complete all of your projects
                      </p>
                    </div>
                  </div>
                </div>
              </div>

              <div class="howto-cta text-center">
                <a
                  href="https://app.altresume.com"
                  class="btn btn-green-it text-uppercase text-btn-green-it"
                  style="padding-top: 11px; padding-bottom: 11px"
                  >Create my CV</a
                >
              </div>
            </div>
      </section>
    </main>
    <script src="js/index.js"></script>
  </body>
</html>
