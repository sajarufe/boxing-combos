Implement a simple static webpage that generates random boxing combinations. It should contain a simple form to select the combo length (minimum value 2). The combinations should include the standard punches (1 to 6) and the following defensive moves: slip right (SR), slip left (SL), roll right (RR), roll left (RL), lean (L). The combinations should alternate left and right moves, except for the jab which may be repeated but only once.
The interface should be slick and evoke a boxing feel. Use Tailwind CSS for styling. Do it by filling in this HTML file that already includes a custom script that handles the Tailwind CSS bundle dynamically.

index.html
```
<!doctype html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {}
  </script>
  
</head>
<body>

</body>
</html>
```
