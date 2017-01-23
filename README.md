#JQUERY

jQuery est une bibliothèque JavaScript libre et multi-plateforme créée pour faciliter l'écriture de scripts côté client dans le code HTML. La première version est lancée en janvier 2006 par John Resig.  
C'est donc une grande bibliothèques de fonctions pré-conçues en Javascript, un peu le Bootstrap du JS.  

####Exemple de code en JQuery et en simple JS
	// jQuery
	$(document).ready(function() {
	    // vos scripts
	})

	// Javascript
	document.addEventListener('DOMContentLoaded', function() {
	    // vos scripts
	})
On remarque que l'on écrit beaucoup moins grâce au JQuery.  
  
On remplace le innerHTML par ceci :  
  
	$(function() {
		$('#text-js').html('Texte renseigné par le bais de jQuery');
	});

##Comment signifier que l'on écrit à l'aide du JQuery
Il y a deux façon de programmer à l'aide du JQuery

	jQuery(document).ready(function() {
	// Ici le DOM est prêt
	});

OU

	$(document).ready(function() {
    	// Ici le DOM est prêt
	});

On peux également enlever le (document).ready :  

	$(function() {
    	// Ici le DOM est prêt
	});

##Changement au niveau DOM

Pour les ID

	// Version Javascript
	document.getElementById('sub-footer');

	// Version jQuery
	$('#sub-footer');

Pour les class

	// Version Javascript
	document.getElementsByClassName('box');

	// Version jQuery
	$('.box');

D'autres exemples :   

Définit ou retourne la largeur des éléments sélectionnés

	.width()	

Définit ou retourne la position de la barre de défilement vertical des éléments sélectionnés

	.scrollTop()	

Définit ou retourne une ou plusieurs propriétés de style pour les éléments sélectionnés

	.css()	

Définit ou retourne le contenu des éléments sélectionnés

	.html()	
*LISTE NON EXHAUSTIVE*

##AJAX
Ajax ou Asynchronous JavaScript and XML est une technologie se basant sur l'objet XMLHttpRequest.

XMLHttpRequest est un objet ActiveX ou JavaScript qui permet d'obtenir des données au format XML, JSON, mais aussi HTML, ou encore texte simple à l'aide de requêtes HTTP.

![alt text](https://sutterlity.gitbooks.io/apprendre-jquery/content/img/ajax-model.jpg "Logo Title Text 1")
