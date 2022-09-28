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

	#main-content h1:before, #main-content h2:before, #main-content h3:before, #main-content h4:before {
		padding-right: 0;
    	margin-left: 0;
    	content: none;
	}

/* Собственные стили */

	.about__row {
		display:flex;
		margin: 0 0 20px 0;
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
		font-size: 14px;
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
		margin: 80px 0 50px 0 !important;
	}

	.startup__row {
		position: relative;
		display:flex;
		flex-direction:column;
		margin: 0px 0px 20px 0px;
	}

	.startup__row::after {
		content: '';
		position: absolute;
		bottom: -5px;
		left: 0px;
		width: 100%;
		height: 2px;
		background-color: #000;
	}

	.startup__img {
		position:relative;
		flex: 0 0 250px;
		width: 100%;
		margin: 0 0 10px 0;
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

	footer {
		position: relative;
		text-align: center;
		padding: 0px 0px 20px !important;
		margin: 0px !important;
	}

	footer::after {
		content: '';
		position: absolute;
		bottom: 0px;
		left: 0px;
		width: 100%;
		height: 2px;
		background-color: #000;
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
	
		.startup__title {
			margin: 50px 0 50px 0;
		}
	}

</style>

<!-- Блок краткой информации обо мне -->

<div class="about__row">
	<div class="about__myphoto">
		<img class="about__img" src="img/myphoto.jpg"/>
		<h3> Larionov Anton (31 year) </h3>
		<h3> Frontend Web Developer </h3>
		<h3> Rostov-on-don </h3>
	</div>
	<div class="about__description">
		<h2> About me </h2>
		<p> Пишу проекты на стеке React \ Typescript \ Redux Toolkit \ Tailwind (CSS, SCSS) </p>
		<p> В поиске IT вакансий и команды для совместной веб разработки. </p>
		<p>Из языков и технологий знаю:</p>
			<ul>
			<li> <b>WEB</b> - клиент-сервер, протоколы - tcp\ip, dns, dhcp, http (get, post, put, delete, option) </li> 
			<li> <b>HTML</b> - структура документа, теги, атрибуты, формы, семантика </li> 
			<li> <b>CSS</b> - БЭМ, селекторы, свойства, классы, псевдоклассы, псевдоэлементы, каскадирование, наследование, приоритет, медиазапросы  </li> 
			<li> <b>SCSS</b> - переменные, вложенность, фрагментирование, миксины, расширение, мат.операторы</li> 
			<li> <b>JavaScript</b> - переменные, типы данных, операторы, условия, циклы, функции (рекурсия, замыкание, колбеки, промисы), классы, обьекты, прототипное наследование, this, работа с DOM, модули, обработка ошибок, паттерны (ООП, MVC) </li> 
			<li> <b>TypeScript</b> - типы данных, проверка типов, преобразование типов, generic, tuples, enum, alias, интерфейсы, модификаторы доступа </li> 
			<li> <b>React</b> - jsx разметка, рендеринг, компоненты, пропсы, состояние, контекст, обработчики событий, формы, списки и ключи </li> 
			<li> <b>Redux \ Toolkit</b> - store, actions, reducers, saga, slices, RTK Query, using with TypeScript </li> 
			<li> <b>GIT</b> - команды config, init, add, commit, reset, revert, rebase, clone, remote, push, pull, branch, checkout, merge, log </li> 
			<li> <b>Webpack</b> - точка входа\выхода, bundle, plugins, loaders, mode (dev,prod), dev server </li> 
			<li> <b>NodeJS</b> -  </li>
			<li> <b>Unit тестирование</b> -  </li> 
			</ul>
		<p> Увлекаюсь йогой, плаванием, горным трекингом и игрой на музыкальных инструментах. </p>
	</div>
</div>

<!-- Блок контактов -->

<h2>Follow me:</h2>
[![linkedin](https://img.shields.io/badge/Linkedin-0189B4?style=flat&logo=linkedin&logoColor=000000)](https://www.linkedin.com/in/larionov-anton05/)

[![phone](<https://img.shields.io/badge/PHONE_+7_(988)_570_72_57-0189B4?style=flat&logo=apple&logoColor=D9D9D9>)](tel:+79885707257)
[![email](https://img.shields.io/badge/EMAIL_larionovanton05@gmail.com-0189B4?style=flat&logo=gmail&logoColor=F44336)](mailto:larionovanton05@gmail.com)
[![telegram](https://img.shields.io/badge/TELEGRAM-0189B4?style=flat&logo=telegram&logoColor=1D97C9)](https://t.me/AntonLarionov1)
[![instagram](https://img.shields.io/badge/INSTARAM-0189B4?style=flat&logo=instagram&logoColor=B83092)](https://www.instagram.com/seignior.anlarion/)
[![vk](https://img.shields.io/badge/VKONTAKTE-0189B4?style=flat&logo=vk&logoColor=5181B8)](https://vk.com/larionov66)
[![twitter](https://img.shields.io/badge/TWITTER-0189B4?style=flat&logo=twitter&logoColor=209BF3)](https://twitter.com/larionov_anton1)

<!-- Блок стека технологий -->

<h2>Tech Stack:</h2>

![html](https://img.shields.io/badge/HTML5-7A8573?style=flat&logo=html5&logoColor=E34F26)
![pug](https://img.shields.io/badge/PUG-7A8573?style=flat&logo=pug&logoColor=A86454)
![css](https://img.shields.io/badge/CSS3-7A8573?style=flat&logo=css3&logoColor=117B11)
![scss](https://img.shields.io/badge/SCSS-7A8573?style=flat&logo=sass&logoColor=D05385)
![JS(OOP/MVC)](<https://img.shields.io/badge/JS_(OOP/MVC)-7A8573?style=flat&logo=javascript&logoColor=F7E01D>)
![TypeScript](https://img.shields.io/badge/TYPE_SCRIPT-7A8573?style=flat&logo=typescript&logoColor=3179C7)

<h2>Tools:</h2>

![React](https://img.shields.io/badge/REACT-7A8573?style=flat&logo=react&logoColor=5BDFF9)
![Redux\Toolkit](https://img.shields.io/badge/REDUX_TOOLKIT-7A8573?style=flat&logo=redux&logoColor=764ABC)
![TailwindCss](https://img.shields.io/badge/TAILWIND_CSS-7A8573?style=flat&logo=tailwindcss&logoColor=38BDF8)
![nodejs](https://img.shields.io/badge/NODE.JS-7A8573?style=flat&logo=node.js&logoColor=7BB065)
![webpack](https://img.shields.io/badge/WEBPACK-7A8573?style=flat&logo=webpack&logoColor=1B77C3)
![gulp](https://img.shields.io/badge/GULP-7A8573?style=flat&logo=gulp&logoColor=E84C51)
![git](https://img.shields.io/badge/GIT-7A8573?style=flat&logo=git&logoColor=DF4C37)
![github](https://img.shields.io/badge/GITHUB-7A8573?style=flat&logo=github&logoColor=000000)
![vscode](https://img.shields.io/badge/VSCODE-7A8573?style=flat&logo=Visualstudio&logoColor=0278CB)
![avocode](https://img.shields.io/badge/AVOCODE-7A8573?style=flat&logo=adobephotoshop&logoColor=00BD87)

<!-- Блок проекта - React, Redux Toolkit, Typescript  -->

<h1 class="startup__title">Portfolio</h1>
<h2><a target="_blank" href="https://react-advanced-taupe.vercel.app/">React, Redux Toolkit, Typescript</a></h2>

[![github](https://img.shields.io/badge/VIEW ON GITHUB-0189B4?style=flat&logo=github&logoColor=000000)](https://github.com/Larionov-Anton/react_advanced)

![html](https://img.shields.io/badge/HTML5-FACC15?style=plastic&logo=html5&logoColor=E34F26)
![css](https://img.shields.io/badge/CSS3-FACC15?style=plastic&logo=css3&logoColor=117B11)
![ts](https://img.shields.io/badge/TYPESCRIPT-FACC15?style=plastic&logo=typescript&logoColor=3179C7)
![react](https://img.shields.io/badge/REACT-FACC15?style=plastic&logo=react&logoColor=67D1FF)
![redux](https://img.shields.io/badge/REDUX_TOOLKIT-FACC15?style=plastic&logo=redux&logoColor=764ABC)
![tailwind](https://img.shields.io/badge/TAILWIND_CSS-FACC15?style=plastic&logo=tailwindcss&logoColor=764ABC)

<div class="startup__row">
	<a target="_blank" href="https://react-advanced-taupe.vercel.app/" class="startup__img"><img src="img/ReactAdvanced.png"/></a>
	<div class="startup__description">
		<h3>About project</h3>
		<p><span>Github Search. React \ Redux Toolkit application on Typescript</span></p>
		<ul>
			<li>Live search пользователя Github по его username. Асинхронные запросы при помощи RTK Query (createApi) для получения данных пользователя от Github api</li>
			<li>Обработка ошибок при запросах, индикатор процеса загрузки</li>
			<li>State manager - Redux Toolkit: configureStore, createSlice, createApi, useDispatch, useSelector</li>
			<li>Полученные данные рендерятся внутри функциональных компонентов React</li>
			<li>Реализованна функция добавления \ удаления ссылки на Github репозиторий в избранное с сохранением данных в Local Storage </li>
			</ul>
		</div>
	</div>

<!-- Блок проекта - React, Redux, JavaScript  -->

<h2><a target="_blank" href="https://redux-course.vercel.app/">React, Redux, Javascript</a></h2>

[![github](https://img.shields.io/badge/VIEW ON GITHUB-0189B4?style=flat&logo=github&logoColor=000000)](https://github.com/Larionov-Anton/redux_course)

![html](https://img.shields.io/badge/HTML5-266560?style=plastic&logo=html5&logoColor=E34F26)
![css](https://img.shields.io/badge/CSS3-266560?style=plastic&logo=css3&logoColor=117B11)
![js](https://img.shields.io/badge/JAVASCRIPT-266560?style=plastic&logo=javascript&logoColor=F7E01D)
![react](https://img.shields.io/badge/REACT-266560?style=plastic&logo=react&logoColor=67D1FF)
![redux](https://img.shields.io/badge/REDUX-266560?style=plastic&logo=redux&logoColor=764ABC)

<div class="startup__row">
	<a target="_blank" href="https://redux-course.vercel.app/" class="startup__img"><img src="img/ReactRedux.png"/></a>
	<div class="startup__description">
		<h3>About project</h3>
		<p><span>React \ Redux application on JavaScript</span></p>
		<ul>
			<li>Асинхронные запросы при помощи redux-thunk для получения списка комментариев на api 'jsonplaceholder'</li>
			<li>Обработка ошибок при запросах, индикатор процеса загрузки</li>
			<li>Данные распределены через Redux: createStore, Actions, Action Creators, Reducers, Immutable Data, hooks 'useSelector', 'useDispatch', 'useState</li>
			<li>Полученные комментарии рендерятся внутри функциональных компонентов React</li>
			<li>Реализованна функции добавления\редактирования\удаления комментариев. Добавления лайков и дизлайков </li>
			</ul>
		</div>
	</div>

<!-- Блок проекта - React application -->

<h2><a target="_blank" href="https://react-course-bay.vercel.app/">React application on TypeScript</a></h2>

[![github](https://img.shields.io/badge/VIEW ON GITHUB-0189B4?style=flat&logo=github&logoColor=000000)](https://github.com/Larionov-Anton/react_course)

![html](https://img.shields.io/badge/HTML5-313E4F?style=plastic&logo=html5&logoColor=E34F26)
![css](https://img.shields.io/badge/CSS3-313E4F?style=plastic&logo=css3&logoColor=117B11)
![ts](https://img.shields.io/badge/TYPESCRIPT-313E4F?style=plastic&logo=typescript&logoColor=3179C7)
![react](https://img.shields.io/badge/REACT-313E4F?style=plastic&logo=react&logoColor=67D1FF)

<div class="startup__row">
	<a target="_blank" href="https://react-course-bay.vercel.app/" class="startup__img"><img src="img/ReactAppTypescript.png"/></a>
	<div class="startup__description">
		<h3>About project</h3>
		<p><span>React application on TypeScript</span></p>
		<ul>
			<li>Асинхронные запросы при помощи Axios для получения списка товаров на 'fakestoreapi'</li>
			<li>Асинхронные запросы реализованны при помощи кастомного хука</li>
			<li>Полученные товары рендерятся внутри функциональных компонентов React: components, state, hooks, props, jsx, event handlers </li>
			<li>Данные приложения распределятся React Context и строго типизированны TypeScript</li>
			<li>Роутинг страниц - 'react-router-dom'</li>
			<li>Реализованна кнопка "Показать Детали" через хук useState</li>
			<li>Реализованна возможность добавить собственный товар передав заголовок через асинхронный запрос на 'fakestoreapi'</li>
			</ul>
		</div>
	</div>

<!-- Блок проекта - Calculator OOP\MVC -->

<>

<h2><a target="_blank" href="https://larionov-anton.github.io/calculator_oop/dist/">Calcuator (OOP/MVC)</a></h2>

[![github](https://img.shields.io/badge/VIEW ON GITHUB-0189B4?style=flat&logo=github&logoColor=000000)](https://github.com/Larionov-Anton/calculator_oop)

![html](https://img.shields.io/badge/HTML5-FF9501?style=plastic&logo=html5&logoColor=E34F26)
![css](https://img.shields.io/badge/CSS3-FF9501?style=plastic&logo=css3&logoColor=117B11)
![js](https://img.shields.io/badge/JAVASCRIPT-FF9501?style=plastic&logo=javascript&logoColor=F7E01D)
![OOP/MVC](https://img.shields.io/badge/OOP_MVC-FF9501?style=plastic&logo=javascript&logoColor=F7E01D)
![Webpack](https://img.shields.io/badge/WEBPACK-FF9501?style=plastic&logo=webpack&logoColor=F7E01D)

<div class="startup__row">
	<a target="_blank" href="https://larionov-anton.github.io/calculator_oop/dist/" class="startup__img"><img src="img/Calculator.png"/></a>
	<div class="startup__description">
		<h3>About project</h3>
		<p><span>Calculator on JavaScript (OOP/MVC)</span></p>
		<ul>
			<li>Классический калькулятор c iphone, выполняющий базовые математические операции</li>
			<li>Проект собирается самописной сборкой webpack</li>
			<li>Структура проекта составлена в соответствии с паттерном MVC в объектно-ориентированном стиле</li>
			<li>Вся логика написана на ванильном JavaScript</li>
			<li>Данные приложения сохраняются в local storage</li>
			</ul>
		</div>
	</div>

<!-- Блок проекта - Todo JS -->

<h2><a target="_blank" href="https://larionov-anton.github.io/todo_js/public/">Todo JS (OOP\MVC)</a></h2>

[![github](https://img.shields.io/badge/VIEW ON GITHUB-0189B4?style=flat&logo=github&logoColor=000000)](https://github.com/Larionov-Anton/todo_js)

![html](https://img.shields.io/badge/HTML5-BE61FB?style=plastic&logo=html5&logoColor=E34F26)
![css](https://img.shields.io/badge/CSS3-BE61FB?style=plastic&logo=css3&logoColor=117B11)
![js](https://img.shields.io/badge/JAVASCRIPT-BE61FB?style=plastic&logo=javascript&logoColor=F7E01D)
![OOP/MVC](https://img.shields.io/badge/OOP_MVC-BE61FB?style=plastic&logo=javascript&logoColor=F7E01D)

<div class="startup__row">
	<a target="_blank" href="https://larionov-anton.github.io/todo_js/public/" class="startup__img"><img src="img/Todo_JS.png"/></a>
	<div class="startup__description">
		<h3>About project</h3>
		<p><span>Todo list on JavaScript (OOP/MVC)</span></p>
		<ul>
			<li>Структура проекта составлена в соответствии с паттерном MVC в объектно-ориентированном стиле</li>
			<li>Вся логика написана на ванильном JavaScript</li>
			<li>События данных реализованны через Event Emmiter</li>
			<li>Приложение умеет: добавлять, редактировать, отмечать как выбранные и удалять задачи</li>
			<li>Данные приложения сохраняются в local storage</li>
			</ul>
		</div>
	</div>

<!-- Блок проекта - Landig page startup -->

<h2><a target="_blank" href="https://larionov-anton.github.io/startup/">Startup</a></h2>

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
	<a target="_blank" href="https://larionov-anton.github.io/startup/" class="startup__img"><img src="img/startup.jpg"/></a>
	<div class="startup__description">
		<h3>About project</h3>
		<p><span>Landing Page</span></p>
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

<!-- Блок проекта - Тестовое задание по верстке Rocket_Business -->

<h2><a target="_blank" href="https://larionov-anton.github.io/test_Rocket_Business/">Multidisciplinary clinic</a></h2>

[![github](https://img.shields.io/badge/VIEW ON GITHUB-0189B4?style=flat&logo=github&logoColor=000000)](https://github.com/Larionov-Anton/test_Rocket_Business)

![html](https://img.shields.io/badge/HTML5-1FA181?style=plastic&logo=html5&logoColor=E34F26)
![css](https://img.shields.io/badge/CSS3-1FA181?style=plastic&logo=css3&logoColor=117B11)
![scss](https://img.shields.io/badge/SCSS-1FA181?style=plastic&logo=sass&logoColor=D05385)
![js](https://img.shields.io/badge/JAVASCRIPT-1FA181?style=plastic&logo=javascript&logoColor=F7E01D)
![jq](https://img.shields.io/badge/JQUERY-1FA181?style=plastic&logo=jquery&logoColor=193657)
![git](https://img.shields.io/badge/GIT-1FA181?style=plastic&logo=git&logoColor=DF4C37)
![vscode](https://img.shields.io/badge/VSCODE-1FA181?style=plastic&logo=Visualstudio&logoColor=0278CB)
![prepros](https://img.shields.io/badge/PREPROS-1FA181?style=plastic&logo=webpack&logoColor=20C4E1)
![marsy](https://img.shields.io/badge/MARSY-1FA181?style=plastic&logo=adobephotoshop&logoColor=FCEC7D)

<div class="startup__row">
	<a target="_blank" href="https://larionov-anton.github.io/test_Rocket_Business/" class="startup__img"><img src="img/Rocket.png"/></a>
	<div class="startup__description">
		<h3>About project</h3>
		<p><span>Тестовое задание по верстке</span></p>
		<ul>
			<li>Popup c формой на JavaScript</li>
			<li>Форма с валидацией маской ввода на JavaScript</li>
			<li>Отправка формы на почту (PHPmailer)</li>
			<li>Слайдер с счетчиком слайдов на JQ (SlickSlider)</li>
			<li>Адаптивное выпадающее мобильное меню на JavaScript</li>
			<li>Flexbox</li>
			<li>Использование относительных единиц EM</li>
			<li>Префиксы под все современные браузеры</li>
			<li>Адаптив по брейк пойнтам под любые устройства </li>
			</ul>
		</div>
	</div>

<!-- Блок проекта - Тестовое задание по верстке Elon Musc -->

<h2><a target="_blank" href="https://larionov-anton.github.io/Elon_Musc/">Elon Musc</a></h2>

[![github](https://img.shields.io/badge/VIEW ON GITHUB-0189B4?style=flat&logo=github&logoColor=000000)](https://github.com/Larionov-Anton/Elon_Musc)

![html](https://img.shields.io/badge/HTML5-0c161e?style=plastic&logo=html5&logoColor=E34F26)
![css](https://img.shields.io/badge/CSS3-0c161e?style=plastic&logo=css3&logoColor=117B11)
![scss](https://img.shields.io/badge/SCSS-0c161e?style=plastic&logo=sass&logoColor=D05385)
![js](https://img.shields.io/badge/JAVASCRIPT-0c161e?style=plastic&logo=javascript&logoColor=F7E01D)
![jq](https://img.shields.io/badge/JQUERY-0c161e?style=plastic&logo=jquery&logoColor=193657)
![git](https://img.shields.io/badge/GIT-0c161e?style=plastic&logo=git&logoColor=DF4C37)
![vscode](https://img.shields.io/badge/VSCODE-0c161e?style=plastic&logo=Visualstudio&logoColor=0278CB)
![prepros](https://img.shields.io/badge/PREPROS-0c161e?style=plastic&logo=webpack&logoColor=20C4E1)
![marsy](https://img.shields.io/badge/MARSY-0c161e?style=plastic&logo=adobephotoshop&logoColor=FCEC7D)

<div class="startup__row">
	<a target="_blank" href="https://larionov-anton.github.io/Elon_Musc/" class="startup__img"><img src="img/Elon_Musc.jpg"/></a>
	<div class="startup__description">
		<h3>About project</h3>
		<p><span>Тестовое задание по верстке</span></p>
		<ul>
			<li>Flexbox</li>
			<li>Градиенты</li>
			<li>Различное позиционирование элементов</li>
			<li>Адаптивное выпадающее меню</li>
			<li>Использование относительных единиц EM</li>
			<li>Префиксы под все современные браузеры</li>
			<li>Full screen блок главного экрана</li>
			<li>Адаптив по брейк пойнтам под любые устройства </li>
			</ul>
		</div>
	</div>

<!-- Подвал сайта -->

<footer>
	<h2>Larionov Anton © 2022</h2>
	<h3>Frontend Web Developer</h3>
	<h3>Rostov-on-don</h3>
</footer>
