<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Менің Портфолиом</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header бөлімі -->
    <header>
        <h1>Жылқыбаев Ғалымжан</h1>
        <p>Байланыс: <a href="mailto:galymzhan@email.com">galymzhan@email.com</a> |
           Тел: +7 705 542 71 91</p>
    </header>

    <!-- Өзіңіз жайлы -->
    <section id="about">
        <h2>Өзім жайлы</h2>
        <p>Мен веб-бағдарламалау саласында тәжірибемді дамытып жүрген студентпін. 
        HTML, CSS және JavaScript тілдерін үйреніп жатырмын. Болашақта кәсіби 
        веб-дизайнер және full-stack әзірлеуші болғым келеді.</p>
    </section>

    <!-- Жобалар -->
    <section id="projects">
        <h2>Жобаларым</h2>
        <ul>
            <li><strong>Студенттер тізімі:</strong> HTML+CSS қолдана отырып GPA есептеу.</li>
            <li><strong>Кредит калькуляторы:</strong> Пайыздық мөлшерлемемен автоматты есептеу.</li>
            <li><strong>Жеке блог макеті:</strong> Веб-дизайнға арналған статикалық сайт үлгісі.</li>
        </ul>
    </section>

    <!-- Байланыс формасы (макет түрінде) -->
    <section id="contact">
        <h2>Байланыс</h2>
        <form>
            <label for="name">Атыңыз:</label>
            <input type="text" id="name" name="name" placeholder="Атыңызды жазыңыз" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Email енгізіңіз" required>

            <label for="message">Хабарлама:</label>
            <textarea id="message" name="message" placeholder="Хабарламаңызды жазыңыз..." required></textarea>

            <button type="submit">Жіберу</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2025 Жылқыбаев Ғалымжан. Барлық құқықтар қорғалған.</p>
    </footer>

</body>
</html>
