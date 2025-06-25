# clase03-2bim

![Captura desde 2025-06-18 08-10-35](https://github.com/user-attachments/assets/85b4d2c6-ce31-40dd-b9ee-cf49d038bcb0)

Esta es la forma natural de mostrar el numero de telefono en el caso de no haber puesto en la clase NumeroTelefonico de models.py el related_name. En este caso se pone el nombre de
la clase en minusculas seguido de guion bajo mas la palabra set.

### 25 junio 2025

crear_numero_telefonico_estudiante la diferencia con el crear_numero_telefonico es que primero el campo estudiante no esta visible en la pagina, por que
en el formulario mediante un def le decimos self.initial['estudiante'] = estudiante, asignamos el campo para mantener la integridad de los datos por que un 
numero de telefono obligatoriamente debe estar asignado a un estudiante, y luego con self.fields["estudiante"].widget = forms.widgets.HiddenInput(), lo que hacemos 
es ocultar este campo estudiante en la pagina pero esta ahi.
