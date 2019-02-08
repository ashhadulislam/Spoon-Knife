<!DOCTYPE HTML>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
        <!--[if lte IE 8]><script src="assets/js/ie/html5shiv.js"></script><![endif]-->
    <link rel="stylesheet" href="assets/css/main.css" />
    <!-- <script src="https://code.jquery.com/jquery-2.2.4.min.js"></script> -->
    <!-- Latest compiled and minified CSS -->
    <!-- <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous"> -->
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
        <!-- <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous"> -->

  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>







    <!-- Optional theme -->
<!--     <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css" integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp" crossorigin="anonymous">
 -->
    <!-- Latest compiled and minified JavaScript -->
<!--     <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script> -->
{% block header %}{% endblock %}
</head>

<body>

<!-- 
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="#">
                            <img src="https://upload.wikimedia.org/wikipedia/en/thumb/1/18/DBS_Bank_Logo.svg/320px-DBS_Bank_Logo.svg.png" width="80" height="33" class="d-inline-block align-top" alt="DBS Logo">
                            </a>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Home
                                            <span class="sr-only">(current)</span>
                                        </a>
                </li>
                <li class="nav-item">
                    <a target="_blank" class="nav-link" href="https://gitlab.dev.apps.cs.sgp.dbs.com/kirankunapuli/sentiment-analysis-framework">Sentiment Analysis - Gitlab</a>
                </li>
                <li class="nav-item">
                    <a target="_blank" class="nav-link" href="https://gitlab.dev.apps.cs.sgp.dbs.com/aditya1/Document_Classification">Document Classification - Gitlab</a>
                </li>
            </ul>
        </div>
    </nav> -->



<nav class="navbar navbar-default">
  <div class="container-fluid">
    <div class="navbar-header">
      <a class="navbar-brand" href="http://10.91.132.110:5011">SSB DS Framework Visualization</a>
      <a class="navbar-brand" href="#">
                            
    </div>
    <ul class="nav navbar-nav">
      <li class="active"><a href="http://10.91.132.110:5011">Home</a></li>
      <li><a href="http://10.91.132.110:5011/getAdvViz">See Multiple Models</a></li>
      <li><a href="http://10.91.132.110:5011/selectModelPage">Execute Model</a></li>
      <li><a href="http://10.91.132.110:5011/compareViz">Compare Model with Stack</a></li>
      <li><a href="http://10.91.132.110:5011/prodView">Prod View</a></li>      
    </ul>
    <ul class="nav navbar-nav navbar-right">
      <li><a href="#"><span class="glyphicon glyphicon-user"></span> Sign Up</a></li>
      <li><a href="#"><span class="glyphicon glyphicon-log-in"></span> Login</a></li>
      <li><img class ="glyphicon" src="https://www.soundgrovemusic.sg/wp-content/uploads/2017/02/dbs-bank-logo.jpg" width="100" height="65" class="d-inline-block align-middle" alt="DBS Logo"></li>
    </ul>
  </div>
</nav>




<!--     <div class="container">
        <a href="http://localhost:5011" class="btn btn-info" role="button">Home</a>
        <a href="http://localhost:5011/getAdvViz" class="btn btn-info" role="button">See Multiple Models</a>
        <a href="http://localhost:5011/selectModelPage" class="btn btn-info" role="button">Execute Model</a>
        <a href="http://localhost:5011/compareViz" class="btn btn-info" role="button">Compare Model with Stack</a>


    </div> -->

    <div class="container">
        {% block content %}{% endblock %}
    </div>

    

</body>
    <footer>
        {% block other_footers %}{% endblock %}
    </footer>

</html>
