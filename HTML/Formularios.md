# Formularios


## <a href=https://www.w3schools.com/html/html_forms.asp>Form</a>
```html
<form action="/destino/" name="registro" method="get" autocomplete="off">
```
- *action* = destino del formulario
- *name* = nombre del formulario
- *method* = get/post 
	El método GET concatena los campos del formulario en la URL, se utiliza para formularios de consulta. No crea ni modifica registros.
	El método POST, envía mas información, documentos adjuntos y puede modificar registros.
		CRUD -> Create, Read, Update,Delete
- *autocomplete* = off 
## <a href=https://www.w3schools.com/tags/tag_input.asp>input</a>
```html
<input type="text" name="nombre">
```
#### Atributos de input
input tiene muchos atributos entre ellos los mas importantes: 
- type = "the type of data this input fiel covers"
- name = "El nombre del campo que estamos rellenando"
- value = "Especifica el valor por defecto o rellenados antes"
- reset = "Crea un botón que borra el formulario"
- hidden = "Esconde un field del usuario"
- file = "Solo con POST"
- <a href="https://www.w3schools.com/tags/att_form_enctype.asp" style="color:green">enctype = multipart/form-data</a> = "Hay que ponerlo cuando tengamos ficheros"
![[Pasted image 20240920202717.png]]
![[Pasted image 20240920202815.png]]