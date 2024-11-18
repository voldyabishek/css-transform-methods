# css-transform-methods

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Transform Methods</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
            height: 100vh;
            margin: 0;
            background-color:#195625;
        }

        .container {
            margin: 20px;
            display: inline-block;
        }

        .box {
            width: 100px;
            height: 100px;
            background-color: #ff6347; /* Tomato color */
            margin-bottom: 10px;
            display: inline-block;
            text-align: center;
            line-height: 100px;
            color: white;
            font-weight: bold;
        }

        /* Transform: translate */
        .translate {
            transform: translate(20px, 20px);
        }

        /* Transform: rotate */
        .rotate {
            transform: rotate(45deg);
        }

        /* Transform: scale */
        .scale {
            transform: scale(1.5);
        }

        /* Transform: skew */
        .skew {
            transform: skew(10deg, 10deg);
        }

        /* Transform: translateX and translateY */
        .translateX {
            transform: translateX(100px);
        }

        .translateY {
            transform: translateY(100px);
        }

        /* Transform: scaleX and scaleY */
        .scaleX {
            transform: scaleX(2);
        }

        .scaleY {
            transform: scaleY(2);
        }

        /* Transform: skewX and skewY */
        .skewX {
            transform: skewX(10deg);
        }

        .skewY {
            transform: skewY(10deg);
        }


        h1 {
            width: 100%;
            text-align: center;
            margin-bottom: 40px;
        }

    </style>
</head>
<body>

    <h1>CSS Transform Methods</h1>

    <!-- Translate -->
    <div class="container">
        <div class="box translate">Translate</div>
    </div>

    <!-- Rotate -->
    <div class="container">
        <div class="box rotate">Rotate</div>
    </div>

    <!-- Scale -->
    <div class="container">
        <div class="box scale">Scale</div>
    </div>

    <!-- Skew -->
    <div class="container">
        <div class="box skew">Skew</div>
    </div>

    <!-- TranslateX -->
    <div class="container">
        <div class="box translateX">TranslateX</div>
    </div>

    <!-- TranslateY -->
    <div class="container">
        <div class="box translateY">TranslateY</div>
    </div>

    <!-- ScaleX -->
    <div class="container">
        <div class="box scaleX">ScaleX</div>
    </div>

    <!-- ScaleY -->
    <div class="container">
        <div class="box scaleY">ScaleY</div>
    </div>

    <!-- SkewX -->
    <div class="container">
        <div class="box skewX">SkewX</div>
    </div>

    <!-- SkewY -->
    <div class="container">
        <div class="box skewY">SkewY</div>
    </div>

  

</body>
</html>
