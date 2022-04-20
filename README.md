# Slider-Animation-Effect

    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        html{
            width: 62.2em;
        }
        .center{
            width: 221vh;
            height: 99vh;
            display: grid;
            place-items: center;
            position: relative;
            font-size: 30px;
            background-color: rgb(58, 51, 72);
        }
        h1{
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
       color: white;
       position: relative;
       
        }
        h1::before{
            content:"~Awesome~" ;
            color: aqua;
            position: absolute;
            border-right: 2px solid aqua;
            animation: slider 3s linear infinite;
       overflow: hidden;
        }
        @keyframes slider {
            0%{
                width: 0%;
            }
            50%{
                width: 100%;
            }
            100%{
                width: 0%;
            }
        }
    </style>
</head>
<body>
    <div class="center">
        <h1>~Awesome~</h1>
    </div>

    </div>
</body>
</html>
