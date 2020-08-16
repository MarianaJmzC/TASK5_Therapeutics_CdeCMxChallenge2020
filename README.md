# Borrador-web-proyCdeCMx
Este es mi primer intento personal de una página web para CdeMx Challenge

## Texto simple prueba A (Título 2)
Aquí van cosas de información

### Negritas prueba A (Título 3)
**Más información en negritas**

#### Cursivas prueba A (Título 4)
*Texto en cursiva intento uno*

### Negritas prueba B (Título 3)
__Más información en negritas__

#### Cursivas prueba B (Título 4)
_Texto en cursiva intento uno_

## LISTAS (Título 2)
* Elemento 1
* Elemento 2
* Elemento 3
4. Elemento 4
5. Elemento 5
6. Elemento 6

###### ENLACES (Título 6)
[GitHub]
(http://github.com)

## IMÁGENES (Título 2)
![GitHub Logo] (/images/logo.png)
- Formato: ![Alt Text] (url) "Pasando el cursor arriba de la imagen"

## CITAS
Nelson Mandela:
> Yo soy el amode mi destino,
> y el capitán de mi alma
- Las citas se representan en texto más claro

## Formato de Código
El 'archivo.md' es este.
'''javascript
function fancyAlert(arg) {
if(arg) {$.facebox({div:'#foo'})
}
'''

- Útil cuando queremos resaltar el nombre de algún archivo o que se muestre correctamente algún pedazo de texto que queramos poner.

## LISTA DE TAREAS
- [x] Escribir la primer tarea ya realizada (se rellena el cuadrito)
- [x] Escribir la tarea 2 (la x rellena el cuadrito, lo palomea)
- [ ] Escribir la tarea 3 sin realizar (no hay x, no se palomea; espacio en blanco com barra espaciadora entre corchetes)

## TABLAS
Primera columna | Segunda columna
----------------| ---------------
Dato 1A         | Dato 1B
Dato 2A         | Dato 2B

¡OJO! Se puede exportar markdown a pdf o html


# CÓDIGO MENÚ
# NO
<!doctype html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<title>CSS Menu responsivo</title>
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="style.css">
</head>

<body>
	<label for="show-menu" class="show-menu">Desplegar Menu</label>
	<input type="checkbox" id="show-menu" role="button">
		<ul id="menu">
		<li><a href="#">Inicio</a></li>
		<li>
			<ul class="hidden">
				<li><a href="#">1. Resumen</a></li>
				<li><a href="#">2. Introducción</a></li>
				<li><a href="#">3. Antecedentes</li>
				<li><a href="#">4. Análisis</li>
				<li><a href="#">5. Conclusiones</li>
			</ul>
		</li>
		<li><a href="#">6. Recomendaciones</a></li>
		<li><a href="#">7. Referencias</a></li>
		<li><a href="#">8. Anexos</a></li>
	</ul>
</body>
</html>

