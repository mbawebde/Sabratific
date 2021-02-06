



# Welcome to Sabratific - Detailed Website Coming Soon
##  Vision Statement
To bring to awareness the possibilities of digital entrepreneurship
<iframe src="https://storage.ning.com/topology/rest/1.0/file/get/8525106258?profile=original" style="border:0px #ffffff none;" name="myiFrame" scrolling="no" frameborder="1" marginheight="0px" marginwidth="0px" height="900px" width="900px" allowfullscreen></iframe>
## Video Describing  Sabratific Goals and Services
<iframe width="760px" height="500px" src="https://sway.office.com/s/N6FhU6SCjJJst7fH/embed" frameborder="0" marginheight="0" marginwidth="0" max-width="100%" sandbox="allow-forms allow-modals allow-orientation-lock allow-popups allow-same-origin allow-scripts" scrolling="no" style="border: none; max-width: 100%; max-height: 100vh" allowfullscreen mozallowfullscreen msallowfullscreen webkitallowfullscreen></iframe>



Interested in working together to explore  the possiblities of Digital Business? 
Get started with a free e-book.



All features and services free for 30 days when Website Platform is setup compeletely.


## Social Media Channels
<iframe src="https://www.youtube.com/embed/-8HEFWKmpvU" frameborder="0" allowTransparency="true" style="border:none;overflow:hidden;width:480;height:360;"></iframe> 

## Support or Contact
Feel free to contact us.
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
      status.innerHTML = "Thanks!";
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

