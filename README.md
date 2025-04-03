# Loading-Screen
Pantalla de carga creada para la pagina https://kreative.alphadocere.cl/


# Como agregar a proyecto:

!.-Deben poner loading-component.js en su proyecto

2.-Agregar el script en cualquier seccion de su proyecto donde vaya a ser utilizado, Ejemplo:
   Si se agrega en index.html, en su header debe incluir: <script src="ruta/loading-component.js" defer></script>

3.-Cuando se recargue la pagina se va hacer la llamada al script

# Informacion adicional

- En (loading-component.js:2) Se puede cambiar el minimo de tiempo que se visualiza el componente, por defecto los establecí en 2000ms (2 Segundos) pero se puede cambiar este parametro al valor que sea necesario
- El logo que se visualiza en el centro de la pantalla de carga se puede editar desde la carpeta de Assets, conserva el nombre del archivo para evitar problemas de enrutamiento, idealmente no debe tener un fondo visible.
- En (loading-component.js:27) Se definen los estilos de la pantalla de carga, los cambios visibles mas importantes serian:
      -Color de Fondo del loading screen En (loading-component.js:47)
      -Color del contenedor circular del logo En (loading-component.js:64)
- 
