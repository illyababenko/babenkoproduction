<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Видео съемка - Услуги</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <style>
        body { font-family: Arial, sans-serif; }
        .hero { background: url('video-bg.jpg') center/cover; color: white; padding: 100px 20px; text-align: center; }
        .services, .portfolio, .contact { padding: 50px 20px; }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Видео съемка</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#portfolio">Портфолио</a></li>
                    <li class="nav-item"><a class="nav-link" href="#services">Услуги</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Контакты</a></li>
                </ul>
            </div>
        </div>
    </nav>
    
    <header class="hero">
        <h1>Профессиональная видео съемка</h1>
        <p>Снимаем лучшие моменты вашей жизни!</p>
    </header>
    
    <section id="portfolio" class="portfolio">
        <div class="container">
            <h2 class="text-center">Портфолио</h2>
            <div class="row">
                <div class="col-md-4">
                    <img src="video1.jpg" class="img-fluid" alt="Видео работа 1">
                </div>
                <div class="col-md-4">
                    <img src="video2.jpg" class="img-fluid" alt="Видео работа 2">
                </div>
                <div class="col-md-4">
                    <img src="video3.jpg" class="img-fluid" alt="Видео работа 3">
                </div>
            </div>
        </div>
    </section>
    
    <section id="services" class="services bg-light">
        <div class="container">
            <h2 class="text-center">Наши услуги</h2>
            <ul>
                <li>Свадебная съемка</li>
                <li>Рекламные ролики</li>
                <li>Клипы и музыкальные видео</li>
            </ul>
        </div>
    </section>
    
    <section id="contact" class="contact">
        <div class="container">
            <h2 class="text-center">Свяжитесь с нами</h2>
            <form>
                <div class="mb-3">
                    <label class="form-label">Ваше имя</label>
                    <input type="text" class="form-control">
                </div>
                <div class="mb-3">
                    <label class="form-label">Email</label>
                    <input type="email" class="form-control">
                </div>
                <div class="mb-3">
                    <label class="form-label">Сообщение</label>
                    <textarea class="form-control"></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Отправить</button>
            </form>
        </div>
    </section>
    
    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2025 Видео съемка | Все права защищены</p>
    </footer>
    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
