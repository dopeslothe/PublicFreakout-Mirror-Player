## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/dopeslothe/PublicFreakout-Mirror-Player/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/dopeslothe/PublicFreakout-Mirror-Player/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.


<html lang="en">
<head>

    <title>Video.js | HTML5 Video Player</title>
    <link href="http://vjs.zencdn.net/5.19/video-js.css" rel="stylesheet">
    <script src="http://vjs.zencdn.net/ie8/1.1/videojs-ie8.min.js"></script>
    <script src="http://vjs.zencdn.net/5.19/video.js"></script>

</head>
<body>

  <video id="example_video_1" class="video-js vjs-default-skin" controls preload="none" width="640" height="264" poster="http://vjs.zencdn.net/v/oceans.png" data-setup="{}">
    <source src="http://vjs.zencdn.net/v/oceans.mp4" type="video/mp4">
    <source src="http://vjs.zencdn.net/v/oceans.webm" type="video/webm">
    <source src="http://vjs.zencdn.net/v/oceans.ogv" type="video/ogg">
    <track kind="captions" src="../shared/example-captions.vtt" srclang="en" label="English"></track>
    <!-- Tracks need an ending tag thanks to IE9 -->
    <track kind="subtitles" src="../shared/example-captions.vtt" srclang="en" label="English"></track>
    <!-- Tracks need an ending tag thanks to IE9 -->
    <p class="vjs-no-js">To view this video please enable JavaScript, and consider upgrading to a web browser that <a href="http://videojs.com/html5-video-support/" target="_blank">supports HTML5 video</a></p>
  </video>

</body>

</html>
