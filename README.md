<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Constitution of the United States</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: "Times New Roman", serif;
            background: linear-gradient(to right, #b22234 50%, #3c3b6e 50%);
        }

        header {
            background-color: #00205b; /* Dark blue header */
            color: #ffffff; /* White text */
            text-align: center;
            padding: 20px 0;
        }

        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
            background-color: #ffffff; /* White content background */
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1); /* Subtle shadow effect */
        }

        h1 {
            font-size: 24px;
            margin-bottom: 20px;
            text-align: center;
            color: #ffffff; /* White heading color */
        }

        p {
            font-size: 18px;
            line-height: 1.6;
            color: #ffffff; /* White text color */
        }

        footer {
            background-color: #00205b; /* Dark blue footer */
            color: #ffffff; /* White text */
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .stars {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
        }

        .stars:before {
            content: ' ';
            display: block;
            position: absolute;
            top: -1000px;
            left: -1000px;
            width: 3000px;
            height: 3000px;
            background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="100%" height="100%" viewBox="0 0 100 100" preserveAspectRatio="none"><text x="50%" y="50%" font-size="50" fill="white" text-anchor="middle">☆</text></svg>');
            background-size: 50px;
            animation: twinkle 10s linear infinite;
        }

        @keyframes twinkle {
            0% {
                transform: translateY(-2000px);
            }
            100% {
                transform: translateY(2000px);
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Constitution of the United States</h1>
    </header>
    
    <div class="container">
        <p>We the People of the United States, in Order to form a more perfect Union, establish Justice, insure domestic Tranquility, provide for the common defence, promote the general Welfare, and secure the Blessings of Liberty to ourselves and our Posterity, do ordain and establish this Constitution for the United States of America.</p>
       
    </div>
    
   

    <div class="stars"></div>
</body>
</html>
