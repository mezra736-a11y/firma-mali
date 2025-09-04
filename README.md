.firma-container {
  width: 350px;
  height: 200px;
  position: relative;
  overflow: hidden;
  border: 3px solid #ffffff; /* Color del borde, modificable */
  box-sizing: border-box;
  background-color: #000; /* Fondo por si la imagen no carga */
}

/* Imagen base */
.firma-imagen img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: all 0.4s ease;
}

/* Filtro al pasar el mouse */
.firma-container:hover img {
  filter: brightness(0.7) saturate(1.2); /* Ajusta para cambiar el efecto */
}

/* Texto superpuesto */
.firma-texto {
  position: absolute;
  right: 15px;
  bottom: 15px;
  color: #fff;
  font-family: Arial, sans-serif;
  font-size: 14px;
  text-align: right;
  line-height: 1.2;
  text-transform: uppercase;
  background: rgba(0, 0, 0, 0.4); /* Fondo sutil para que se lea mejor */
  padding: 4px 6px;
  border-radius: 4px;
}
