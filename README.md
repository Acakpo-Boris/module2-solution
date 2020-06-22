<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Module2-solution</title>
	<link rel="stylesheet" type="text/css" href="css.css">
  <style>
		html {
  font-family: sans-serif;
}
body {
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue", Arial, sans-serif, 
  font-weight: 400;
  line-height: 1.5;
  text-align: left;
}

h2{
  text-align: center;
}

div.container{
  margin-left: 40px;
}

.row{
  margin-top: 80px;
}

p{
  
  border:2px solid black;
  margin-bottom: 15px;
  margin-right: 75px;
  padding-left:5px;
  background-color: gray;
  width: 90%;
  height: 250px;
  font-family: Helvetica;
  color: black;
  overflow: hidden;
}

.container {
 padding-right: 15px;
  padding-left: 15px;
  margin-right: auto;
  margin-left: auto;
}

.row {
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  margin-right: -15px;
  margin-left: -15px;
}

.t1{
	border: 2px solid black;
	background-color: blue;
  border-top: 0px;
}
.t2{
	border: 2px solid black;
	background-color: yellow;
  border-top: 0px;
  color: white;
}

.t3{
	border: 2px solid black;
	background-color: red;
  border-top: 0px;
}

em{
  float: right;
  padding:3px 15px 3px 15px;
  text-transform: uppercase;
}

@media (min-width: 576px) {
  .col-sm {
    min-width: 0;
    max-width: 100%;
  }
.col-sm-1 {
    max-width: 8.333333%;
  }
  .col-sm-2 {
    max-width: 16.666667%;
  }
  .col-sm-3 {
    max-width: 25%;
  }
  .col-sm-4 {
    max-width: 33.333333%;
  }
  .col-sm-5 {
    max-width: 41.666667%;
  }
  .col-sm-6 {
    max-width: 50%;
  }
  .col-sm-7 {
    max-width: 58.333333%;
  }
  .col-sm-8 {
    max-width: 66.666667%;
  }
  .col-sm-9 {
    max-width: 75%;
  }
  .col-sm-10 {
    max-width: 83.333333%;
  }
  .col-sm-11 {
    max-width: 91.666667%;
  }
  .col-sm-12 {
    max-width: 100%;
  }
}


 @media (min-width: 768px) {
  .col-md {
    min-width: 0;
    max-width: 100%;
  }
  .col-md-1 {

    max-width: 8.333333%;
  }
  .col-md-2 {
    max-width: 16.666667%;
  }
  .col-md-3 {
    max-width: 25%;
  }
  .col-md-4 {
    max-width: 33.333333%;
  }
  .col-md-5 {
    max-width: 41.666667%;
  }
  .col-md-6 {
    max-width: 50%;
  }
  .col-md-7 {
    max-width: 58.333333%;
  }
  .col-md-8 {
    max-width: 66.666667%;
  }
  .col-md-9 {
    max-width: 75%;
  }
  .col-md-10 {
    max-width: 83.333333%;
  }
  .col-md-11 {
    max-width: 91.666667%;
  }
  .col-md-12 {
    max-width: 100%;
  }
  }
	</style>
</head>
<body>
	<h2>Our Menu</h2>
<div class="container">
	<div class="row">
		<div class=" col-md-4 col-sm-6">
			<p><em class="t1">Le BYOD</em><br/> Bring Your Own Device, ou BYOD, signifie littéralement "amène ton propre appareil". Il s’agit d’une pratique d’entreprise qui consiste pour l’employé d’une société à utiliser du matériel personnel - smartphone, tablette ou ordinateur - dans l’exercice de sa profession. Egalement appelé "apportez votre propre technologie (BYOT)", ou "apportez votre propre téléphone (BYOP)" ou même "apportez votre propre ordinateur personnel (BYOPC).
			 </p>
		</div>
		<div class="col-md-4 col-sm-6 ">
			<p><em class="t2">Réaction</em><br/>Né en 2009, le BYOD était le résultat de la frustration du personnel, qui devait transporter plusieurs appareils, dont beaucoup étaient supérieurs aux produits technologiques offerts par leurs employeurs. Au fur et à mesure que le coût des produits électroniques grand public diminuait, leur caractère omniprésent les a vus apparaître de plus en plus souvent sur les lieux de travail. De nombreux leaders informatiques ont adopté la tendance, en incorporant le BYOD dans leur stratégie technologiqu.</p><div class="clear"></div>
		</div>
		<div class=" col-md-4 col-sm6">
			<p><em class="t3">Adaptation</em><br/>Face a une telle situation, les entreprise ont dû élaborer une politique BYOD. La rédaction de cette politique BYOD oblige les entreprises à réfléchir avant de libérer leurs employés avec leurs propres smartphones et tablettes sur le réseau de l'organisation. Les questions qui doivent être réglées par le leadership de l'organisation au cours de la phase de planification comprennent: Quels navigateurs Web les employés devraient-ils utiliser? Quels outils de sécurité offrent la meilleure protection pour la gamme d'appareils qui seront autorisés à se connecter au réseau?</p><div class="clear"></div>
		</div>
	</div>
</div>
	
</body>
</html>
