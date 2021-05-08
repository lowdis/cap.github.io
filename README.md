# cap.github.io
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>controle html/css</title>
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
<style type="text/css" media="all">
*
{
	margin: 0;
	padding: 0;

}


.cadre
{
	margin: auto;
	width: 30%;
	border: 1px solid grey;
	text-align: left;
	padding-bottom: 40px;
	padding-left: 90px;
	position: relative;
	padding-top: 10px;
	

}
.cadre label
{
	margin-left: 8px;
	font-family: Georgia, 'Times New Roman', Times, serif;
    
}
.cadre input[type=text]
{
	margin: 10px;
	position: relative;
	left: 1px;
}

.cadre input[type=submit]
{
	background-color: blue;
	font-size: 15px;
	color: white;
	border-radius:5px;
	border: 2px solid blue; 
   padding: 10px;
   margin-left: 7px;
   cursor: pointer;
}
.cadre input[type=reset]
{
	font-family: sans-serif;
	font-size: 15px;
	color: red;
	border-radius:5px;
	border: 3px solid red; 
   padding: 09px;
  margin-left: 30px;
  cursor: pointer;
}

.titre
{
	text-align: center;
	border: 1px solid grey;
	width: 39%;
  position: relative;
  margin-left: 297px;
  background-color: rgb(241, 234, 234);
  border-radius: 5px 5px 0px 0px;
  margin-top: 40px;
  padding-top: 30px;
}
.titre h3
{
	font-size: 20px;
	font-family: Georgia, 'Times New Roman', Times, serif;
    
}

 

.even 
{
     border: 15px solid blue;
	width: 95%; 
	margin-left: 20px;
	background-color: blue;
}


 .even #ac

{
	border: 1px solid blue;
    background-color: white;
	width: 60px;
   padding: 10px;
   border-radius: 5px;
} 

.even #HT
{
	
	border: 1px solid white;
	margin-left: 20px;
	padding: 10px;
	border-radius: 5px;
    color: black;

} 
.even #CS
{
	border: 1px solid white;
	margin-left: 20px;
	padding: 10px;
	border-radius: 5px;
	padding-right: 10px;
	color: black;
}
.even #AD
{
  border: 1px solid white;
	margin-left: 20px;
	padding: 10px;
	border-radius: 5px;
	padding-right: 10px;
	color: black;	
}

.even #Rep
{
	margin-left: 160px;
	padding: 10px;
	border-radius: 5px;
	color: black;
}

h1
{
	text-align: center;
}
.even #search
{
	padding: 10px;
	border-radius: 5px;
	border: 1px solid white;
	margin-left: 20px;
	padding-right: 30px;
	cursor: pointer;
}
.even label:hover
{
	background-color: white;
}
.fa
{
  margin-left: 10px;
  color: black;
}

.footer
{
    border: 1px solid black;
	width: 100%; 

	background-color: skyblue; 
}
.footer a
{
	color: blue;
	margin-left: 350px;
}
.footer p
{
    margin-left: 350px;
    font-size: 20px;
}
.footer .fa
{
    margin-left: 20px;
    color: blue;
    font-size: 15px;
}
#dec h3
{
    margin-left: 620px;
    position: relative;
    bottom: 80px;
}
#dec .fa
{
    color: red;
    
}
#dec p
{
    position: relative;
    bottom: 110px;
    font-size: 10px;
    margin-left: 70px;
}
#dec p,.fa
{
    font-size: 15px;
    color: black;
}

</style>
</head>
<body>
	<div class="even">
     	<label id="ac">Accueil</label>
     	<label id="HT">HTML</label>
        <label id="CS">CSS</label>
        <label id="AD">Aide</label>
       <input type="search" name="" id="Rep" placeholder="Recherche....">
       <input type="button" name="" id="search" value="Recherche"><i class="fa fa-search"></i>
    </div>
      <h1>Bienvenue sur mon formulaire</h1>
      
  <div class="titre">
  <h3>Adherez a notre communauté</h3>
  </div>
  <form>
  	<div class="cadre">
  	<label>Nom</label> <br>
  	<input type="text" name=" nom" maxlength="20" id="nom"> <br>
   <label>prenom</label> <br>
    <input type="text" name="prenom" maxlength="20" id="prenom"> <br>
    <label>Numero</label> <br>
    <input type="text" name="tel" maxlength="20" id="tel"> <br>
    <label>Email</label> <br>
    <input type="text" name="email" id="mail" maxlength="20"> <br> <br>
    <input type="submit" name="" value="Envoyer">
    <input type="reset" name="" value="Reset">

  	</div>
  </form>
  <!----- section pieds de page-----> 
  <div class="footer">
   	<p>Visitez un site</p><br>
    <a href="https://www.facebook.com">facebook<i class="fa fa-facebook-official"></i></a><br>
    <a href="http://www.whatsapp.com">whatsapp web<i class="fa fa-whatsapp"></i></a><br>
    <a href="https://www.Gmail.com">Gmail<i class="fa fa-envelope"></i></a><br>
    <a href="https://www.twitter.com">twitter<i class="fa fa-twitter"></i></a><br>
    <a href="https://www.Opera.com">Opera<i class="fa fa-opera"></i></a><br>
       <div id="dec">
          <h3>realiser avec <i class="fa fa-heart-o"></i>juste pour vous</h3> 
          <p>Tel: <i class="fa fa-phone"></i>674491694/691708308</p><br />
          <p>Adresse: <i class="fa fa-map-marker"></i>Douala yassa</p>
       </div>
  </div>
 </body>
</html>
