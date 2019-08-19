# Display-element-by-the-name-using-javascript

// Display element by the name using javascript
// First create html element,

<ul>
     <li name="lname">Red</li>
     <li  name="lname">Blue</li>
     <li  name="lname">Green</li>
</ul>


// now create a function,

function show(){
    var y = document.getElementsByName("lname");
    document.getElementById("display").innerHTML= y[2].innerHTML;
}

// now create a p tag to display the output,

<p id="display"></p>

// now create a button,

<button type="button" onclick="show()">Check Now</button>


//OUTPUT


Green


//


// Thank you for reading the post. Have a great day!
