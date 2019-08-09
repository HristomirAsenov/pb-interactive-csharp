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
document.querySelectorAll(".lesson-navigation-section")
    .forEach((s) => s.querySelectorAll("a.content-link h4")
    .forEach((h) => h.addEventListener('click', (e) => {
      console.log(e.currentTarget);
      let previouslySelectedElement = document.querySelector(".someCustomTrackSection");
      if (previouslySelectedElement) {
         previouslySelectedElement.className = "";
      }
      e.currentTarget.className = "someCustomTrackSection";   
     })))
  </script>
[/html]
[/slide]
