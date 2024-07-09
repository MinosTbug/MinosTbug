<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<title>Pol jeff</title>
	<link href='http://fonts.googleapis.com/css?family=Open+Sans+Condensed:300' rel='stylesheet' type='text/css'>
	<link href='http://fonts.googleapis.com/css?family=Akronim' rel='stylesheet' type='text/css'>
	<link rel="stylesheet" href="css/normalize.css">
	<link rel="stylesheet" href="css/animate.min.css">

	<link rel="stylesheet" href="css/perfil.css">
	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1"/>
	<link rel="stylesheet" href="css/icomon.css">
</head>
<body> 
        
	<div id="loader" >
		<div id="status" class="animated flipInY">
			<div id="red" class="ball"></div>
			<div id="blue" class="ball"></div>
			<div id="green" class="ball"></div>
			<div id="yellow" class="ball"></div>
		</div>
		<div class="loadertext"><strong>Bien</strong><span style='font-weight: 100;'>venido </span>:)</div>
	</div>
	<div id="animatedModal1">
            <div  id="btn-close-modal" class="close-animatedModal1 close-btn"> 
                <span class="icon-cancel"></span>
            </div>
            <div class="modal-content">
            </div>
        </div>

        <div id="animatedModal2">
            <div  id="btn-close-modal" class="close-animatedModal2 close-btn"> 
				<span class="icon-cancel"></span>
            </div>
            <div class="modal-content">
            </div>
        </div>

	<header>
		<div  class="cont_nac_opc">
			<div class="inf_nav">
				PolJefferson
			</div>
			<div id="select" class="select_nav">
				<svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="32" height="32" viewBox="0 0 32 32">
				<path fill="#fff" d="M2 6h28v6h-28zM2 14h28v6h-28zM2 22h28v6h-28z"></path>
				</svg>
			</div>
		</div>
		<nav>
			<ul id="menuId" class="menu">
				<li><a id="modal1" link='personal_profile' href="#animatedModal1">Perfil</a></li>
				<li><a id="modal2" link='personal_data'  href="#animatedModal2">Sobre mi</a></li>
				<li><a link='knowledge' href="#">Conocimientos</a></li>
				<li><a link='contact' href="#">Contactame</a></li>
			</ul>
		</nav>
	</header>
	<section>
		<article class="contenedor personal_profile">
			<div class="photo_user"></div>
			<div class="name_user">PAUL MALPARTIDA ROJAS</div>
			<div class="profession_user">Ingeniero de sistemas / Developer</div>
			<div class="city_user">Cerro de Pasco - Perú</div>
		</article>
		<article class="contenedor personal_data">
			<div class="nombre"> Hola,un poco sobre mí: </div>
			
			<div class="descr">
				<p><span class='icon-tag4'></span><span class='title'><span class="negrita">Desarrollador</span> Web/Backend con ZendFramework/Frontend</span></p>
				<p><span class='icon-tag4'></span>Amante de la tencologia <span class="negrita">Open Source</span> - GNU LINUX <span class='icommon title icon-chn-tencent-03'></span></p>
				<p><span class='icon-tag4'></span>Trabajo en ambiente <span class="negrita">Linux</span> ( Ubuntu - elementary )</p>
				<p><span class='icon-tag4'></span><span class='title'>Soy una persona <span class="negrita">apasionada</span> por todo lo que tiene que ver con <span class="negrita">Internet</span> y las nuevas <span class="negrita">tecnologías</span>. Soy <span class="negrita">autodidacta</span>, y me encanta impartir <span class="negrita">enseñar</span> lo aprendido</span></p>
				<p class="des-int"></p>
				<p><span class='icon-tag4'></span><span class='title'>Trabajo en ambiente <span class="negrita">Windows</span> ( en todas sus versiones )</span></p>
				
			</div>

		</article>
		<article class="contenedor knowledge">
			<p class="nombre">
				 Conocimientos 
			</p>
			
			<div class="dentro">
				<div class="aun_dentro">
					<div class="kl_icon"><p class="icon_mane">Html</p>
						<span class="icon-html5-02"></span>
					</div>
					<div class="kl_icon"><p class="icon_mane">Css</p>
						<span class="icon-css3-02"></span>
					</div>
					<div class="kl_icon"><p class="icon_mane">JavaScript</p>
						<span class="icon-prog-js02"></span>
					</div>
					<div class="kl_icon"><p class="icon_mane">jquery</p>
						<span class="icon-prog-jquery"></span>
					</div>
					<div class="kl_icon"><p class="icon_mane">Php</p>
						<span class="icon-prog-php01"></span>
					</div>
					<div class="kl_icon"><p class="icon_mane">Python</p>
						<span class="icon-prog-python"></span>
					</div>
					<div class="kl_icon"><p class="icon_mane">Illustrator</p>
						<span class="icon-adb-illustrator"></span>
					</div>
					<div class="kl_icon "><p class="icon_mane">PhotoShop </p>
						<span class="icon-adb-photoshop"></span>
					</div>

					<div class="kl_icon no-visto"><p class="icon_mane">ZendFramework</p>
						<span class="icon-prog-zendfrm"></span>
					</div>
					<div class="kl_icon no-visto"><p class="icon_mane">Symfony</p>
						<span class="icon-prog-symfony"></span>
					</div>
					<div class="kl_icon no-visto"><p class="icon_mane">.Net</p>
						<span class="icon-prog-dotnet"></span>
					</div>
					<div class="kl_icon no-visto"><p class="icon_mane">CorelDraw</p>
						<span class="icon-corel-draw"></span>
					</div>
				</div> 
			</div>
			<p class="pos-nav">
				<span id='1pos' class="posactive icon-radio-button-on"></span>
				<span id='2pos' class="icon-radio-button-off"></span>
				<span id='3pos' class="icon-radio-button-off"></span>
				<span id='4pos' class="icon-radio-button-off"></span>
				<span id='5pos' class="icon-radio-button-off"></span>
				<span id='6pos' class="icon-radio-button-off"></span>
				<span id='7pos' class="icon-radio-button-off"></span>
				<span id='8pos' class="icon-radio-button-off"></span>
			</p>
		</article>
		<article class="contact">
			<div class="row">
				<div class="ico-contact">
					<span class="icon-phone"></span>
				</div>
				<div class="ico-desc">
					<span class="title">
						telefono
					</span>
					<p class="info">
						+51 942930440
					</p>
				</div>
			</div>
			<div class="row">
				<div class="ico-contact">
					<span class="icon-mail"></span>
				</div>
				<div class="ico-desc">
					<span class="title">
						contacto
					</span>
					<p class="info">
						poolrojasm@gmail.com
					</p>
				</div>
			</div>
			<div class="row">
				<div class="ico-contact">
					<span class="icon-bookmark"></span>
				</div>
				<div class="ico-desc">
					<span class="title">
						redes
					</span>
					<p class="with-ico">
						<a rel='author' target='_blank' href="https://www.facebook.com/Pol.jeffer?fref=ts"><span class="icon-facebook"></span></a> 
						<a rel='author' target='_blank' href="https://plus.google.com/u/0/107860275200808801866"><span class="icon-google__x2B_"></span></a>
						<a rel='author' target='_blank' href="https://twitter.com/poolMalpartida"><span class="icon-twitter-2"></span></a>
						<a rel='author' target='_blank' href="https://github.com/"><span class="icon-github-01"></span></a>
					</p>
				</div>
			</div>
			<div class="row">
				<div class="ico-contact">
					<span class="icon-heart"></span>
				</div>
				<div class="ico-desc">
					<p class="unico">
						Creado por Paul y fue <span class="negrita">desarrollado</span> con todo el <span class="icon-heart6"></span>
					</p>
				</div>
			</div>
		</article>

	</section>
	<footer><p>PolJeff - All Rights Reserved - 2015</p></footer>
	<div class="topLink">
		<span class=''></span>
	</div>
	<script src="js/jquery.min.js"></script>
	<script src="js/animatedModal.min.js"></script>
	<script src="js/perfil.js"></script>
</body>
</html>
