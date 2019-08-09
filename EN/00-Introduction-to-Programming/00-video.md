[slide]
# Training Session

[vimeo-video videoId="342590118" /]
[html]
    <style>  
    .someCustomTrackSection{
    border:1px solid yellow;
    }
  </style>
  <script src="https://code.jquery.com/jquery-3.4.1.min.js" integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo="   crossorigin="anonymous"></script>
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
