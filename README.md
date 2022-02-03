<style type="text/css">
	
/* Измененные стили темы */

	header {
		background: #051F32 !important;
	}

	h3 {
		margin-top: 10px !important; 
	}

	a {
		color: #474747;
		transition: all 0.5s ease 0s;
	}

	a:hover {
		text-decoration: none;
		color: #0D70A3;
	}

	a:visited {
	text-decoration: none;
	}

	a:focus,
	a:active {
	outline: none;
	}

	aside#sidebar {
		display:none !important;
	}

	#main-content {
    float: none;
    width: 100% !important;
	}

	#main-content h3:before, #main-content h2:before {
		padding-right: 0;
    	margin-left: 0;
    	content: none;
	}

/* Собственные стили */

	.about__row {
		display:flex;
		align-items:center;
	}

	.about__myphoto {
		position:relative;
		margin: 0px 20px 20px 0px; 
		flex: 0 0 250px;
		height: 290px;	
	}

	.about__img {
		position: absolute;
    	width: 100%;
    	height: 100%;
    	top: 0;
    	left: 0;
    	-o-object-fit: cover;
    	object-fit: cover;
	}

	.startup__title {
		text-align:center;
		font-size: 30px !important;
		margin: 80px 0 50px 0;
	}

	.startup__row {
		display:flex;
	}

	.startup__img {
		position:relative;
		flex: 0 0 250px;
		height: 290px;
		margin: 0 20px 0 0;
	}

	.startup__img>img {
		position: absolute;
    	width: 100%;
    	height: 100%;
    	top: 0;
    	left: 0;
    	-o-object-fit: cover;
    	object-fit: cover;
	}

	span {
		font-style:italic;
	}

/* Медиа запросы */

	@media (max-width:768px) {
		.about__row {
			flex-direction:column;
		}
		.about__myphoto {
			margin: 0px 0px 10px 0px; 
			flex: 0 0 290px;
			width: 250px;	
		}
		.startup__row {
			flex-direction:column;
		}
		.startup__img {
			flex: 0 0 250px;
			width: 100%;
			margin: 0 0 10px 0;
		}
		.startup__title {
			margin: 50px 0 50px 0;
		}
	}

	@media (max-width: 424px) {
		.about__myphoto {
			flex: 0 0 240px;
			width: 200px;	
		}
	}
</style>

<!-- Блок краткой информации обо мне -->

<div class="about__row">
	<div class="about__myphoto"><img class="about__img" src="img/myphoto.jpg"/></div>
	<div class="about__description">
		<h3> About me </h3>
		<p>Я Junior Frontend Web Developer. Верстаю лендинги и небольшие статические сайты. Углубленно изучаю фреймворк REACT, алгоритмы, ООП.</p>
		<p>В настоящее время ищу работу в IT компании и команду для совместной веб разработки.</p>
		<p>Увлекаюсь медитацией, йогой, горным трекингом и играю на гитаре, африканском барабане джембе.</p>
	</div>
</div>

<!-- Блок контактов -->

<h3>Follow me:</h3>

[![instagram](https://img.shields.io/badge/INSTARAM-7A8573?style=flat&logo=instagram&logoColor=B83092)](https://www.instagram.com/seignior.anlarion/)
[![vk](https://img.shields.io/badge/VKONTACTE-7A8573?style=flat&logo=vk&logoColor=5181B8)](https://vk.com/larionov66)
[![twitter](https://img.shields.io/badge/TWITTER-7A8573?style=flat&logo=twitter&logoColor=209BF3)](https://twitter.com/larionov_anton1)
[![telegramm](https://img.shields.io/badge/TELEGRAMM-7A8573?style=flat&logo=telegram&logoColor=1D97C9)](https://t.me/AntonLarionov1)
[![phone](https://img.shields.io/badge/PHONE_+7_(988)_570_72_57-7A8573?style=flat&logo=apple&logoColor=D9D9D9)](tel:+79885707257)
[![email](https://img.shields.io/badge/EMAIL_larionovanton05@gmail.com-7A8573?style=flat&logo=gmail&logoColor=F44336)](mailto:larionovanton05@gmail.com)

<!-- Блок стека технологий -->

<h3>Tech Stack:</h3>

![html](https://img.shields.io/badge/HTML5-7A8573?style=flat&logo=html5&logoColor=E34F26)
![css](https://img.shields.io/badge/CSS3-7A8573?style=flat&logo=css3&logoColor=117B11)
![scss](https://img.shields.io/badge/SCSS-7A8573?style=flat&logo=sass&logoColor=D05385)
![js](https://img.shields.io/badge/JAVASCRIPT-7A8573?style=flat&logo=javascript&logoColor=F7E01D)
![jq](https://img.shields.io/badge/JQUERY-7A8573?style=flat&logo=jquery&logoColor=193657)

<h3>Tools:</h3>

![git](https://img.shields.io/badge/GIT-7A8573?style=flat&logo=git&logoColor=DF4C37)
![github](https://img.shields.io/badge/GITHUB-7A8573?style=flat&logo=github&logoColor=000000)
![vscode](https://img.shields.io/badge/VSCODE-7A8573?style=flat&logo=Visualstudio&logoColor=0278CB)
![gulp](https://img.shields.io/badge/GULP-7A8573?style=flat&logo=gulp&logoColor=E84C51)
![photoshop](https://img.shields.io/badge/PHOTOSHOP-7A8573?style=flat&logo=adobephotoshop&logoColor=001E36)
![avocode](https://img.shields.io/badge/AVOCODE-7A8573?style=flat&logo=adobephotoshop&logoColor=00BD87)
![prepros](https://img.shields.io/badge/PREPROS-7A8573?style=flat&logo=webpack&logoColor=20C4E1)



<!-- Блок проекта startup -->

<h2 class="startup__title">Portfolio</h2>
<h3><a href="https://larionov-anton.github.io/startup/">Startup</a></h3>

[![github](https://img.shields.io/badge/View on GITHUB-0189B4?style=flat&logo=github&logoColor=000000)](https://github.com/Larionov-Anton/startup)

![html](https://img.shields.io/badge/HTML5-701E16?style=plastic&logo=html5&logoColor=E34F26)
![css](https://img.shields.io/badge/CSS3-701E16?style=plastic&logo=css3&logoColor=117B11)
![scss](https://img.shields.io/badge/SCSS-701E16?style=plastic&logo=sass&logoColor=D05385)
![js](https://img.shields.io/badge/JAVASCRIPT-701E16?style=plastic&logo=javascript&logoColor=F7E01D)
![jq](https://img.shields.io/badge/JQUERY-701E16?style=plastic&logo=jquery&logoColor=193657)
![git](https://img.shields.io/badge/GIT-701E16?style=plastic&logo=git&logoColor=DF4C37)
![vscode](https://img.shields.io/badge/VSCODE-701E16?style=plastic&logo=Visualstudio&logoColor=0278CB)
![prepros](https://img.shields.io/badge/PREPROS-701E16?style=plastic&logo=webpack&logoColor=20C4E1)
![marsy](https://img.shields.io/badge/MARSY-701E16?style=plastic&logo=adobephotoshop&logoColor=FCEC7D)

<div class="startup__row">
	<a href="https://larionov-anton.github.io/startup/" class="startup__img"><img src="img/startup.jpg"/></a>
	<div class="startup__description">
		<h3>About project</h3>
		<p><span>Одностраничный лендинг</span></p>
		<ul>
			<li>Префиксы под все современные браузеры</li>
			<li>Адаптив по брейк пойнтам под любые устройства </li>
			<li>Full screen блок главного экрана</li>
			<li>2 слайдера реализованный при помощи библиотеки slick slaider</li>
			<li>Блок с табуляцией</li>
			<li>Форма с валидацией</li>
			<li>Блог</li>
			</ul>
		</div>
	</div>





