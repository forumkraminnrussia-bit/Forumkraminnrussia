<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KRAPINN RUSSIA | Технические работы</title>
    <!-- Подключение шрифтов и иконок -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700;800;900&family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --primary: #ff1e27;
            --primary-glow: rgba(255, 30, 39, 0.4);
            --primary-dark: #8b0000;
            --bg-color: #07080a;
            --card-bg: rgba(18, 10, 12, 0.75);
            --text-main: #ffffff;
            --text-sub: #a3a8b5;
            --border-glow: rgba(255, 30, 39, 0.25);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Montserrat', sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
            overflow-x: hidden;
            position: relative;
        }

        /* Анимированный Canvas фон */
        #bgCanvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 0;
            pointer-events: none;
        }

        /* Внешнее красное свечение заднего плана */
        .glow-orb-1, .glow-orb-2 {
            position: fixed;
            width: 450px;
            height: 450px;
            border-radius: 50%;
            background: radial-gradient(circle, rgba(255, 30, 39, 0.2) 0%, rgba(0,0,0,0) 70%);
            z-index: 0;
            animation: orbFloat 8s infinite ease-in-out alternate;
            pointer-events: none;
        }

        .glow-orb-1 { top: -100px; left: -100px; }
        .glow-orb-2 { bottom: -100px; right: -100px; animation-delay: -4s; }

        @keyframes orbFloat {
            0% { transform: scale(1) translate(0, 0); opacity: 0.6; }
            100% { transform: scale(1.3) translate(40px, 30px); opacity: 0.9; }
        }

        .container {
            position: relative;
            z-index: 1;
            max-width: 680px;
            width: 100%;
            background: var(--card-bg);
            border: 1px solid var(--border-glow);
            backdrop-filter: blur(16px);
            border-radius: 24px;
            padding: 45px 35px;
            text-align: center;
            box-shadow: 0 0 50px rgba(255, 30, 39, 0.15), inset 0 0 20px rgba(255, 30, 39, 0.05);
            animation: cardAppear 1s cubic-bezier(0.16, 1, 0.3, 1) forwards;
        }

        @keyframes cardAppear {
            0% { opacity: 0; transform: translateY(30px) scale(0.95); }
            100% { opacity: 1; transform: translateY(0) scale(1); }
        }

        /* Иконка с волновым эффектом */
        .icon-wrapper {
            position: relative;
            width: 90px;
            height: 90px;
            margin: 0 auto 25px;
        }

        .icon-box {
            width: 100%;
            height: 100%;
            background: linear-gradient(135deg, #ff1e27, #8b0000);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 0 30px var(--primary-glow);
            position: relative;
            z-index: 2;
        }

        .icon-box i {
            font-size: 40px;
            color: #fff;
            animation: wrenchRotate 3s ease-in-out infinite alternate;
        }

        @keyframes wrenchRotate {
            0% { transform: rotate(-15deg); }
            100% { transform: rotate(25deg); }
        }

        .icon-pulse {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border-radius: 50%;
            border: 2px solid var(--primary);
            animation: pulseWave 2s infinite ease-out;
            z-index: 1;
        }

        @keyframes pulseWave {
            0% { transform: scale(1); opacity: 1; }
            100% { transform: scale(1.6); opacity: 0; }
        }

        /* Заголовки */
        .brand-tag {
            display: inline-block;
            font-size: 13px;
            font-weight: 800;
            letter-spacing: 2px;
            color: var(--primary);
            text-transform: uppercase;
            margin-bottom: 8px;
            text-shadow: 0 0 10px var(--primary-glow);
        }

        h1 {
            font-size: 30px;
            font-weight: 900;
            margin-bottom: 12px;
            text-transform: uppercase;
            letter-spacing: 1px;
            background: linear-gradient(180deg, #ffffff 0%, #d1d5db 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .status-badge {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            background: rgba(255, 30, 39, 0.12);
            color: #ff5258;
            border: 1px solid rgba(255, 30, 39, 0.3);
            padding: 8px 18px;
            border-radius: 30px;
            font-size: 13px;
            font-weight: 700;
            margin-bottom: 25px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .status-dot {
            width: 8px;
            height: 8px;
            background-color: var(--primary);
            border-radius: 50%;
            box-shadow: 0 0 8px var(--primary);
            animation: blink 1.2s infinite alternate;
        }

        @keyframes blink {
            0% { opacity: 0.3; }
            100% { opacity: 1; }
        }

        .description {
            font-size: 15px;
            color: var(--text-sub);
            line-height: 1.7;
            margin-bottom: 30px;
            font-family: 'Roboto', sans-serif;
        }

        .description strong {
            color: #fff;
            font-weight: 600;
        }

        /* Блок таймера */
        .timer-title {
            font-size: 13px;
            text-transform: uppercase;
            color: var(--text-sub);
            letter-spacing: 1.5px;
            font-weight: 700;
            margin-bottom: 15px;
        }

        .timer-container {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-bottom: 35px;
        }

        .timer-box {
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(255, 255, 255, 0.08);
            border-radius: 14px;
            padding: 12px 18px;
            min-width: 85px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.3);
            transition: transform 0.3s ease, border-color 0.3s ease;
        }

        .timer-box:hover {
            border-color: var(--primary);
            transform: translateY(-3px);
        }

        .timer-value {
            font-size: 28px;
            font-weight: 900;
            color: var(--primary);
            text-shadow: 0 0 12px var(--primary-glow);
            font-family: 'Montserrat', sans-serif;
        }

        .timer-label {
            font-size: 11px;
            color: var(--text-sub);
            text-transform: uppercase;
            margin-top: 4px;
            font-weight: 600;
        }

        /* Кнопки */
        .buttons-grid {
            display: flex;
            flex-direction: column;
            gap: 14px;
        }

        .btn {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            padding: 16px 24px;
            border-radius: 12px;
            font-size: 15px;
            font-weight: 800;
            text-decoration: none;
            cursor: pointer;
            transition: all 0.3s cubic-bezier(0.16, 1, 0.3, 1);
            border: none;
            width: 100%;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            position: relative;
            overflow: hidden;
        }

        .btn-telegram {
            background: linear-gradient(135deg, #24A1DE, #1b83b6);
            color: #fff;
            box-shadow: 0 6px 20px rgba(36, 161, 222, 0.25);
        }
        .btn-telegram:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(36, 161, 222, 0.4);
        }

        .btn-admin {
            background: rgba(255, 255, 255, 0.05);
            color: #fff;
            border: 1px solid rgba(255, 255, 255, 0.12);
        }
        .btn-admin:hover {
            background: rgba(255, 255, 255, 0.1);
            border-color: rgba(255, 255, 255, 0.25);
            transform: translateY(-3px);
        }

        .btn-rules {
            background: linear-gradient(135deg, #ff1e27, #8b0000);
            color: #fff;
            box-shadow: 0 6px 20px var(--primary-glow);
        }
        .btn-rules:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 30px rgba(255, 30, 39, 0.6);
        }

        /* Модальное окно */
        .modal-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.85);
            backdrop-filter: blur(8px);
            display: none;
            align-items: center;
            justify-content: center;
            z-index: 100;
            padding: 20px;
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .modal-overlay.active {
            display: flex;
            opacity: 1;
        }

        .modal-content {
            background: #111319;
            border: 1px solid var(--border-glow);
            border-radius: 20px;
            max-width: 620px;
            width: 100%;
            max-height: 80vh;
            display: flex;
            flex-direction: column;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.9), 0 0 30px rgba(255, 30, 39, 0.2);
            transform: scale(0.9);
            transition: transform 0.3s ease;
        }

        .modal-overlay.active .modal-content {
            transform: scale(1);
        }

        .modal-header {
            padding: 22px 25px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.08);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .modal-header h2 {
            font-size: 20px;
            font-weight: 800;
            display: flex;
            align-items: center;
            gap: 10px;
            color: var(--primary);
        }

        .close-btn {
            background: none;
            border: none;
            color: var(--text-sub);
            font-size: 22px;
            cursor: pointer;
            transition: color 0.2s;
        }
        .close-btn:hover {
            color: #fff;
        }

        .modal-body {
            padding: 25px;
            overflow-y: auto;
            text-align: left;
            color: #d1d5db;
            font-size: 14px;
            line-height: 1.7;
            font-family: 'Roboto', sans-serif;
        }

        .modal-body h3 {
            color: #fff;
            margin: 18px 0 10px;
            font-size: 16px;
            font-weight: 700;
            border-left: 3px solid var(--primary);
            padding-left: 10px;
        }

        .modal-body h3:first-child { margin-top: 0; }

        .modal-body ul {
            margin-left: 18px;
            margin-bottom: 12px;
        }

        .modal-body li { margin-bottom: 8px; }

        /* Кастомный скроллбар */
        .modal-body::-webkit-scrollbar { width: 6px; }
        .modal-body::-webkit-scrollbar-track { background: rgba(0,0,0,0.2); }
        .modal-body::-webkit-scrollbar-thumb { background: var(--primary); border-radius: 4px; }
    </style>
</head>
<body>

    <canvas id="bgCanvas"></canvas>
    <div class="glow-orb-1"></div>
    <div class="glow-orb-2"></div>

    <div class="container">
        <div class="icon-wrapper">
            <div class="icon-pulse"></div>
            <div class="icon-box">
                <i class="fa-solid fa-wrench"></i>
            </div>
        </div>
        
        <div class="brand-tag">KRAPINN RUSSIA B.Y FARICH(разраб)</div>
        <h1>Технические работы</h1>
        
        <div class="status-badge">
            <span class="status-dot"></span>
            Обновление системы
        </div>
        
        <p class="description">
            Привет! В данный момент сайт временно закрыт на техническое обслуживание.<br>
            Мы заливаем крупные обновления и добавляем новые разделы.<br><br>
            Подача заявлений на пост Администратора и Лидера временно недоступна.<br>
            Обо всех изменениях и открытии форума мы сразу сообщим в нашем канале!
        </p>

        <!-- Таймер -->
        <div class="timer-title">Примерное время открытия (по МСК)</div>
        <div class="timer-container">
            <div class="timer-box">
                <div class="timer-value" id="hours">00</div>
                <div class="timer-label">Часов</div>
            </div>
            <div class="timer-box">
                <div class="timer-value" id="minutes">00</div>
                <div class="timer-label">Минут</div>
            </div>
            <div class="timer-box">
                <div class="timer-value" id="seconds">00</div>
                <div class="timer-label">Секунд</div>
            </div>
        </div>

        <div class="buttons-grid">
            <a href="https://t.me/lame_mobile" target="_blank" class="btn btn-telegram">
                <i class="fa-brands fa-telegram"></i> Наш Telegram-канал
            </a>

            <a href="https://t.me/urtung" target="_blank" class="btn btn-admin">
                <i class="fa-solid fa-user-shield"></i> Связь со спец. администратором
            </a>

            <button class="btn btn-rules" onclick="openRules()">
                <i class="fa-solid fa-book-bookmark"></i> Правила проекта
            </button>
        </div>
    </div>

    <!-- Модальное окно правил -->
    <div class="modal-overlay" id="rulesModal">
        <div class="modal-content">
            <div class="modal-header">
                <h2><i class="fa-solid fa-shield-halved"></i> Правила KRAPINN RUSSIA</h2>
                <button class="close-btn" onclick="closeRules()"><i class="fa-solid fa-xmark"></i></button>
            </div>
            <div class="modal-body">
                <h3>1. Общие положения</h3>
                <ul>
                    <li><strong>1.1.</strong> Каждый игрок, регистрируясь на ресурсах проекта KRAPINN RUSSIA, соглашается с правилами.</li>
                    <li><strong>1.2.</strong> Незнание правил не освобождает от ответственности.</li>
                    <li><strong>1.3.</strong> Руководство проекта оставляет за собой право менять регламент наказаний.</li>
                </ul>

                <h3>2. Правила форума и чатов</h3>
                <ul>
                    <li><strong>2.1.</strong> Запрещен оффтоп, спам и оскорбления участников в любых разделах.</li>
                    <li><strong>2.2.</strong> Запрещена публикация сторонних ссылок, вирусного ПО или читов.</li>
                    <li><strong>2.3.</strong> Выдача себя за администрацию карается перманентной блокировкой.</li>
                </ul>

                <h3>3. Безопасность</h3>
                <ul>
                    <li><strong>3.1.</strong> Администрация никогда не просит пароли от ваших аккаунтов.</li>
                    <li><strong>3.2.</strong> Продажа, передача или покупка аккаунтов/игровых ценностей за реальные деньги запрещена.</li>
                </ul>
            </div>
        </div>
    </div>

    <script>
        /* === Интерактивный Canvas Фон без сканера === */
        const canvas = document.getElementById('bgCanvas');
        const ctx = canvas.getContext('2d');

        let particles = [];
        let width = canvas.width = window.innerWidth;
        let height = canvas.height = window.innerHeight;

        window.addEventListener('resize', () => {
            width = canvas.width = window.innerWidth;
            height = canvas.height = window.innerHeight;
            initParticles();
        });

        class Particle {
            constructor() {
                this.reset();
            }

            reset() {
                this.x = Math.random() * width;
                this.y = Math.random() * height;
                this.size = Math.random() * 2 + 0.5;
                this.speedX = (Math.random() - 0.5) * 0.4;
                this.speedY = -Math.random() * 0.6 - 0.2;
                this.alpha = Math.random() * 0.6 + 0.1;
            }

            update() {
                this.x += this.speedX;
                this.y += this.speedY;

                if (this.y < 0 || this.x < 0 || this.x > width) {
                    this.reset();
                    this.y = height;
                }
            }

            draw() {
                ctx.fillStyle = `rgba(255, 30, 39, ${this.alpha})`;
                ctx.beginPath();
                ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
                ctx.fill();
            }
        }

        function initParticles() {
            particles = [];
            const count = Math.floor((width * height) / 10000);
            for (let i = 0; i < count; i++) {
                particles.push(new Particle());
            }
        }

        function animateCanvas() {
            ctx.clearRect(0, 0, width, height);
            particles.forEach(p => {
                p.update();
                p.draw();
            });
            requestAnimationFrame(animateCanvas);
        }

        initParticles();
        animateCanvas();

        /* === Логика точного таймера (до 18:00 по МСК) === */
        function updateTimer() {
            const now = new Date();
            
            // Текущее время UTC в МСК (UTC+3)
            const utcTime = now.getTime() + (now.getTimezoneOffset() * 60000);
            const mskNow = new Date(utcTime + (3 * 3600000));
            
            // Целевое время: Сегодня 18:00 МСК
            let target = new Date(mskNow);
            target.setHours(18, 0, 0, 0);

            // Если 18:00 МСК уже прошло, устанавливаем на завтра 18:00
            if (mskNow >= target) {
                target.setDate(target.getDate() + 1);
            }

            const diff = target - mskNow;

            const h = Math.floor((diff / (1000 * 60 * 60)) % 24);
            const m = Math.floor((diff / (1000 * 60)) % 60);
            const s = Math.floor((diff / 1000) % 60);

            document.getElementById('hours').innerText = String(h).padStart(2, '0');
            document.getElementById('minutes').innerText = String(m).padStart(2, '0');
            document.getElementById('seconds').innerText = String(s).padStart(2, '0');
        }

        setInterval(updateTimer, 1000);
        updateTimer();

        /* === Модальное окно === */
        function openRules() {
            const modal = document.getElementById('rulesModal');
            modal.classList.add('active');
        }

        function closeRules() {
            const modal = document.getElementById('rulesModal');
            modal.classList.remove('active');
        }

        window.onclick = function(event) {
            const modal = document.getElementById('rulesModal');
            if (event.target === modal) {
                closeRules();
            }
        }
    </script>
</body>
</html>
