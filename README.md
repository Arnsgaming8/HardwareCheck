<style>
        body {
            font-family: 'Courier New', Courier, monospace;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .download-button {
            background-color: #0055AA;
            color: white;
            padding: 15px 30px;
            font-size: 18px;
            font-weight: bold;
            border: 3px outset #0066CC;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
            display: inline-block;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
        }

        .download-button:hover {
            background-color: #004488;
            border-color: #0055AA;
        }

        .download-button:active {
            border-style: inset;
            box-shadow: 1px 1px 3px rgba(0, 0, 0, 0.3);
        }
    </style>
</head>
<body>
    <!-- Change the href attribute to your file path -->
    <a href="../Device Hardware Check/RunHardwareCheck.bat" download="RunHardwareCheck.bat" class="download-button">Download Hardware Check</a>
</body>
</html>
