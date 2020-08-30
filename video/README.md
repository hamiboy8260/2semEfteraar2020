# JavaScript Boilerplate: Video

Here is a vanilla Javascript for videos. In this case the event listener works on the element via onclick(). A more elegant solution would be to add an eventlistener along these lines:

~~~~
// in the html:
<button id="shutUp">

// in the Javascript
var myVideo = document.getElementById("myVideo");
myVideo.width = 420;
myVideo.controls = true;

shutUp.addEventListener("click", shutUpPlease);

function shutUpPlease(){
  myVideo.muted = true;
}

// ..... etc. .....

~~~~

Feel free to enhance the code.