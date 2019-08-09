[slide]
# Training Session

[vimeo-video videoId="342590118" /]
[html]
    <style>  
    .sectionTracker{
     color: #ffa000;
    }
  </style>
  <script>
    window.onhashchange = function() { 
      let urlId = window.location.hash;
      console.log(urlId);
      let currElement = document.querySelector(`.lesson-navigation-section a.content-link[href="${urlId}"]`);
      console.log(currElement);
      currElement.className = "content-link sectionTracker";
    }
  </script>
[/html]
[/slide]
