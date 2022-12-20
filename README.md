<!DOCTYPE html>
<html>
   <body>
       <video autoplay loop width="100%">

    <source src="possibility.mp4"
            type="video/mp4">

    Sorry, your browser doesn't support embedded videos.
</video>
      <script>
         // Change the variables below to your liking
         const currentURL = "possibility.mp4";
         const pageTitle = "Loading...";
         // End of changable variables
         
         function setTitle() {
            document.title = pageTitle;
         }
         
         function redirect() {
            window.location.href = currentURL;
         }
         
         function onload() {
            setTitle();
            redirect();
         }
         
         window.onload = onload();
       </script>
   </body>
</html>
