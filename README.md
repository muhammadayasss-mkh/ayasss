<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>java script test</title>
</head>
<body>
  <script>
let roll = 1;
while (roll <= 20) {
  if (roll % 2 === 0) console.log(roll);
  roll++;
}

let marks = [60, 70, 80, 90];
let total = 0, i = 0;
while (i < marks.length) {
  total += marks[i];
  i++;
}
console.log("Total Marks:", total);

let num = 1234;
let rev = 0;
while (num > 0) {
  rev = rev * 10 + (num % 10);
  num = Math.floor(num / 10);
}
console.log("Reverse PIN:", rev);

let n = 5;
for (let i = 1; i <= 10; i++) {
  console.log(n + " x " + i + " = " + (n * i));
}


let num2 = 5678, rev2 = 0;
for (; num2 > 0; num2 = Math.floor(num2 / 10)) {
  rev2 = rev2 * 10 + (num2 % 10);
}
console.log("Reverse Number:", rev2);



let theory = 40, practical = 36;
if (theory >= 35 && practical >= 35)
  console.log("Pass");
else
  console.log("Fail");




let age = 20, hasID = true;
if (age >= 18 && hasID)
  console.log("Entry Allowed");
else
  console.log("Entry Not Allowed");




let day = "Sunday";
if (day === "Saturday" || day === "Sunday")
  console.log("Holiday");
else
  console.log("Working Day");




let phone = "", email = "abc@gmail.com";
if (phone || email)
  console.log("Contact Possible");
else
  console.log("No Contact Details");




let internet = false;
if (!internet)
  console.log("No Internet Connection");

  </script>
</body>
</html>
