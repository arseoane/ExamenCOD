> Antón Rodríguez Seoane
> Ayer me comí una empanada
# Examen 1ª Evaluación (2ª Parte) - Control de Versiones

---

## Instrucciones
- Los commits de cada apartado deben tener el mensaje *"Apartado X - descripción del cambio realizado"*
- Entrega en la tarea de Moodle tu repositorio
- Solo se corrigen los commits que estén en el repositorio remoto

### Apartado 1

- Clona este repositorio.
- Modifica este Readme, poniendo tu nombre completo, realiza un `commit` con el mensaje *"Apartado 1"* y un `push`.

Ponemos mi nombre completo:

![img.png](img.png)
- 
Pregunta 
- ¿Qué paso es fundamental cuando clonamos un repositorio ajeno para que podamos subir nuestros propios commits? Explícalo y utiliza capturas de pantalla.

Es fundamental crear un fork.

![img_1.png](img_1.png)

### Apartado 2

- Realiza una modificación en el código en la web de tu repositorio en GitHub
- Utiliza fetch para descargar los cambios realizados en tu repositorio.

Hacemos la modificación desde la web:

<img width="1920" height="912" alt="image" src="https://github.com/user-attachments/assets/d8940584-efea-4ecd-8f36-cede775946fb" />

Usamos git fetch para traer los cambios hechos en la web:

![img_2.png](img_2.png)

Pregunta
- Explica los pasos para que el código modificado en GitHub, llegue a tu rama principal local. Explícalo con capturas de pantalla.

Se ejecutan estos comandos:

![img_3.png](img_3.png)

Luego para comprobar, se usa:

![img_4.png](img_4.png)

### Apartado 3

- Realiza otro cambio desde la web de tu repositorio en GitHub.
- Utiliza pull para descargar los cambios realizados en tu repositorio.

Hacemos el cambio:

![img_5.png](img_5.png)

Usamos el pull:

![img_6.png](img_6.png)


Pregunta
- Explica los pasos dados para que el cambio realizado en GitHub, llegue a tu rama principal local. Explícalo con capturas de pantalla.

Ejecutamos estos tres comandos:

![img_7.png](img_7.png)

Verificamos que todo esté bien:

![img_8.png](img_8.png)