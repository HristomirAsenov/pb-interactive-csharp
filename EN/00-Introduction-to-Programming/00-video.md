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
      let previouslySelectedElements = document.getElementsByClassName("sectionTracker");
      if (previouslySelectedElements.length > 0) {
         previouslySelectedElements[0].className = "content-link";
      }
      let urlId = window.location.hash;
      console.log(urlId);
      let currElement = document.querySelector(`.lesson-navigation-section a.content-link[href="${urlId}"]`);
      console.log(currElement);
      currElement.className = "content-link sectionTracker";
    }
  </script>
[/html]
[/slide]
