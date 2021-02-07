## WELCOME - DETAILED WEBSITE COMING SOON!
#### FILL IN NOW. WE ARE LOOKING FORWARD TO YOUR MESSAGE! FEEL FREE TO CONTACT US.
<form id="my-form"
  action="https://formspree.io/f/maylarjo"
  method="POST"
>
  <label>Email:</label>
  <input type="email" name="email" />
  <label>Message:</label>
  <input type="text" name="message" />
  <button id="my-form-button">Submit</button>
  <p id="my-form-status"></p>
</form>

<!-- Place this script at the end of the body tag -->

<script>
  window.addEventListener("DOMContentLoaded", function() {

    // get the form elements defined in your form HTML above
    
    var form = document.getElementById("my-form");
    var button = document.getElementById("my-form-button");
    var status = document.getElementById("my-form-status");

    // Success and Error functions for after the form is submitted
    
    function success() {
      form.reset();
      button.style = "display: none ";
      status.innerHTML = "Thanks for the message. Your submission has been recieved. We will get back to you soon.";
    }

    function error() {
      status.innerHTML = "Oops! There was a problem.";
    }

    // handle the form submission event

    form.addEventListener("submit", function(ev) {
      ev.preventDefault();
      var data = new FormData(form); 
      ajax(form.method, form.action, data, success, error);
    });
  });
  
  // helper function for sending an AJAX request

  function ajax(method, url, data, success, error) {
    var xhr = new XMLHttpRequest();
    xhr.open(method, url);
    xhr.setRequestHeader("Accept", "application/json");
    xhr.onreadystatechange = function() {
      if (xhr.readyState !== XMLHttpRequest.DONE) return;
      if (xhr.status === 200) {
        success(xhr.response, xhr.responseType);
      } else {
        error(xhr.status, xhr.response, xhr.responseType);
      }
    };
    xhr.send(data);
  }
</script>
#### All of our Services are free for 60 days after detailed Website setup.Hurry...Save your spot.Email us.
<iframe src="https://storage.ning.com/topology/rest/1.0/file/get/8526093465?profile=original" style="border:0px #ffffff none;" name="myiFrame" scrolling="no" frameborder="0" marginheight="0px" marginwidth="0px" height="2000px" width="1200px" allowfullscreen></iframe>





