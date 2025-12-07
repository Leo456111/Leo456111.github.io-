# Leo456111.github.io-
Рио
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Мой Сайт</title>
                <link rel="stylesheet" href="styles.css"> <!-- Подключите свой файл стилей -->
                </head>
                <body>
                    <header>
                            <h1>Добро пожаловать на мой сайт!</h1>
                                </header>

                                    <main>
                                            <section>
                                                        <h2>Информация</h2>
                                                                    <p>Здесь будет описание вашего сайта.</p>
                                                                            </section>

                                                                                    <form id="contactForm">
                                                                                                <h2>Оставьте свой email</h2>
                                                                                                            <input type="email" id="email" placeholder="Введите ваш email" required>
                                                                                                                        <button type="submit">Отправить</button>
                                                                                                                                </form>
                                                                                                                                    </main>

                                                                                                                                        <footer>
                                                                                                                                                <p>&copy; 2023 Мой Сайт. Все права защищены.</p>
                                                                                                                                                    </footer>

                                                                                                                                                        <script>
                                                                                                                                                                document.getElementById('contactForm').addEventListener('submit', function(event) {
                                                                                                                                                                            event.preventDefault();

                                                                                                                                                                                        const email = document.getElementById('email').value;

                                                                                                                                                                                                    // Отправка результатов на почту (требуется серверная часть для обработки)
                                                                                                                                                                                                                console.log('Email отправлен на:', email);
                                                                                                                                                                                                                            alert('Спасибо, ваш email сохранен!');
                                                                                                                                                                                                                                    });
                                                                                                                                                                                                                                        </script>
                                                                                                                                                                                                                                        </body>
                                                                                                                                                                                                                                        </html>