### Polluting the global namespace
####

  <pre class="javascript">
<code>
var x = 10;
function example() {
    var x = 20;
    console.log(x); //Prints 20
}
example();
console.log(x); //Prints 10
</code>
  </pre>

<aside class="notes">Global variables are less likely to get garbage collected.</aside>
