<html lang="en">
<script>
    function getQueryVariable(variable)
    {
        var query = window.location.search.substring(1);
        var vars = query.split("&");
        for (var i=0;i<vars.length;i++) {
                var pair = vars[i].split("=");
                if(pair[0] == variable){return pair[1];}
        }
        return(false);
    }
</script>

<head>

    <title>Video.js | HTML5 Video Player</title>
    <link href="video-js.css" rel="stylesheet">
    <script src="video.js"></script>

</head>
<body>
    
  <video id="videoPlayer" class="video-js vjs-default-skin" controls preload="none" width="80%" max-width="100%" height="364" poster="https://i.imgur.com/0nepAeW.png">
    <source id="mp4source" src="" type="video/mp4">

    <!-- Tracks need an ending tag thanks to IE9 -->
    
    <p class="vjs-no-js">To view this video please enable JavaScript, and consider upgrading to a web browser that <a href="http://videojs.com/html5-video-support/" target="_blank">supports HTML5 video</a></p>
  </video>

</body>


  <script type="text/javascript">
    var mirror = decodeURIComponent(getQueryVariable("url"));
    document.querySelector("#videoPlayer > source").src = mirror;   
    var player = videojs('videoPlayer');
    player.play();
  </script>

</html>
