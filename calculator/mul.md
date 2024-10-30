# Multiplication

Enter numbers to multiply:

<input id="num1" type="number" placeholder="First number">
<input id="num2" type="number" placeholder="Second number">
<button onclick="calculateMul()">Calculate</button>

<h3 id="result">Result: </h3>

<script>
  function calculateMul() {
    const num1 = parseFloat(document.getElementById('num1').value);
    const num2 = parseFloat(document.getElementById('num2').value);
    document.getElementById('result').textContent = 'Result: ' + (num1 * num2);
  }
</script>
