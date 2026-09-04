<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Security Alert</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            background-color: #000000;
            font-family: Arial, Helvetica, sans-serif;
            display: flex;
            flex-direction: column; /* Stack the box and the new text vertically */
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        /* Responsive Container */
        .card {
            border: 4px solid #00ff00;
            background-color: #000000;
            width: 100%;
            max-width: 400px;
            padding: 30px 20px 15px 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            box-shadow: 0 0 15px rgba(0, 255, 0, 0.2);
        }

        /* Warning Icon */
        .warning-icon {
            width: 50px;
            height: 50px;
            margin-bottom: 15px;
            flex-shrink: 0;
        }

        /* Heading Title */
        .title {
            color: #0dca30;
            font-size: 1.5rem;
            font-weight: bold;
            margin-bottom: 20px;
            line-height: 1.2;
        }

        /* Description text */
        .body-text {
            color: #ffff00;
            font-size: 1rem;
            font-weight: bold;
            line-height: 1.4;
            margin-bottom: 40px;
        }

        /* Small blue footer text inside box */
        .footer-text {
            color: #00a2ff;
            font-size: 0.8rem;
            font-weight: bold;
            align-self: flex-start;
            word-break: break-word;
        }

        /* Cyan text outside and below the box */
        .external-credit {
            color: #00ffff; /* Cyan */
            font-size: 0.9rem;
            font-weight: bold;
            margin-top: 15px;
            text-align: center;
        }

        /* Adjustments for smaller mobile screens */
        @media (max-width: 360px) {
            .card {
                padding: 20px 15px 12px 15px;
            }
            .title {
                font-size: 1.3rem;
            }
            .body-text {
                font-size: 0.9rem;
                margin-bottom: 30px;
            }
        }
    </style>
</head>
<body>

    <div class="card">
        <!-- SVG Warning Triangle Logo -->
        <svg class="warning-icon" viewBox="0 0 24 24" fill="none" stroke="#ffff00" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <path d="M10.29 3.86L1.82 18a2 2 0 0 0 1.71 3h16.94a2 2 0 0 0 1.71-3L13.71 3.86a2 2 0 0 0-3.42 0z"></path>
            <line x1="12" y1="9" x2="12" y2="13"></line>
            <line x1="12" y1="17" x2="12.01" y2="17"></line>
        </svg>

        <div class="title">
            IP Address got leaked!
        </div>

        <div class="body-text">
            It looks like your IP address got leaked. Run a quick anti-virus check or change your IP address.
        </div>

        <div class="footer-text">
            CybersecurityProtocol.Engine
        </div>
    </div>

    <!-- Cyan text placed outside and below the green card -->
    <div class="external-credit">
        JohnV Security Measure
    </div>

</body>
</html>
