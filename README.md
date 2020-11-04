# module-2

* {
    box-sizing: border-box;
   
}


h1 {
    text-align: center;
    font-size: 1.75em;
}

h2 {
    border: 3px solid black;
    font-size: 1.25em;
    text-align: center;
    float:right;
    padding-left: 30px;
    padding-right: 30px;
    position: relative;
    right: 10px;
    bottom: 5px;
    width: 150px;
    margin-bottom: auto;

}

p {
    margin: 10px;
    border: 3px solid black;
    background-color:gray;
    padding-top: 50px;
    padding-left: 10px;
    padding-right:10px;

}

.chicken {
    background-color:pink;
}

.beef {
    color: white;
    background-color: red;
}

.sushi {
    background-color: yellow;
}


/* Simple Responsive Framework. */
.row {
  width: 100%;
}

/********** Large devices only **********/
@media (min-width: 992px) {

  .col-lg-4 {
    float: left;
  }

  .col-lg-4 {
    width: 33.33%;
  }

}

/********** Medium devices only **********/
@media (min-width: 768px) and (max-width: 991px) {

  .col-md-6, .col-md-12 {
    float: left;
}

  .col-md-6 {
    width: 50%;
  }

  .col-md-12 {
    width: 100%;
  }
}

/********** Small devices only **********/
@media (max-width: 767px) {

.col-sm-12 {
    float: left;
}
.col-sm-12{
    width: 100%;
}

h2 {
    bottom: 15px;
}
}


#index.html
<!DOCTYPE html>
    <link rel="stylesheet" type="text/css" href="styling.css">
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Module 2</title>
</head>


<body>
    <h1>Our Menu</h1>
    <div class="row">
        <div class="col-lg-4 col-md-6">
        <h2 class="chicken">Chicken</h2>
            <p>Bacon ipsum dolor amet in anim tail sint, sirloin incididunt prosciutto swine ribeye. Strip steak ea in incididunt, ground round salami chuck sausage eu lorem pork belly reprehenderit occaecat laborum. Id reprehenderit cupidatat aute kielbasa nisi. </p>
        </div>

        <div class="col-lg-4 col-md-6">
        <h2 class="beef">Beef</h2>
            <p>Bacon ipsum dolor amet in anim tail sint, sirloin incididunt prosciutto swine ribeye. Strip steak ea in incididunt, ground round salami chuck sausage eu lorem pork belly reprehenderit occaecat laborum. Id reprehenderit cupidatat aute kielbasa nisi. </p>
        </div>

        <div class="col-lg-4 col-md-12">
        <h2 class="sushi">Sushi</h2>
            <p>Bacon ipsum dolor amet in anim tail sint, sirloin incididunt prosciutto swine ribeye. Strip steak ea in incididunt, ground round salami chuck sausage eu lorem pork belly reprehenderit occaecat laborum. Id reprehenderit cupidatat aute kielbasa nisi. </p>
        </div>
    </div>

</body>
</html>
