
<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Ли Альбина Тевоновна</p>
<br><br><br>
<p align = "center"><br><strong>Лабораторная работа №7. «CSS»</strong><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>

<p><b>Веб-разработка</b> — процесс создания веб-сайта или веб-приложения. Основными этапами процесса являются: </p>

<ul>
<li>Проектирование сайта или веб-приложения (сбор и анализ требований, разработка технического задания, проектирование интерфейсов);</li>
<li>Создание дизайн-концепции сайта;</li>
<li>Создание страниц;</li>
<li>Программирование;</li>
<li>Оптимизация и размещение материалов сайта;</li>
<li>Тестирование и внесение корректировок;</li>
<li>Публикация проекта на хостинге;</li>
<li>Обслуживание работающего сайта.</li>
</ul>

<br>

<h1 align = "center">Цели и задачи</h1>


<p>Цель: ознакомиться с принципами работы со стилями, классами.</p>

<p>Задачи:</p>

<ul>
<li>Создать копию веб страницы</li>
<li>Научиться форматированию элементов при помощи стилей</li>
<li>Поэкспериментировать с классами, формами, кнопками, меню и т.д.</li>
</ul>

<p></p>

<h1 align = "center">Решение</h1>

<p>Для выполнения этой лабораторной работы, я пользовалась лекционным материалом и интернет-ресурсами для поиска решений задач оформления и для поиска медиаресурсов:</p>

<ul>
<li><a href="https://youtube.com/">YouTube</a></li>
<li><a href="https://stackoverflow.com/">Stack Overflow</a></li>
</ul>

<p>Примеры CSS:</p>
  <code>.container {
    width: 100%;
    display: flex;
    justify-content: center;
}
.container:has(.header) {
    background-image: url("Images/header-wrapper-bg.png");
    height: 187px;
}
.header {
    width: 960px;
}
.menu {
    width: 100%;
    padding: 41px 0;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.menu_logo {
    background-image: url("Images/logo-bg.png");
    background-size: 100% 100%;
    border-radius: 10px;
    padding: 25px;
    width: 200px;
    text-align: center;
    margin-right: 150px;
}
.menu_link {
    color: white;
    text-decoration: none;
    background-size: 100% 100%;
    border-radius: 10px;
    font-size: 1.1em;
    display: block;
}
.menu_links {
    display: flex;
    flex-direction: row;
    gap: 25px;
}
.menu_link_selected {
    background: url("Images/menu-first-bgleft.png") no-repeat left top;
}
.menu_link-text {
    height: 40px;
    padding: 8px 21px 8px 21px;
    display: block;
}
.menu_link_selected .menu_link-text {
    background: url("Images/menu-first-bgright.png") no-repeat right top;
}</code>
</br></br>
<img src="/Images/page.PNG"></img>
</br>
<h1 align = "center">Вывод</h1>
<p>В результате проделанной лабораторной работы, я закрепила знания по html, потренировалась в написании стилей и более сложных структур разметки.</p>
