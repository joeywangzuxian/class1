<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        .main{
            background-color: white;
            border: solid 1px #cccccc;
            width: 480px;
            height: 480px;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
            position: absolute;
            padding: 30px;
        }
        .grid{
            background-color: yellow;
            border: solid 1px yellow;
            border-radius: 10px;
            width: 25%;
            height: 25%;
        }

        .one{
            float: left;
        }
        .two{
            float: right;
        }
        .three{
            background-color: yellow;
            margin: 0 37.5%;
        }
        .four{
            float: left;
            margin: 12.5% 68.75% 37.5% 0;
        }
        .fife{
            float: right;
            margin-top: -62.5%;
        }
        .six{
            margin-top: 12.5%;
            margin-left: 37.5%;
        }
        .seven{
            float: left;
            margin-top: -25%;
        }
        .eight{
            float: right;
            margin-top: -25%;
        }
        .nine{
            float: right;
            background-color: yellow;
            margin-top: -25%;
            margin-right: 12.5%;
        }


    </style>
</head>
<body>
<div class="main">
    <div class="grid one"></div>
    <div class="grid two" ></div>
    <div class="grid three"></div>
    <div class="grid four"></div>
    <div class="grid fife"></div>
    <div class="grid six"></div>
    <div class="grid seven"></div>
    <div class="grid eight"></div>
    <div class="grid nine"></div>
</div>
</body>
</html>
