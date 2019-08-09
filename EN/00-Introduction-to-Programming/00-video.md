[slide]
# Training Session

[vimeo-video videoId="342590118" /]
[html]
    <style>  
    .someCustomTrackSection{
     text-decoration: underline;
     color: #ffa000;
    }
  </style>
  <script>
    window.onhashchange = function() { 
      let previouslySelectedElement = document.querySelector(".someCustomTrackSection");
      if (previouslySelectedElement) {
         previouslySelectedElement.className = "content-link";
      }
      let urlId = window.location.hash;
      console.log(urlId);
      let currElement = document.querySelector(`.lesson-navigation-section a.content-link[href="${urlId}"]`);
      console.log(currElement);
      currElement.className = "";
      currElement.className = "content-link someCustomTrackSection";
    }
  </script>
[/html]
[/slide]
