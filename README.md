# contenedores
filas y columnas

actividad1 crear 4 columnas en bootstrap. Aplicsr diferente colores
actividad2 crear dos columnas y dos filas.Usar diferente colores para cada una de de ellas
actividad3 crear 3 filas, la primera conendra dos columnas, la segunda 3 yla tercera 2

1:
<div class="container mt-4">
  <div class="row text-white text-center">
    <div class="col-md-3 bg-primary p-3">Columna 1</div>
    <div class="col-md-3 bg-success p-3">Columna 2</div>
    <div class="col-md-3 bg-danger p-3">Columna 3</div>
    <div class="col-md-3 bg-warning text-dark p-3">Columna 4</div>
  </div>
</div>

2:
<div class="container mt-4">
  <div class="row text-white text-center mb-2">
    <div class="col-6 bg-info p-4">F1 - Columna A</div>
    <div class="col-6 bg-secondary p-4">F1 - Columna B</div>
  </div>
  
  <div class="row text-white text-center">
    <div class="col-6 bg-dark p-4">F2 - Columna A</div>
    <div class="col-6 bg-primary p-4">F2 - Columna B</div>
  </div>
</div>

3:
<div class="container mt-4">
  <div class="row mb-2">
    <div class="col-6 bg-light border p-3">Fila 1 - Col 1</div>
    <div class="col-6 bg-light border p-3">Fila 1 - Col 2</div>
  </div>

  <div class="row mb-2">
    <div class="col-4 bg-secondary text-white border p-3">Fila 2 - Col 1</div>
    <div class="col-4 bg-secondary text-white border p-3">Fila 2 - Col 2</div>
    <div class="col-4 bg-secondary text-white border p-3">Fila 2 - Col 3</div>
  </div>

  <div class="row">
    <div class="col-6 bg-info text-white border p-3">Fila 3 - Col 1</div>
    <div class="col-6 bg-info text-white border p-3">Fila 3 - Col 2</div>
  </div>
</div>
