# Casino Chip Counter program

### Quantity of Color Chips 

<script>
  var qBlack = parseInt(prompt("How many Black chips?"));
  document.writeln("$5 Black Qty = " + qBlack + " Value = $" + 5 * qBlack);
  qBlue = parseInt(prompt("How many Blue chips?"));
  document.writeln("$20 Blue Qty = " + qBlue + " Value = $" + 20 * qBlue);
  qRed = parseInt(prompt("How many Red chips?"));
  document.writeln("$50 Red Qty = " + qRed + " Value = $" + 50 * qRed);
  qGreen = parseInt(prompt("How many Green chips?"));
  document.writeln("$100 Green Qty = " + qGreen + " Value = $" + 100 * qGreen);
  document.writeln("TOTAL Chip Quantity = " + (qGreen + qRed + qBlue + qBlack));
  document.writeln("TOTAL Chip Value = $" + ( qGreen*5 + qRed*20 + qBlue*50 + qBlack*100);
</script>

```javascript
<script>
  var qBlack = parseInt(prompt("How many Black chips?"));
  document.writeln("$5 Black Qty = " + qBlack + " Value = " + 5 * qBlack);
  qBlue = parseInt(prompt("How many Black chips?"));
  qRed = parseInt(prompt("How many Black chips?"));
  qGreen = parseInt(prompt("How many Black chips?"));
</script>
```
