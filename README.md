<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font: 150% sans-serif;
      background: red;
      margin-left: 80px;
      margin-top: 80px;
      margin-right: 80px;
      margin-bottom: 80px;
    }

    .raster div {
      /* background: #white;
      border: 1px #2C3E50 solid;
      */
    }

    .raster {
      display: grid;
      grid-template-columns: 1fr 1fr 1fr 1fr;
      grid-template-rows: 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
      grid-gap: 20px;
    }

    .a {
      grid-column-start: 3;
      grid-column-end: 5;
      grid-row-start: 1;
      grid-row-end: 2;
      font-size: 100%;
    }

    .h {
      grid-column-start: 1;
      grid-column-end: 5;
      grid-row-start: 3;
      grid-row-end: 4;
      font-size: 450%;
      font-weight: bold;
    }

    .i {
      grid-column-start: 1;
      grid-column-end: 3;
      grid-row-start: 4;
      grid-row-end: 5;
      font-size: 100%;
    }

    .j{
      grid-column-start: 3;
      grid-column-end: 5;
      grid-row-start: 4;
      grid-row-end: 5;
      font-size: 100%;
    }

    .k{
      grid-column-start: 1;
      grid-column-end: 5;
      grid-row-start: 5;
      grid-row-end: 6;
      font-size: 450%;
      font-weight: bold;
    }

.l{
  grid-column-start: 1;
  grid-column-end: 3;
  grid-row-start: 6;
  grid-row-end: 7;
  font-size: 100%;
}

.m{
  grid-column-start: 3;
  grid-column-end: 5;
  grid-row-start: 6;
  grid-row-end: 7;
  font-size: 100%;
}

.t{
  vertical-align: bottom;
  grid-column-start: 3;
  grid-column-end: 5;
  grid-row-start: 8;
  grid-row-end: 9;
  font-size: 100%;
  margin-top: 80px;
}
  </style>



  <title>Gridlayout</title>
</head>
<body>
<div class="raster">
  <div class="a">Josef Müller-Brockmann</div>
  <div class="h">Grid systems</div>
  <div class="i">in graphic design</div>
  <div class="j">A visual communication manual<br> for graphic designers,<br>typographers and<br>three dimensional designers</div>
  <div class="k">Raster systeme</div>
  <div class="l">für die <br> visuelle Gestaltung</div>
  <div class="m">Ein Handbuch für <br> Grafiker, Typografen und<br>Ausstellungsgestalter</div>
  <div class="t">Niggli</div>


</div>
</body>
</html>
