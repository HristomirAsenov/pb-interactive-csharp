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
      let previouslySelectedElement = document.querySelectorAll(".someCustomTrackSection");
      if (previouslySelectedElement) {
         previouslySelectedElement[0].classList.remove("someCustomTrackSection");
      }
      let urlId = window.location.hash;
      document.querySelectorAll(`.lesson-navigation-section a.content-link[href="${urlId}"]`)[0].classList.add("someCustomTrackSection");
    }
  </script>
[/html]
[/slide]
