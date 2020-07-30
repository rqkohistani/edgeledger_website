https://github.com/lokesh/lightbox2
download the files
download the zip
go to dist folder
go css folder copy paste lightbox.min.css to your project folder
create a new folder js, in this js copy paste the lightbox.min.js
go to dist images and copy the pointers pictures
************************************************************

inserting classes the index.html or where they suppose to be
  <link rel="stylesheet" href="css/lightbox.min.css">

  ************************************************************
  for java script 
  paste all this down to the body tag
  <script src="js/lightbox.min.js"></script>
  To implement this we need to wrap them in links 
  to store them
  Old codes
  <div class="row">
        <div class="column">
          <a href="images/cases/cases1.jpg" data-lightbox="cases"
            data-title="Lorem ipsum dolor sit amet, consectetur adipisicing elit!">
            <img src="images/cases/cases1.jpg" alt="">
          </a>
New codes
   <a href="images/cases/cases1.jpg" data-lightbox="cases"
            data-title="Lorem ipsum dolor sit amet, consectetur adipisicing elit!">
            <img src="images/cases/cases1.jpg" alt="">
          </a>
Repeat for all pictures

************************************************************

For the lightbox we need jquery. inject this jquery code in your index.html
since you have your pictures there.
 <!-- jquery -->
  <script src="https://code.jquery.com/jquery-3.5.0.min.js"
    integrity="sha256-xNzN2a4ltkB44Mc/Jz3pT4iU1cmeR0FkXs4pru/JxaQ=" crossorigin="anonymous"></script>

    copy paste it from jquery.com 
