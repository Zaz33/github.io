<!DOCTYPE html>
<html lang="hy">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ազատի ֆիլմերի կայք</title>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Roboto:wght@400;500&display=swap" rel="stylesheet" />
    <style>
        /* Բազային ստիլեր */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f2f3f7;
            color: #333;
            line-height: 1.6;
        }
        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 2.5rem;
            text-align: center;
            margin-top: 40px;
            color: #2c3e50;
        }
        /* Կառուցում ենք կոնտեյներ ֆիլմերի համար */
        .container {
            max-width: 1200px;
            margin: 30px auto;
            padding: 0 20px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        /* Ֆիլմի քարտ */
        .movie {
            background: #ffffff;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .movie:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
        }
        .movie img {
            width: 100%;
            height: auto;
            display: block;
        }
        .movie-content {
            padding: 15px;
        }
        .movie h3 {
            font-family: 'Playfair Display', serif;
            font-size: 1.4rem;
            margin-bottom: 8px;
            color: #34495e;
        }
        .movie p {
            font-size: 0.95rem;
            margin-bottom: 6px;
            color: #555;
        }
        .movie .year {
            font-weight: 500;
            color: #7f8c8d;
        }
        /* Footer */
        footer {
            text-align: center;
            margin: 50px 0 20px 0;
            font-size: 0.9rem;
            color: #777;
        }
        footer a {
            color: #3498db;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <h1>Բարի գալուստ Ազատի Ֆիլմերի Կայք 🎬</h1>

    <div class="container">
        <div class="movie">
            <img src="https://via.placeholder.com/300x450" alt="Ֆիլմ 1" />
            <div class="movie-content">
                <h3>Ֆիլմի Անվանում 1</h3>
                <p>Նկարագրություն: Սա հիանալի առաջին ֆիլմն է, որը ստեղծվել է մեր հայացքով …</p>
                <p class="year">Տարի՝ 2023</p>
            </div>
        </div>
        <div class="movie">
            <img src="https://via.placeholder.com/300x450" alt="Ֆիլմ 2" />
            <div class="movie-content">
                <h3>Ֆիլմի Անվանում 2</h3>
                <p>Նկարագրություն: Երկրորդ ֆիլմի մասին անձնական կարծիք, հիմնական կետերը և սյուժեների մասին կարճ …</p>
                <p class="year">Տարի՝ 2022</p>
            </div>
        </div>
        <div class="movie">
            <img src="https://via.placeholder.com/300x450" alt="Ֆիլմ 3" />
            <div class="movie-content">
                <h3>Ֆիլմի Անվանում 3</h3>
                <p>Նկարագրություն: Երրորդ ֆիլմի հետաքրքիր տվյալներ, գլխավոր դերասաններ և ռեժիսոր …</p>
                <p class="year">Տարի՝ 2021</p>
            </div>
        </div>
        <!-- Կարող ես անսահման ավելացնել նոր .movie արկղեր -->
    </div>

    <footer>
        <p>© 2025 Ազատ – <a href="https://zaz33.github.io">zaz33.github.io</a></p>
    </footer>
</body>
</html>
