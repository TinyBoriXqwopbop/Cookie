<html>
<head>
  <style>
    body, html, iframe {
      margin: 0;
      padding: 0;
      height: 100%;
      width: 100%;
      overflow: hidden;
    }

    .forceIosScrolling {
      overflow: scroll;
      -webkit-overflow-scrolling: touch;
    }
  </style>
  <script src="https://apis.google.com/_/scs/abc-static/_/js/k=gapi.lb.en.z9QjrzsHcOc.O/m=gapi_rpc/rt=j/sv=1/d=1/ed=1/rs=AHpOoo8359JQqZQ0dzCVJ5Ui3CZcERHEWA/cb=gapi.loaded_0?le=scs" async=""></script>
  <script src="https://apis.google.com/js/api.js?checkCookie=1" gapi_processed="true"></script>
</head>

<body>
  <iframe id="innerFrame" name="innerFrame" sandbox="allow-scripts allow-popups allow-forms allow-same-origin allow-popups-to-escape-sandbox allow-downloads" frameborder="0" allowfullscreen="" src="https://advanced-channeler.02.gz-associates.com/?t=tmm-cookieclicker" style="overflow: auto;"></iframe>

  <button onclick="toggleFullscreen()">Toggle Fullscreen</button>

  <script>
    function toggleFullscreen() {
      const iframe = document.getElementById('innerFrame');

      if (iframe.requestFullscreen) {
        if (document.fullscreenElement) {
          document.exitFullscreen();
        } else {
          iframe.requestFullscreen();
        }
      } else if (iframe.mozRequestFullScreen) {
        if (document.mozFullScreenElement) {
          document.mozCancelFullScreen();
        } else {
          iframe.mozRequestFullScreen();
        }
      } else if (iframe.webkitRequestFullscreen) {
        if (document.webkitFullscreenElement) {
          document.webkitExitFullscreen();
        } else {
          iframe.webkitRequestFullscreen();
        }
      } else if (iframe.msRequestFullscreen) {
        if (document.msFullscreenElement) {
          document.msExitFullscreen();
        } else {
          iframe.msRequestFullscreen();
        }
      }
    }
  </script>
</body>
</html>
