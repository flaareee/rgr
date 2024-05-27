<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Найвідоміші музеї світу</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="styles.css">
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://code.jquery.com/ui/1.12.1/jquery-ui.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px;
            background-color: #f8f9fa;
        }
        .header-container img {
            height: 50px;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        nav ul li {
            margin-right: 20px;
        }
        nav ul li a {
            text-decoration: none;
            color: #000;
        }
        .gallery-container img {
            width: 100%;
            max-width: 300px;
            margin: 10px;
        }
        .photos img {
            width: 100px;
            margin: 5px;
        }
        .footer-container {
            padding: 10px;
            background-color: #f8f9fa;
            text-align: center;
        }
        .carousel-inner img {
            width: 100%;
            height: 400px;
        }
        .news-section article {
            margin-bottom: 20px;
        }
    </style>
</head>
<body>

<header>
    <div class="header-container">
        <img src="logo.png" alt="Логотип сайту Найвідоміші музеї світу">
        <nav>
            <ul>
                <li><a href="#about">Про сайт</a></li>
                <li><a href="#gallery">Галерея картинок</a></li>
                <li><a href="#news">Новини</a></li>
                <li><a href="#contacts">Контакти</a></li>
            </ul>
        </nav>
    </div>
</header>

<main>
    <!-- Слайдер -->
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img class="d-block w-100" src="louvre1.jpg" alt="Лувр">
            </div>
            <div class="carousel-item">
                <img class="d-block w-100" src="vatican1.jpg" alt="Музей Ватикану">
            </div>
            <div class="carousel-item">
                <img class="d-block w-100" src="metropolitan1.jpg" alt="Музей Метрополітен">
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>

    <!-- Про сайт -->
    <section id="about">
        <h2>Про сайт</h2>
        <p>Ласкаво просимо на інформаційний портал про найвідоміші музеї світу! Ми є вашим провідником у світ культурної спадщини, де ви знайдете цікаві факти, захоплюючі виставки та останні новини з найпрестижніших музеїв усього світу. Від Лувру в Парижі до Музею Метрополітен у Нью-Йорку, ми розкажемо вам про найдивовижніші колекції мистецтва, архітектурні шедеври та унікальні виставки. Наш сайт пропонує глибокий занурення у світ культури та мистецтва, де кожен зможе знайти щось цікаве для себе. Долучайтеся до нашої подорожі і відкрийте для себе неймовірний світ музеїв!</p>
    </section>

    <!-- Галерея картинок -->
    <section id="gallery">
        <h2>Галерея картинок</h2>
        <div class="gallery-container d-flex flex-wrap">
            <img src="louvre.png" alt="Лувр">
            <img src="vatican1.jpg" alt="Музей Ватикану">
            <img src="metropolitan1.jpg" alt="Музей Метрополітен">
            <!-- додайте інші картинки за бажанням -->
        </div>
    </section>

    <!-- Новини -->
    <section id="news" class="news-section">
        <h2>Новини</h2>
        <!-- Новина 1 -->
        <article>
            <h3>Відкриття нової виставки у Луврі</h3>
            <p>Музей Лувр у Парижі анонсував відкриття нової виставки "Скарби світового мистецтва", яка презентує вражаючу колекцію картин, скульптур і реліквій з усього світу. Виставка буде відкрита для відвідувачів з 1 червня.</p>
            <!-- фото -->
            <div class="photos">
                <img src="louvre2.jpg" alt="Лувр">
                <img src="louvre3.jpg" alt="Лувр">
                <!-- додайте інші фото за бажанням -->
            </div>
        </article>
        <!-- Новина 2 -->
        <article>
            <h3>Музей Метрополітен: скарби світового мистецтва</h3>
            <p>У музеї Метрополітен можна знайти практично все: від артефактів палеоліту до предметів поп- арту. Є тут і колекції мистецтва Африки і Океанії, Близького Сходу і Єгипту, які сміливо можна назвати раритетом...</p>
            <!-- фото -->
            <div class="photos">
                <img src="metropolitan2.jpg" alt="Музей Метрополітен">
                <img src="metropolitan3.jpg" alt="Музей Метрополітен">
                <!-- додайте інші фото за бажанням -->
            </div>
        </article>
        <!-- Новина 3 -->
        <article>
            <h3>Музей Ватикану: найбільший музей світу</h3>
            <p>Музей Ватикану — найбільший музей світу: 1400 залів, 50000 об’єктів, і щоб обійти всі представлені експонати треба пройти 7 км. Зрозуміло, всі відвідувачі першою справою прагнуть потрапити в Сикстинську капелу...</p>
            <!-- фото -->
            <div class="photos">
                <img src="vatican2.jpg" alt="Музей Ватикану">
                <img src="vatican3.jpg" alt="Музей Ватикану">
                <!-- додайте інші фото за бажанням -->
            </div>
        </article>
        <!-- інші новини -->
        <article>
            <h3>British Museum: культурне скарбниця Великої Британії</h3>
            <p>British Museum — Британський музей в Лондоні — є одним з найбільших та найстаріших музеїв у світі. Заснований в 1753 році, він має в своєму зібранні понад 8 мільйонів артефактів, які охоплюють всю історію людства з давніх часів до сучасності.</p>
            <!-- фото -->
            <div class="photos">
                <img src="britishmuseum1.jpg" alt="British Museum">
                <img src="britishmuseum2.jpg" alt="British Museum">
                <!-- додайте інші фото за бажанням -->
            </div>
        </article>
        <article>
            <h3>Національний музей Китаю: культурна спадщина Піднебесної</h3>
            <p>Національний музей Китаю в Пекіні є найбільшим музеєм в країні та одним з найбільших у світі. Він містить понад мільйон об’єктів, що охоплюють історію Китаю від давнини до сучасності.</p>
            <!-- фото -->
            <div class="photos">
                <img src="nationalmuseumchina1.jpg" alt="Національний музей Китаю">
                <img src="nationalmuseumchina2.jpg" alt="Національний музей Китаю">
                <!-- додайте інші фото за бажанням -->
            </div>
        </article>
        <article>
            <h3>Уффіці: ренесансна скарбниця Флоренції</h3>
            <p>Уффіці в Флоренції є однією з найвідоміших художніх галерей у світі. Заснована в 1581 році, вона містить багатющу колекцію італійського ренесансного мистецтва, включаючи твори Леонардо да Вінчі, Мікеланджело, Рафаеля та Боттічеллі.</p>
            <!-- фото -->
            <div class="photos">
                <img src="uffizi1.jpg" alt="Уффіці">
                <img src="uffizi2.jpg" alt="Уффіці">
                <!-- додайте інші фото за бажанням -->
            </div>
        </article>
    </section>

    <!-- Контакти -->
    <section id="contacts">
        <h2>Контакти</h2>
        <p>Для отримання додаткової інформації, будь ласка, зв'яжіться з нами:</p>
        <p>Email: info@worldmuseums.com</p>
        <p>Телефон: +123 456 7890</p>
        <!-- Карта Google -->
        <div id="map" style="height: 400px; width: 100%;"></div>
        <script>
            function initMap() {
                var location = { lat: 48.858844, lng: 2.294351 }; // Приклад координат
                var map = new google.maps.Map(document.getElementById('map'), {
                    zoom: 10,
                    center: location
                });
                var marker = new google.maps.Marker({
                    position: location,
                    map: map
                });
            }
        </script>
        <script async defer
            src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap">
        </script>
    </section>
</main>

<footer>
    <div class="footer-container">
        <p>&copy; 2024 Найвідоміші музеї світу. Всі права захищені.</p>
    </div>
</footer>

</body>
</html>
