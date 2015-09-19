  <!DOCTYPE html>
<html lang="en">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>A Basic Bootstrap Tab Page</title>
    <!-- Bootstrap -->
    <!-- Latest compiled and minified CSS -->
<link href="//maxcdn.bootstrapcdn.com/bootstrap/3.1.1/css/bootstrap.min.css" rel="stylesheet">
   <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
<script src="//maxcdn.bootstrapcdn.com/bootstrap/3.1.1/js/bootstrap.min.js"></script>
</head>
  <body>
<div class="container">
<h1  class="page-header">Sam's Used Cars <small>2008 Nissan Pathfinder</small></h1>
<p class="lead">Tabs are a great way to fit a lot of content on the page at once, without seeming overwhelming at first.</p>
<!-- Nav tabs -->
<ul class="nav nav-tabs" role="tablist">
  <li class="active"><a href="#overview" role="tab" data-toggle="tab">Overview</a></li>
  <li><a href="#photos" role="tab" data-toggle="tab">Photograph</a></li>
  <li><a href="#financing" role="tab" data-toggle="tab">Financing</a></li>
</ul>

<!-- Tab panes -->
<div class="tab-content">
  <div class="tab-pane active" id="overview">
<h2>Nissan Pathfinder</h2>
Body Style: Sport Utility <br/>
Exterior Color: Red / Brown <br/>
Fuel: Gasoline <br/>
Transmission: 5-Speed Automatic <br/>
Drivetrain: 4WD<br/>
Doors: 4<br/>
Engine:  4.0L V6 24V <br/>
  </div>

  <div class="tab-pane" id="photos">
        <a href="/images/nissan.jpg" class="thumbnail">
        <img src="/images/nissan.jpg" alt="Nissan Pathfinder">
      </a>
</div>


  <div class="tab-pane" id="financing">
<h2>No money, no worries!</h2>
     Don't worry, everybody gets financing at Sam's Used Cars.
  </div>

</div>
  </div> 
  </body>

</html>

    
    
