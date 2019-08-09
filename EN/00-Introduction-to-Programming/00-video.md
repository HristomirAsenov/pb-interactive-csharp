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
         previouslySelectedElement.classList.remove("someCustomTrackSection");
      }
      let urlId = window.location.hash;
      document.querySelector(`.lesson-navigation-section a.content-link[href="${urlId}"]`).classList.add("someCustomTrackSection");
    }
  </script>
[/html]
[/slide]
