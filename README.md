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

<html lang="en">
<head>

    <title>Video.js | HTML5 Video Player</title>
    <link href="video-js.css" rel="stylesheet">
    <script src="video.js"></script>

</head>
<body>

    alert("URL variables detected: " + getQueryVariable("id"))

  <video id="pf_mirror" class="video-js vjs-default-skin" controls preload="none" width="640" height="364" poster="https://i.imgur.com/0nepAeW.png" data-setup="{}">
    <source src="https://my.mixtape.moe/cqaidu.mp4" type="video/mp4">
<!--    <source src="http://vjs.zencdn.net/v/oceans.webm" type="video/webm">
    <source src="http://vjs.zencdn.net/v/oceans.ogv" type="video/ogg">
    <track kind="captions" src="../shared/example-captions.vtt" srclang="en" label="English"></track>
-->
    
    <!-- Tracks need an ending tag thanks to IE9 -->

    <!-- Tracks need an ending tag thanks to IE9 -->
    <p class="vjs-no-js">To view this video please enable JavaScript, and consider upgrading to a web browser that <a href="http://videojs.com/html5-video-support/" target="_blank">supports HTML5 video</a></p>
  </video>

</body>

</html>
