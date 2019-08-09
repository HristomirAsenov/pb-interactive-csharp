[slide]
# Training Session

[vimeo-video videoId="342590118" /]
[html]
   <style>  
    #sectionTracker{
     background-color: orange;
    }
  </style>
  <script>
    window.onhashchange = function() { 
      let urlId = window.location.hash;
      console.log(urlId);
      let currElement = document.querySelector(`.lesson-navigation-section a.content-link[href="${urlId}"]`);
      console.log(currElement);
      currElement.id = "sectionTracker";
    }
  </script>
[/html]
[/slide]
