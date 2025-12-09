# Prueba_RA2

##Ejercicio1

### 1A. Pregunta
El texto del h1 no se centra visualmente porque su contenedor principal .site-header está usando display: flex con justify-content: space-between.

### 1B. Ejercicio - Soluciona de dos formas diferentes
He usado display: block; en .site-header para separar el h1 del menu y dividirlo en 2 columnas.

Mi CSS:
/* ===== CABECERA Y MENÚ SUPERIOR ===== */
.site-header {
  position: sticky;
  top: 0;
  z-index: 10;
  display: flex;
  align-items: center;
  display: block;
  background-color: #ff5152;
  color: #ffffff;
  padding: 15px 25px;
}

/*== Titulo del header ==*/
.site-header h1 {
  font-size: 3rem;
  margin-bottom: 30px;
}

### 1C. Ejercicio – Convertir la cabecera en dos filas

##Ejercicio2
