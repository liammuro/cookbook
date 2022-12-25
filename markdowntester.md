# markdowntester

## ingredients

<details>
    <summary>Toggle Switch</summary>
    Foldable Content[enter image description here][1]
</details>

<button onclick="myFunction()">Click Me</button>

<div id="myDIV">Hello</div>

<script>
    function myFunction() {
        var x = document.getElementById("myDIV");
        if (x.innerHTML === "Hello") {
            x.innerHTML = "Swapped text!";
        } else {
            x.innerHTML = "Hello";
        }
    }
<script>

<!-- Rectangular switch -->
<label class="switch">
  <input type="checkbox">
  <span class="slider"></span>
</label>

<!-- Rounded switch -->
<label class="switch">
  <input type="checkbox">
  <span class="slider round"></span>
</label>
