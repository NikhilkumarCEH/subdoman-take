<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="app.css">
</head>

<body>

    <div class="main">
        <div class="box">
            <span id="pass-box">Testing</span>
            <div class="row">
                <div class="left">
                    Password Length
                </div>
                <div class="right">
                    <input type="number" id="total-char" max="30" min="2" value="10">
                </div>
            </div>
            <div class="row">
                <label for="upper-case">
                    <div class="left">
                        Contains Uppercase
                    </div>
                </label>
                <div class="right">
                    <input type="checkbox" id="upper-case" checked>
                </div>
            </div>
            <div class="row">
                <label for="lower-case">
                    <div class="left">
                        Contains Lowercase
                    </div>
                </label>
                <div class="right">
                    <input type="checkbox" id="lower-case">
                </div>
            </div>
            <div class="row">
                <label for="symbols">
                    <div class="left">
                        Contains Symbols
                    </div>
                </label>
                <div class="right">
                    <input type="checkbox" id="symbols">
                </div>
            </div>
            <div class="row">
                <label for="number">
                    <div class="left">
                        Contains Number
                    </div>
                </label>
                <div class="right">
                    <input type="checkbox" id="number">
                </div>
            </div>
            <div class="row">
                <button id="btn">
                    Generate
                </button>
            </div>
        </div>
    </div>

    <script src="app.js"></script>
</body>

</html>
