<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>NASA Mars Photos Viewer</title>
	<script src="https://cdn.jsdelivr.net/npm/lightgallery@2.3.0/lightgallery.umd.min.js"></script>
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

    <!--Font Google-->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk&display=swap" rel="stylesheet">
	
    <link rel="stylesheet" type="text/css" href="css/style.css"  />

    <link type="text/css" rel="stylesheet" href="css/lightgallery.css" />

    <!-- lightgallery plugins -->
    <link type="text/css" rel="stylesheet" href="css/lg-zoom.css" />
    <link type="text/css" rel="stylesheet" href="css/lg-thumbnail.css" />
</head>



<div class="container" id="bodyLayout">
    
    <!-- Logo -->
    <div class="row">
        <img class="mx-auto" id="logo" src="img/nasa-logo.svg" alt="NASA">
    </div>

        <form id="s-form">
            <div class="row justify-content-center align-items-end">
                <div class="col-sm-12 col-lg-3 text-center my-3">
                    <label for="numberOfImages" class="form-label ">Number of images:</label>
                    <input type="number" class="form-control" id="numberOfImages">
                </div>
                <div class="col-sm-12 col-lg-3 text-center my-3">
                    <label for="selectedDate" class="form-label ">Select a date:</label>
                    <input type="date" class="form-control" id="selectedDate">
                </div>
                <div id="submitButtonColumn" class="col-sm-12 col-lg-1 text-center my-3">
                    <button id="submitButton" type="submit" class="mx-auto btn btn-primary">Submit</button>
                </div>
            </div>
        </form>
   
    <div class="row">

    </div>
   
    </div>
    
<body>

</body>
</html>