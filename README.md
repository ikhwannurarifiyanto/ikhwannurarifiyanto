<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ikhwan Nur Arifiyanto - Profile, Grandmaster AI Chess & Cyber Snake</title>
    <!-- Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <!-- Chessboard.js CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/chessboard-js/1.0.0/chessboard-1.0.0.min.css">
    
    <style>
        :root {
            --bg-dark: #0f172a;
            --accent: #6366f1;
            --accent-hover: #4f46e5;
            --board-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.7);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
        }

        body {
            background: radial-gradient(circle at center, #1e293b 0%, #0f172a 100%);
            color: #f8fafc;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }

        /* Container Komponen Profil */
        .profile-container {
            width: 100%;
            max-width: 800px;
            margin-bottom: 30px;
            text-align: center;
        }

        .profile-container img {
            max-width: 100%;
            height: auto;
        }

        .profile-container h3 {
            margin-top: 15px;
            margin-bottom: 10px;
            font-size: 1.5rem;
        }

        .profile-container p, .profile-container strong {
            font-size: 1.1rem;
        }

        .profile-links {
            margin-top: 15px;
            display: flex;
            justify-content: center;
            gap: 10px;
            flex-wrap: wrap;
        }

        hr.divider {
            width: 100%;
            max-width: 800px;
            border: 0;
            height: 1px;
            background: rgba(255, 255, 255, 0.1);
            margin: 20px 0 30px 0;
        }

        /* Container Catur */
        .header-title {
            margin-bottom: 20px;
            text-align: center;
        }

        .header-title h1 {
            font-size: 1.8rem;
            font-weight: 700;
        }

        .header-title h1 span {
            color: var(--accent);
        }

        .status-text {
            font-size: 0.9rem;
            color: #94a3b8;
            margin-top: 5px;
        }

        /* HD Board Container */
        .board-wrapper {
            position: relative;
            width: 480px;
            max-width: 90vw;
            box-shadow: var(--board-shadow);
            border-radius: 12px;
            overflow: hidden;
            border: 4px solid #334155;
        }

        #board {
            width: 100%;
        }

        /* Warna Papan HD Realistis */
        .white-1e1d3 {
            background-color: #e2d6b5 !important;
            color: #b58863;
        }

        .black-3c85d {
            background-color: #b88b4a !important;
            color: #f0d9b5;
        }

        /* Highlight untuk bidak yang disentuh/diklik */
        .highlight-selected {
            background-color: rgba(99, 102, 241, 0.6) !important;
        }

        /* Action Buttons minimalis */
        .actions {
            margin-top: 20px;
            display: flex;
            gap: 12px;
            width: 480px;
            max-width: 90vw;
            margin-bottom: 40px;
        }

        .btn {
            flex: 1;
            padding: 12px;
            border: none;
            border-radius: 10px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.2s ease;
            background: rgba(255, 255, 255, 0.1);
            color: #f8fafc;
        }

        .btn:hover {
            background: rgba(255, 255, 255, 0.2);
            transform: translateY(-2px);
        }

        .btn-restart {
            background: var(--accent);
        }

        .btn-restart:hover {
            background: var(--accent-hover);
        }

        /* Styles untuk Snake Game */
        .snake-container {
            position: relative;
            padding: 4px;
            border-radius: 16px;
            background: linear-gradient(135deg, #00f2fe, #4facfe, #00c6ff);
            box-shadow: 0 0 35px rgba(0, 242, 254, 0.3);
            margin-top: 10px;
            margin-bottom: 40px;
            max-width: 100%;
        }

        .canvas-wrapper {
            position: relative;
            background: #0d1117;
            border-radius: 12px;
            overflow: hidden;
        }

        canvas {
            display: block;
            background: radial-gradient(circle at center, #161b22 0%, #0d1117 100%);
            max-width: 100%;
            height: auto;
        }

        .overlay {
            position: absolute;
            top: 16px;
            left: 20px;
            color: #f0f6fc;
            font-size: 13px;
            letter-spacing: 1.5px;
            text-transform: uppercase;
            font-weight: 600;
            pointer-events: none;
            display: flex;
            align-items: center;
            gap: 10px;
            text-shadow: 0 2px 4px rgba(0,0,0,0.8);
            z-index: 10;
        }

        .badge {
            background: rgba(255, 0, 127, 0.2);
            border: 1px solid rgba(255, 0, 127, 0.5);
            color: #ff007f;
            padding: 3px 8px;
            border-radius: 6px;
            font-size: 11px;
        }
    </style>
</head>
<body>

    <!-- SECTION PROFIL GITHUB (Atas) -->
    <div class="profile-container">
        <div align="center">
            <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Ikhwan%20Nur%20Arifiyanto&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=38"/>

            <h3>👋 Hello, I'm Ikhwan</h3>

            <p><strong>🎨 Graphic Designer • 💻 Digital Creative • 🌐 Web Enthusiast</strong></p>

            <br>

            <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=36BCF7&center=true&vCenter=true&width=600&lines=Graphic+Designer;Digital+Creative;Web+Enthusiast;Visual+Content+Creator;Always+Learning+Something+New" />

            <br><br>

            <div class="profile-links">
                <a href="https://portofolio-i.my.canva.site/portofolio-ikhwan-nur" target="_blank">
                    <img src="https://img.shields.io/badge/Portfolio-Visit-111111?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" />
                </a>
                <a href="https://www.linkedin.com/in/ikhwan-nur-arifiyanto-7295953ab?utm_source=share_via&utm_content=profile&utm_medium=member_android" target="_blank">
                    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
                </a>
                <a href="https://www.instagram.com/ikhwannur__?stkn=dmRhd2M3a3h2YnY4" target="_blank">
                    <img src="https://img.shields.io/badge/Instagram-Follow-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
                </a>
            </div>
        </div>
    </div>

    <hr class="divider">

    <!-- SECTION GAME CATUR (Tengah) -->
    <div class="header-title">
        <h1>Grandmaster <span>AI Chess</span></h1>
        <div id="status" class="status-text">Sentuh bidak Anda untuk melangkah</div>
    </div>

    <!-- Papan Catur -->
    <div class="board-wrapper">
        <div id="board"></div>
    </div>

    <!-- Tombol Kontrol Minimalis -->
    <div class="actions">
        <button id="btn-restart" class="btn btn-restart">⚡ Game Baru</button>
        <button id="btn-undo" class="btn">↩️ Batal Langkah</button>
    </div>

    <hr class="divider">

    <!-- SECTION AUTONOMOUS CYBER SNAKE (Bawah) -->
    <div class="snake-container">
        <div class="canvas-wrapper">
            <div class="overlay">
                <span>AI Autonomous Snake</span>
                <span class="badge">HARD BOUNDARY</span>
            </div>
            <canvas id="snakeCanvas" width="800" height="400"></canvas>
        </div>
    </div>

    <!-- External CDNs -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/chess.js/0.10.3/chess.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/chessboard-js/1.0.0/chessboard-1.0.0.min.js"></script>

    <!-- Script Game Catur AI -->
    <script>
        const game = new Chess();
        let board = null;
        let stockfish = null;
        let selectedSquare = null;

        const STOCKFISH_WORKER_URL = 'https://cdnjs.cloudflare.com/ajax/libs/stockfish.js/10.0.2/stockfish.js';

        function initStockfish() {
            fetch(STOCKFISH_WORKER_URL)
                .then(res => res.blob())
                .then(blob => {
                    const workerUrl = URL.createObjectURL(blob);
                    stockfish = new Worker(workerUrl);

                    stockfish.onmessage = function(event) {
                        const message = event.data;
                        if (message.startsWith('bestmove')) {
                            const bestMove = message.split(' ')[1];
                            if (bestMove) {
                                game.move({
                                    from: bestMove.substring(0, 2),
                                    to: bestMove.substring(2, 4),
                                    promotion: 'q'
                                });
                                board.position(game.fen());
                                updateStatus();
                            }
                        }
                    };

                    stockfish.postMessage('uci');
                    stockfish.postMessage('ucinewgame');
                    // Tingkat kesulitan AI tetap Maksimal
                    stockfish.postMessage('setoption name Skill Level value 20');
                });
        }

        function makeAIMove() {
            if (game.game_over()) return;

            document.getElementById('status').innerText = '🤖 AI sedang melangkah...';
            
            stockfish.postMessage(`position fen ${game.fen()}`);
            // Dibatasi maksimal 300 ms (0.3 detik) agar respons secepat kilat
            stockfish.postMessage('go movetime 300');
        }

        function removeHighlights() {
            $('#board .square-55d63').removeClass('highlight-selected');
        }

        // Fitur Sentuh Bidak -> Sentuh Petak Tujuan
        function handleSquareClick(square) {
            if (game.game_over() || game.turn() === 'b') return;

            if (selectedSquare === null) {
                const piece = game.get(square);
                if (piece && piece.color === 'w') {
                    selectedSquare = square;
                    $('#board .square-' + square).addClass('highlight-selected');
                }
            } else {
                const move = game.move({
                    from: selectedSquare,
                    to: square,
                    promotion: 'q'
                });

                removeHighlights();
                const previousSquare = selectedSquare;
                selectedSquare = null;

                if (move === null) {
                    const piece = game.get(square);
                    if (piece && piece.color === 'w' && square !== previousSquare) {
                        selectedSquare = square;
                        $('#board .square-' + square).addClass('highlight-selected');
                    }
                    return;
                }

                board.position(game.fen());
                updateStatus();
                // Eksekusi AI langsung tanpa penundaan
                window.setTimeout(makeAIMove, 50);
            }
        }

        function updateStatus() {
            if (game.in_checkmate()) {
                document.getElementById('status').innerText = 'Skakmat! Permainan Selesai.';
            } else if (game.in_draw()) {
                document.getElementById('status').innerText = 'Remis / Seri!';
            } else {
                if (game.turn() === 'w') {
                    document.getElementById('status').innerText = game.in_check() ? '⚠️ SKAK! Giliran Anda' : 'Giliran Anda (Sentuh bidak)';
                } else {
                    document.getElementById('status').innerText = '🤖 Giliran AI...';
                }
            }
        }

        board = Chessboard('board', {
            position: 'start',
            draggable: false, // Mengharuskan mode sentuh/klik
            pieceTheme: 'https://chessboardjs.com/img/chesspieces/wikipedia/{piece}.png'
        });

        initStockfish();

        // Listener untuk Sentuhan/Klik pada Petak Papan
        $('#board').on('click', '.square-55d63', function () {
            const square = $(this).attr('data-square');
            handleSquareClick(square);
        });

        document.getElementById('btn-restart').addEventListener('click', () => {
            game.reset();
            board.start();
            removeHighlights();
            selectedSquare = null;
            updateStatus();
        });

        document.getElementById('btn-undo').addEventListener('click', () => {
            game.undo(); // Undo AI
            game.undo(); // Undo Pemain
            board.position(game.fen());
            removeHighlights();
            selectedSquare = null;
            updateStatus();
        });
    </script>

    <!-- Script Game Autonomous Cyber Snake -->
    <script>
        const canvas = document.getElementById("snakeCanvas");
        const ctx = canvas.getContext("2d");

        const GRID_SIZE = 20;
        const COLS = canvas.width / GRID_SIZE;
        const ROWS = canvas.height / GRID_SIZE;

        // Batas wilayah gerak Aman (Aman dari Dinding Luar)
        const MIN_X = 1;
        const MAX_X = COLS - 2;
        const MIN_Y = 1;
        const MAX_Y = ROWS - 2;

        let snake = [
          { x: 10, y: 10 },
          { x: 9, y: 10 },
          { x: 8, y: 10 }
        ];

        let dir = { x: 1, y: 0 };
        let food = generateFood();
        let particles = [];

        // Algoritma Penjelajah Aman
        function getNextDirection() {
          const head = snake[0];
          const possibleMoves = [
            { x: 1, y: 0 },
            { x: -1, y: 0 },
            { x: 0, y: 1 },
            { x: 0, y: -1 }
          ];

          // Filter: HANYA BOLEH GERAK DI DALAM AREA SAFE ZONE (MIN_X s/d MAX_X, MIN_Y s/d MAX_Y)
          const validMoves = possibleMoves.filter(move => {
            const nextX = head.x + move.x;
            const nextY = head.y + move.y;

            const isInsideWall = nextX >= MIN_X && nextX <= MAX_X && nextY >= MIN_Y && nextY <= MAX_Y;
            const isSelfCollision = snake.some(segment => segment.x === nextX && segment.y === nextY);

            return isInsideWall && !isSelfCollision;
          });

          // Jika terjebak tanpa opsi aman, terpaksa reset game
          if (validMoves.length === 0) return null;

          // Pilih jalur terdekat menuju makanan
          validMoves.sort((a, b) => {
            const distA = Math.abs((head.x + a.x) - food.x) + Math.abs((head.y + a.y) - food.y);
            const distB = Math.abs((head.x + b.x) - food.x) + Math.abs((head.y + b.y) - food.y);
            return distA - distB;
          });

          return validMoves[0];
        }

        function generateFood() {
          let newFood;
          while (!newFood || snake.some(segment => segment.x === newFood.x && segment.y === newFood.y)) {
            newFood = {
              x: Math.floor(Math.random() * (MAX_X - MIN_X + 1)) + MIN_X,
              y: Math.floor(Math.random() * (MAX_Y - MIN_Y + 1)) + MIN_Y
            };
          }
          return newFood;
        }

        function createParticles(x, y) {
          for (let i = 0; i < 12; i++) {
            particles.push({
              x: x * GRID_SIZE + GRID_SIZE / 2,
              y: y * GRID_SIZE + GRID_SIZE / 2,
              vx: (Math.random() - 0.5) * 4,
              vy: (Math.random() - 0.5) * 4,
              alpha: 1,
              size: Math.random() * 3 + 1
            });
          }
        }

        function resetGame() {
          snake = [
            { x: 10, y: 10 },
            { x: 9, y: 10 },
            { x: 8, y: 10 }
          ];
          dir = { x: 1, y: 0 };
          food = generateFood();
        }

        function update() {
          const nextDir = getNextDirection();

          // Reset jika AI terpojok / menabrak
          if (!nextDir) {
            resetGame();
            return;
          }

          dir = nextDir;
          const head = { x: snake[0].x + dir.x, y: snake[0].y + dir.y };

          snake.unshift(head);

          // Cek Makan Makanan
          if (head.x === food.x && head.y === food.y) {
            createParticles(food.x, food.y);
            food = generateFood();
          } else {
            snake.pop();
          }

          // Update Efek Partikel
          particles.forEach((p, index) => {
            p.x += p.vx;
            p.y += p.vy;
            p.alpha -= 0.03;
            if (p.alpha <= 0) particles.splice(index, 1);
          });
        }

        function drawWalls() {
          // Draw Dinding Penghalang Padat (Solid Wall Blocks)
          ctx.fillStyle = "rgba(255, 0, 127, 0.15)";
          ctx.strokeStyle = "#ff007f";
          ctx.lineWidth = 2;

          // Gambar Blok Dinding Luar
          for (let x = 0; x < COLS; x++) {
            for (let y = 0; y < ROWS; y++) {
              if (x < MIN_X || x > MAX_X || y < MIN_Y || y > MAX_Y) {
                ctx.fillRect(x * GRID_SIZE, y * GRID_SIZE, GRID_SIZE, GRID_SIZE);
              }
            }
          }

          // Garis Neon Pembatas Dalam
          ctx.save();
          ctx.shadowBlur = 12;
          ctx.shadowColor = "#ff007f";
          ctx.strokeRect(
            MIN_X * GRID_SIZE,
            MIN_Y * GRID_SIZE,
            (MAX_X - MIN_X + 1) * GRID_SIZE,
            (MAX_Y - MIN_Y + 1) * GRID_SIZE
          );
          ctx.restore();
        }

        function drawGrid() {
          ctx.strokeStyle = "rgba(255, 255, 255, 0.02)";
          ctx.lineWidth = 1;
          for (let x = MIN_X * GRID_SIZE; x <= (MAX_X + 1) * GRID_SIZE; x += GRID_SIZE) {
            ctx.beginPath();
            ctx.moveTo(x, MIN_Y * GRID_SIZE);
            ctx.lineTo(x, (MAX_Y + 1) * GRID_SIZE);
            ctx.stroke();
          }
          for (let y = MIN_Y * GRID_SIZE; y <= (MAX_Y + 1) * GRID_SIZE; y += GRID_SIZE) {
            ctx.beginPath();
            ctx.moveTo(MIN_X * GRID_SIZE, y);
            ctx.lineTo((MAX_X + 1) * GRID_SIZE, y);
            ctx.stroke();
          }
        }

        function draw() {
          ctx.fillStyle = "#0d1117";
          ctx.fillRect(0, 0, canvas.width, canvas.height);

          drawGrid();
          drawWalls();

          // Draw Partikel
          particles.forEach(p => {
            ctx.save();
            ctx.globalAlpha = p.alpha;
            ctx.fillStyle = "#00f2fe";
            ctx.shadowBlur = 10;
            ctx.shadowColor = "#00f2fe";
            ctx.beginPath();
            ctx.arc(p.x, p.y, p.size, 0, Math.PI * 2);
            ctx.fill();
            ctx.restore();
          });

          // Draw Makanan (Pink Glowing Orb)
          ctx.save();
          ctx.fillStyle = "#ff007f";
          ctx.shadowBlur = 15;
          ctx.shadowColor = "#ff007f";
          ctx.beginPath();
          ctx.arc(
            food.x * GRID_SIZE + GRID_SIZE / 2,
            food.y * GRID_SIZE + GRID_SIZE / 2,
            GRID_SIZE / 2.8,
            0,
            Math.PI * 2
          );
          ctx.fill();
          ctx.restore();

          // Draw Ular (Gradient Blue-Cyan)
          snake.forEach((segment, index) => {
            ctx.save();
            
            const progress = index / snake.length;
            const color = index === 0 ? "#00f2fe" : `hsl(${190 + progress * 50}, 100%, 50%)`;
            
            ctx.fillStyle = color;
            ctx.shadowBlur = index === 0 ? 12 : 4;
            ctx.shadowColor = "#00f2fe";

            const x = segment.x * GRID_SIZE + 1;
            const y = segment.y * GRID_SIZE + 1;
            const size = GRID_SIZE - 2;
            const radius = index === 0 ? 6 : 4;

            ctx.beginPath();
            ctx.roundRect(x, y, size, size, radius);
            ctx.fill();

            ctx.restore();
          });
        }

        // Interval Kecepatan Gerak (80ms)
        setInterval(() => {
          update();
          draw();
        }, 80);
    </script>
</body>
</html>
