<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF=8">
    <meta name="viewport" content="width=device-width,initial-scale=1,0">
    <title>final exam</title>
    <style>
    body
{
    padding: 0px;
    font-family: 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    -webkit-font-smoothing:antialiased;
    -moz-osx-font-smoothing:antialiased;
    }
h1{
    text-align:center;
}
.center
{
    margin: 0px auto;
}
#pagewrap {
	padding: 5px;
	width: 100%;
	margin: 20px auto;
}
header {
	height: 100px;
	padding: 0 15px;
}
#content {
	width: 28%;
	float: left;
    padding: 5px 15px;
    border: 2px solid black;
    background-color: #989898;
}

#middle {
	width: 28%;
	float: left;
	padding: 5px 15px;
    margin: 0px 5px 5px 5px;
    border: 2px solid black;
    background-color: #989898;
}

#sidebar {
	width: 28%;
	padding: 5px 15px;
    float: left;
    border: 2px solid black;
    background-color: #989898;
}
#content #second{
    border: 2px solid black;
    width: 20%;
    position: relative;
    left:82.4%; 
    top: -7px;
    background: #d49797;
    text-align: center;
}
#middle #second{
    border: 2px solid black;
    width: 20%;
    color:white;
    position: relative;
    left:82.4%; 
    top: -7px;
    background: #c04442;
    text-align: center;
}
#sidebar #second{
    border: 2px solid black;
    width: 20%;
    position: relative;
    left:82.4%; 
    top: -7px;
    background: #e5d198;
    text-align: center;
}
@media screen and (max-width: 768px) {
	#pagewrap {
		width: 100%;
	}
	#content {
		width: 41%;
		padding: 1% 4%;
        background-color:paleturquoise;
	}
	#middle {
		width: 41%;
		padding: 1% 4%;
		margin: 0px 0px 5px 5px;
		float: right;
        background-color:paleturquoise;
	}
	#sidebar {
		clear: both;
		padding: 1% 4%;
		width: auto;
		float: none;
        background-color:paleturquoise;
	}
}
@media screen and (max-width:712px) {
   #content {
		width: auto;
        float: none;
        background-color:palegreen;
	}
	#middle {
		width: auto;
		float: none;
		margin-left: 0px;
        background-color:palegreen;
	}
	#sidebar {
		width: auto;
		float: none;
        background-color:palegreen;
	}
}
@media screen and (max-width: 480px) {
  #sidebar {
        width: auto;
	}
        }
</style>
    <body>
    <h1><strong>Our Menu</strong></h1>

        
<div id="pagewrap">		
<section id="content">
<div id="second">Chicken</div>
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
</section>

<section id="middle">
<div id="second">Beef</div>
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
</section>

<aside id="sidebar">
<div id="second">Sushi</div>
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
</aside>

</div>
</body>
</head>
</html>
