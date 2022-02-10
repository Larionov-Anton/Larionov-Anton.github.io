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

	#main-content h2:before, #main-content h3:before, #main-content h4:before {
		padding-right: 0;
    	margin-left: 0;
    	content: none;
	}

/* Собственные стили */

	.about__row {
		display:flex;
	}

	.about__myphoto {
		flex: 0 0 250px;
	}
	
	.about__img {
    		width: 250px;
    		height: 290px;
	}
	
	.about__description {
		position: relative;
		padding: 0px 0px 0px 40px; 
	}
	.about__description:before {
		position: absolute;
		top: 0;
		left: 20px;
		content:'';
		width: 2px;
		height: 100%;
		background-color: #666;
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
			margin: 0px 0px 20px 0px; 
			text-align: center;
		}
	
		.about__description {
			padding: 0px 0px 0px 20px; 
		}
		
		.about__description:before {
			left: 10px;
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

	}
</style>

<!-- Блок краткой информации обо мне -->

<div class="about__row">
	<div class="about__myphoto">
		<img class="about__img" src="img/myphoto.jpg"/>
		<h3> Larionov Anton (31 year) </h3>
		<h4> Frontend Web Developer </h4>
		<h4> Rostov-on-don </h4>
	</div>
	<div class="about__description">
		<h3> About me </h3>
		<p> Я Frontend Web Developer. Верстаю кроссбраузерные и мобильно-адаптивные Landing Page и небольшие статические сайты. БЭМ, GULP, SCSS, CSS3\HTML5, Чистый JavaScript, jQuery. Изучаю фреймворк REACT, алгоритмы, объектно-ориентированное программирование. </p>
		<p> В поиске IT вакансий и команды для совместной веб разработки. Выполняю заказы на Freelans биржах. </p>
			<ul>
			<li> С 2012 года работаю в сфере ИТ и в смежных с ней направлениях </li>
			<li> Администрировал сервера Windows, Linux </li> 
			<li> Работал с различными терминалами Bash, Cmd, WSL, PowerShell </li>
			<li> Поддерживал программное обеспечение предприятий </li>
			<li> Занимался настройкой сетевого оборудования </li>
			<li> Знаю основы функционирования хостингов и сетевых протоколов HTTP(S), TCP\IP, FTP, SMTP, POP3, IPv4/6 </li>
			<li> Основы взаимодействие Frontend с Backend / Браузера с Сервером - запросы GET, POST, PUT, Delete </li>
			<li> Более 2х лет успешно развивал собственный бизнес. Выгодно продал фирму </li>
			<li> Человек творческий и целеустремленный. Ответственно и системно подхожу к решению любых задач </li> 
			<li> Понимаю потребности заказчика </li>
			</ul>
		<p> Увлекаюсь медитацией, йогой, плаванием, горным трекингом и игрой на музыкальных инструментах. </p>
	</div>
</div>

<!-- Блок контактов -->

<h3>Follow me:</h3>
[![linkedin](https://img.shields.io/badge/Linkedin-0189B4?style=flat&logo=linkedin&logoColor=000000)](https://www.linkedin.com/in/larionov-anton05/)
<a href="https://freelancehunt.com/freelancer/anton_larionov05.html?from=shield&r=xPWv7" target="_blank"><img src="https://freelancehunt.com/shields/display/id/1109187/type/reviews?style=flat&amp;lang=ru" alt="Freelancehunt — простой и честный фриланс"></a>

[![phone](https://img.shields.io/badge/PHONE_+7_(988)_570_72_57-0189B4?style=flat&logo=apple&logoColor=D9D9D9)](tel:+79885707257)
[![email](https://img.shields.io/badge/EMAIL_larionovanton05@gmail.com-0189B4?style=flat&logo=gmail&logoColor=F44336)](mailto:larionovanton05@gmail.com)
[![telegramm](https://img.shields.io/badge/TELEGRAMM-0189B4?style=flat&logo=telegram&logoColor=1D97C9)](https://t.me/AntonLarionov1)
[![instagram](https://img.shields.io/badge/INSTARAM-0189B4?style=flat&logo=instagram&logoColor=B83092)](https://www.instagram.com/seignior.anlarion/)
[![vk](https://img.shields.io/badge/VKONTACTE-0189B4?style=flat&logo=vk&logoColor=5181B8)](https://vk.com/larionov66)
[![twitter](https://img.shields.io/badge/TWITTER-0189B4?style=flat&logo=twitter&logoColor=209BF3)](https://twitter.com/larionov_anton1)

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

[![github](https://img.shields.io/badge/VIEW ON GITHUB-0189B4?style=flat&logo=github&logoColor=000000)](https://github.com/Larionov-Anton/startup)

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





