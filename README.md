# thpgoogle

<header id="tete">
		<div id="bloc_haut_gauche">
			<p><a class="gmail" href="https://accounts.google.com/">Gmail</a></p>
			<p class="liens_haut_images"><a class="gmail" title="Google apps" href="https://www.google.fr/imghp?hl=en&tab=wi">Images</a></p>
			<p><img src="images/carre.png" id="carre" alt="apps google"></p>
			<input type="button" value="Connexion" name="Connexion" id="connexion">
		</div>
	</header>


#tete
{
    position: absolute;
    right: 0;
    width: 100%;
}

#bloc_haut_gauche
{
    display: flex;
    align-items: center;
    float: right;

}

.liens_haut_images
{
    padding: 0 15px;
}

.gmail
{
	text-decoration: none;
	opacity: 1.0;
	color: black
}

.gmail:hover
{
	text-decoration: underline;
	opacity: 0.7;
}

#carre
{
	width: 16px;
	height: 16px;
	opacity: 0.6;
	padding: 0 7px;
}

#carre:hover
{
	opacity: 1.0;
}

#connexion
{
	width: 93px;
	height: 30px;
	background-color: #4986EA;
	border: 1px solid #4986EA;
	border-radius: 2px;
	color: white;
	font-size: 12.7px;
	font-weight: bold;
	margin-left: 15px;
	margin-right: 30px;
}

#connexion:hover
{
	box-shadow: 0px 1px 0px #e4e4e4;
}

