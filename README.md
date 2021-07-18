# sofiaSkip to content
Michaelxk
/
Xk-Budget
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Xk-Budget/index.html
@Michaelxk
Michaelxk ready
 1 contributor
60 lines (53 sloc)  1.98 KB
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Xk-budget</title>
    <link rel="stylesheet" href="css/styles.css" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css"
    />
    <!-- Compiled and minified JavaScript -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.13.0/css/all.css"
      integrity="sha384-Bfad6CLCknfcloXFOyFnlgtENryhrpZCe29RTifKEixXQZ38WheV+i/6YWSzkz3V"
      crossorigin="anonymous"
    />
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.14.0/css/all.css" integrity="sha384-HzLeBuhoNPvSl5KYnjx0BT+WB0QEEqLprO+NBkkk5gbc67FTaL7XIGa2w1L0Xbgc" crossorigin="anonymous">
  </head>
  <body>
    
    <nav class="navbar blue z-depth-4">
      <h2>Xk-budget</h2>
    </nav>

    <div class="main">
      <form id="vacationCalc">
        <input type="text" placeholder="Destiny" id="destiny" required />
        <input type="number" placeholder="Budget" id="budget" required />
        <input
          type="number"
          placeholder="Acomodation"
          id="acomodation"
          required
        />
        <input type="number" placeholder="Transport " id="transport" required />
        <input type="number" placeholder="Food" id="food" required />
        <input type="submit" value="Calculate" class="btn blue z-depth-4" />
      </form>
    </div>

    <div class="container">
      <div class="icons">
        <h5><i class="fas fa-plane"></i></h5>
        <h5><i class="fas fa-wallet"></i></h5> 
        <h5><i class="fas fa-money-bill-wave-alt"></i></h5>  
      </div>
      
      <div class="data">
        <div class="result" id="result"></div>
      </div>
    </div>



    <script src="js/scripts.js"></script>
  </body>
</html>
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
Loading complete
