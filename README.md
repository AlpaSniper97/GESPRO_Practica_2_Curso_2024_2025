# GESPRO Práctica 2 (Curso 2024-2025)

Repositorio para la asignatura de Gestión de Proyectos (3º de Grado en Ingeniería Informática) en el curso académico 2024/2025. Universidad de Burgos.

## Miembros del grupo
- **Jose Javier Velasco Whu**  
- **Mohamed Amin El Amrani El Khottouli**
  
---

## ABOUT GESPRO_Practica_2
El proyecto busca simular la planificación ágil de tareas de un proyecto software, incentivando a los estudiantes a trabajar en un entorno profesional relacionado con su formación. Se utilizarán herramientas como GitHub y ZenHub para organizar y gestionar tareas.

---

## 1. URL del Repositorio en GitHub
Repositorio donde se realizó la gestión y planificación de tareas:  
https://github.com/AlpaSniper97/GESPRO_Practica_2_Curso_2024_2025

Asegúrate de que el gestor de tareas está configurado como accesible para personas ajenas al equipo.  
![image](https://github.com/user-attachments/assets/f106aa91-0b07-4a38-a341-4c676805b35e)

---

## 2. Guía para interactuar con el proyecto

### 2.1 Configuración inicial del repositorio

1. **Crear una cuenta en GitHub**  
   Asegúrate de asociar tu cuenta al correo de la Universidad de Burgos.

2. **Realizar un fork del repositorio original**  
   Dirígete al repositorio del profesor:  
https://github.com/miguelbl-ubu/GESPRO_Practica_2_Curso_2024_2025
   Haz clic en el botón "Fork".  
![image](https://github.com/user-attachments/assets/dee812f6-cf5c-4e4d-bed2-8f70e74c9667)

3. **Habilitar issues en el repositorio**  
   - Ve a la pestaña `Settings` de tu repositorio.  
![image](https://github.com/user-attachments/assets/8a34edb6-9181-4f90-9f09-dfa4d15dcf8d)
   - Habilita la opción `Issues`.  
![image](https://github.com/user-attachments/assets/d22f4337-36b2-41e6-9591-1893ab7372cc)

4. **Instalar la extensión de ZenHub**  
   - Busca "ZenHub Chrome Extension" en Google.  
   - Descarga e instala la extensión desde la Chrome Web Store.  
![image](https://github.com/user-attachments/assets/a0c0c481-4a42-471d-b347-e1e507ec70ca)

5. **Configurar ZenHub**
   - Regístrate en ZenHub y vincula tu cuenta de GitHub. 
   - Vuelve a GitHub y actualiza la página.
   - Aparecera un nuevo apartado de ZenHub al entrar a el repositorio:
      - 1 Una vez hayamos entrado, nos pedirá unirnos a una organización.
      - 1.1 Para el miembro creador no le dejara unirse a una organizacion ya que la tendra que crear el mismo, nos tendremos que unir a el grupo del profesor ya que no nos dejara unirnos directamente para posteriormente abandonarlo y crae uno donde estaremos con nuestro compañero.
      - 1.2 Para el compañero solo tendras que unirte al gurpo creado por el lider.
   - Accede al apartado `ZenHub` dentro de tu repositorio.  
![image](https://github.com/user-attachments/assets/2d19e133-a39c-443c-8342-12e99f2c757a)
   - Para crear una organización debemos darle donde esta nuestro correo y dar a Create new workspace
![image](https://github.com/user-attachments/assets/464f72b5-4b82-4421-bd03-dd371a032af1)
   Donde asignamos un nombre, descripcion y las opciones.

---

### 2.2 Creación de etiquetas, hitos, Epic, User Stories y Task.

#### **Creación de etiquetas (Labels)**

1. Ve al apartado `Issues` de tu repositorio.  
2. Haz clic en el engranaje junto a `Labels` para crear una nueva etiqueta.  
3. Escribe el nombre de la etiqueta y presiona `Enter`.  
4. Opcional: Asigna un color desde el menú de edición de etiquetas.  
![image](https://github.com/user-attachments/assets/67c56b09-2e14-458c-9800-5b80868af15f)

#### **Creación de hitos (Milestones)**

1. Desde la pestaña `Issues`, selecciona `New Milestone`.  
  ![image](https://github.com/user-attachments/assets/2be8f990-a824-45f2-9c88-ce5f4911dc21)

2. Asigna un nombre, descripción y fecha de finalización al hito.  
3. Haz clic en `Create Milestone`.  
![image](https://github.com/user-attachments/assets/8cc483d5-abb3-4f67-bd23-b23f19c973d5)


#### **Creación de Epic**

1. Haz clic en el botón `+ Create` en ZenHub.
2. Selecciona `GitHub Issue`.  
![image](https://github.com/user-attachments/assets/af4265fb-ac48-42bb-8bac-15a378af6c66)
3. Rellena los campos:
   - **Título**: Nombre de la Epic. 
   - **Labels**: Asiga las etiquetas type Task.
![image](https://github.com/user-attachments/assets/6e2251a4-369b-4aef-a8cf-d5013d2cd54c)

#### **Creación de User Stories**

1. Haz clic en el botón `+ Create` en ZenHub.
2. Selecciona `GitHub Issue`.  
![image](https://github.com/user-attachments/assets/af4265fb-ac48-42bb-8bac-15a378af6c66)
3. Rellena los campos:
   - **Título**: Nombre de la User Storie. 
   - **Descripción**: Descripción de  lo que busce cada US.
   - **Labels**: Asigna las etiquetas type User Stories y el Epic que dependen.
![image](https://github.com/user-attachments/assets/cff66ac1-019b-410e-87bc-6b94b0e060f1)
   
#### **Creación de tareas (Tasks)**

1. Haz clic en el botón `+ Create` en ZenHub.  
![image](https://github.com/user-attachments/assets/af4265fb-ac48-42bb-8bac-15a378af6c66)
2. Selecciona `GitHub Issue`.  
3. Rellena los campos:  
   - **Título**: Nombre de la Task.  
   - **Descripción**: Related with Epic a la que pertenece.
   - **Labels**: Asigna las etiquetas type Task, Topic y US del que dependen.
   - **Milestone**: Vincula la tarea al hito correspondiente.  
   - **Estimate**: Asigna una complejidad (estimación).  
![image](https://github.com/user-attachments/assets/c7d9d144-4e83-4ee2-9e89-402fde3c3834)

---

### 2.3 Filtro por Epics, US y Tasks en la columna de New Issues

-Para filtrar por etiquetas desde GitHub debemos poner en el filtrador, label: seguido de la etiqueta que queramos filtrar.

#### Type: Epic
**[INCLUIR IMAGEN AQUÍ]**

#### Type: User Stories
**[INCLUIR IMAGEN AQUÍ]**

#### Type: Task
**[INCLUIR IMAGEN AQUÍ]**

---

### 2.4 Organización del Sprint Backlog

1. Mueve las tareas del `Product Backlog` al `Sprint Backlog`.
   Movemos todas las tareas del release 1 a Product Backlog primeramente
   ![image](https://github.com/user-attachments/assets/571ec65e-ec25-4f8a-bf23-96a28ed2fa90)

   Posteriormente volvemos a mover estas tareas desde Product Backlog al Sprint Backlog
   ![image](https://github.com/user-attachments/assets/359ebd4a-ab76-4b97-9bc1-7fbdbe420aa8)


2. Distribuye las tareas en diferentes columnas según su estado:  
   - **In Progress**: Tareas en progreso.  
   - **Review**: Tareas en revisión.  
   - **Done**: Tareas completadas.  
![image](https://github.com/user-attachments/assets/6f953270-f6b2-4b97-a79a-57406b0ff685)


---

### 2.5 Cierre del 1er Release

1. Mueve todas las tareas de la `Release 1` a la columna `Closed`.  
2. Esto indicará que las tareas han sido completadas con éxito.  
![image](https://github.com/user-attachments/assets/93bf2330-29c0-49b3-9fc7-412fc58d2d8b)


---

### 2.6 Comienzo del 2º Release

1. Comienza el trabajo en nuevas tareas para la segunda release. Movemos las tareas a Sprint Backlog
   ![image](https://github.com/user-attachments/assets/f7093db8-9ad9-4b2d-a1df-eb795963eef8)


3. Filtra las tareas por etiquetas o temas según sea necesario.  
   - Por ejemplo, `Topic: Setup`.  
![image](https://github.com/user-attachments/assets/3f4648b0-d962-4c48-a3a3-b80b78802d17)


---

### 2.7 Ejemplo de conversación en tareas

#### Tarea: **Manage the app from an Android device**  
**[INCLUIR IMAGEN DE LA CONVERSACIÓN AQUÍ]**

#### Tarea: **Manage accounts**  
**[INCLUIR IMAGEN DE LA CONVERSACIÓN AQUÍ]**

--- 

Con esta estructura, podrás seguir fácilmente cada paso de la práctica y organizar tu repositorio y tareas en GitHub y ZenHub.
