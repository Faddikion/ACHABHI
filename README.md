<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Subscribe to Download</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; margin: 50px; }
        .hidden { display: none; }
        button { padding: 10px 20px; font-size: 16px; }
    </style>
</head>
<body>
    <h2>Subscribe to PKxtion to Download the File</h2>
    
    <!-- YouTube Subscribe Button -->
    <a href="https://www.youtube.com/@PKxtion?sub_confirmation=1" target="_blank">
        <button>Subscribe on YouTube</button>
    </a>

    <p>After subscribing, click the button below:</p>
    <button onclick="verifySubscription()">I Subscribed</button>

    <!-- Download Button (Hidden by Default) -->
    <div id="download-section" class="hidden">
        <p>Thank you for subscribing! Click below to download:</p>
        <a href="your-file-link-here" download>
            <button>Download File</button>
        </a>
    </div>

    <script>
        function verifySubscription() {
            // Show the download button after user confirms subscription
            document.getElementById("download-section").classList.remove("hidden");
        }
    </script>
</body>
</html>
