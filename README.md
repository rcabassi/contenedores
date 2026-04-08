# contenedores
contenedores: filas y columnas


ACTIVIDAD


1. CREAR 4 COLUMNAS EN BOOSTRAPT. APLICAR DIFERENTES COLORES.


2.CREAR 2 COLUMNAS Y 2 FILAS. USAR DIFERENTES COLORES PARA CADA UNA DE ELLAS.


3.CREAR 3 FILAS LA PRIMERA CONTEDRA 2 COLUMNAS LA SEGUNDA 3 Y LA TERCERA 2.


RESPUESTAS

1. <div class="container mt-4">
  <div class="row text-white text-center">
    <div class="col-3 bg-primary p-3">Columna 1</div>
    <div class="col-3 bg-success p-3">Columna 2</div>
    <div class="col-3 bg-danger p-3">Columna 3</div>
    <div class="col-3 bg-warning text-dark p-3">Columna 4</div>
  </div>
</div>


2.<div class="container mt-4 text-white text-center">
  <div class="row mb-2">
    <div class="col-6 bg-info p-4">Fila 1 - Col 1</div>
    <div class="col-6 bg-secondary p-4">Fila 1 - Col 2</div>
  </div>
  <div class="row">
    <div class="col-6 bg-dark p-4">Fila 2 - Col 1</div>
    <div class="col-6 bg-danger p-4">Fila 2 - Col 2</div>
  </div>
</div>


3.<div class="container mt-4 text-white text-center">
  <div class="row mb-2">
    <div class="col-6 bg-primary p-3">F1 - Col 1</div>
    <div class="col-6 bg-primary border-start p-3">F1 - Col 2</div>
  </div>

  <div class="row mb-2">
    <div class="col-4 bg-success p-3">F2 - Col 1</div>
    <div class="col-4 bg-success border-start p-3">F2 - Col 2</div>
    <div class="col-4 bg-success border-start p-3">F2 - Col 3</div>
  </div>

  <div class="row">
    <div class="col-6 bg-info p-3">F3 - Col 1</div>
    <div class="col-6 bg-info border-start p-3">F3 - Col 2</div>
  </div>
</div>
