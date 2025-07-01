# Übung 3 – Flexbox: Kästchen nebeneinander zentriert

```
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <title>CSS Übung 3 – Lösung</title>
  <style>
    .container {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 50px;
    }

    .box {
      width: 100px;
      height: 100px;
      background-color: tomato;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      font-weight: bold;
      border-radius: 8px;
    }

    .box:nth-child(2) {
      background-color: royalblue;
    }

    .box:nth-child(3) {
      background-color: seagreen;
    }
  </style>
</head>
<body>

  <div class="container">
    <div class="box">Box 1</div>
    <div class="box">Box 2</div>
    <div class="box">Box 3</div>
  </div>

</body>
</html>
```
