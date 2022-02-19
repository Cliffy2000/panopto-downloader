# iPanopto - a Panopto video download Chrome extension

This is an extension that uses the RSS links found in the html code of Panopto pages to reach and download videos on Panopto.

### Installation
Download the folder that contains the files included in the extension, and add the folder to chrome using the load unpacked option under manage extensions.

### Usage
To use it, navigate to the folder with the list of videos and click on the extension to select the desired videos. 

<html>

<head>
  <title>iPanopto Downloader</title>
  <meta charset="UTF-8">
  <meta name="description" content="iPanopto - Chrome extension for Panopto video downloading">
  <meta name="keywords" content="Chrome, Panopto, iPanopto, video, download">
  <meta name="author" content="Cliff Yang, Wayne Wang">
  <link rel="stylesheet" href="download.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap">
  <link rel="icon" href="iPanopto.png">
</head>

<body>
  <div id="wrapper">
    <div id="name">
        <img src="iPanopto.png" id="logo">
        <div id="titleTextDiv">
          <p id="titleText1">iPanopto</p>
          <p id="titleText2">Panopto Video Downloader</p>
        </div>
    </div>

    <div id="button">
      <button class="download-pushable" role="button">
        <span class="download-shadow"></span>
        <span class="download-edge"></span>
        <span class="download-front text">
          Download
        </span>
      </button>
    </div>

    <div id="notification">
      <span>Now also available on Chrome extension store!</span>
    </div>

    <div id="description">
      <span>iPanopto</span>
      <span>Tired of watching Panopto videos online? Here is </span>      
      <span>https://developer.chrome.com/docs/extensions/mv3/getstarted/#unpacked</span>
    </div>
  </div>
</body>

</html>