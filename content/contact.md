---
title: "Contact"
date: 2020-10-15T12:09:02+02:00
---

# Get in touch
<style>
   input[type=text], select, textarea{
     width: 100%;
     padding: 12px;
     border: 1px solid #ccc;
     border-radius: 4px;
     box-sizing: border-box;
     resize: vertical;
   }

   label {
     padding: 12px 12px 12px 0;
     display: inline-block;
   }

   input[type=submit] {
     background-color: #4CAF50;
     color: white;
     padding: 12px 20px;
     border: none;
     border-radius: 4px;
     cursor: pointer;
     float: right;
   }

   .col-75 {
     float: left;
     width: 75%;
     margin-top: 6px;
   }

   .row:after {
     content: "";
     display: table;
     clear: both;
   }

   @media screen and (max-width: 600px) {
     .col-25, .col-75, input[type=submit] {
       width: 100%;
       margin-top: 0;
     }
   }
</style>

<div class="container">
  <form action="https://formspree.io/f/xnqopppw" method="POST">

    <div class="row">
     <div class="col-75">
       <label for="fname">Name</label>
     </div>
     <div class="col-75">
       <input type="text" id="fname" name="firstname" placeholder="Your name">
     </div>
   </div>

   <div class="row">
     <div class="col-75">
       <label for="email">Email</label>
     </div>
     <div class="col-75">
       <input type="email" id="lname" name="_replyto" placeholder="Your email">
     </div>
   </div>

   <div class="row">
     <div class="col-75">
       <label for="subject">Message</label>
     </div>
     <div class="col-75">
       <textarea id="subject" name="subject" placeholder="Your message" style="height:200px"></textarea>
     </div>
   </div>

   <div class="row">
   <input type="submit" value="Send">
   </div>

  </form>
</div>

# Find me
<style>
   .google-maps {
       position: relative;
       padding-bottom: 75%; // This is the aspect ratio
       height: 0;
       overflow: hidden;
   }
   .google-maps iframe {
       position: absolute;
       top: 0;
       left: 0;
       width: 100% !important;
       height: 100% !important;
   }
</style>

<div class="google-maps">
   <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2595.5430462631693!2d8.671356151057863!3d49.41754657924488!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4797c1302f8845db%3A0x63a8f54f161199ab!2sIm%20Neuenheimer%20Feld%20267%2C%2069120%20Heidelberg!5e0!3m2!1sen!2sde!4v1602596792233!5m2!1sen!2sde" width="600" height="450" frameborder="0" style="border:0"></iframe>
</div>
