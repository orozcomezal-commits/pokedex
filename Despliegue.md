### 1. Despliegue de Pokedex
**1.  Creamos un repositorio llamado "pokedex"** 

* Nos vamos al codigo fuente que nos dejo el profesor 
* Descargamos el pokedex angular archivo zip.
* Extraemos la carpeta de pokedex angular 
* Abrimos el terminal de la carpeta asignamos los siguientes comandos 
* git init
* git add.
* git commit -m "proyecto pokedex"
* git remote add origin hrrps://github.com/orozcomezal-commits/pokedex.git
* git push -u origin main
Esperamos que cargue, y listo ya tenemos nuestro repositorio correctamente .

<img width="1043" height="621" alt="Image" src="https://github.com/user-attachments/assets/75eac0dc-6cf5-4df6-9054-e05f47007823" />

---
### 2. Creacion de despliegue desde azure student

**2.  creamos un curso llamado static web app**

* Nos ubicamos en el primero **Aplicacion web estatica** Creamos.
* <img width="490" height="578" alt="Image" src="https://github.com/user-attachments/assets/1350e980-e3c7-448c-af7d-6bb0e25becc6" />

**3.Seleccionamos la suscripcion correspondiente **Azure for students,** creamos.**

<img width="931" height="351" alt="Image" src="https://github.com/user-attachments/assets/2f0a7ae2-672b-4f91-9e6f-cee1c122d187" />

**4.Asignamos un nombre en nuestro caso pokedex**
* Tipo de plan , seleccionamos gratis.
<img width="876" height="508" alt="Image" src="https://github.com/user-attachments/assets/bacb3f03-a795-4f86-8b8d-5972334e5f88" />

**5. Asignamos la ubicacion de salida nuestra y creamos.**
<img width="733" height="464" alt="Image" src="https://github.com/user-attachments/assets/a704ca7d-44d7-40cd-9c35-092ab6c9113f" />


**6. vemos nuestra infromacion , creamos .**

<img width="730" height="580" alt="Image" src="https://github.com/user-attachments/assets/76be57e0-67ea-499d-abcf-9ad73119442c" />

**7. Esperamos a que cargue hasta que nos muestre el chulo verde y listo ya tenemos nuestra static de pokedex lista!**

<img width="1362" height="434" alt="Image" src="https://github.com/user-attachments/assets/9d739b9b-02c8-439d-9c4a-5a10d3f7331c" />

**8. verificamos la informacion y nuestra **url** que vamos a navegar.**
 <img width="1345" height="469" alt="Image" src="https://github.com/user-attachments/assets/ca3225d6-971a-4b61-9351-fd7db46e8d01" />



### 3.Configuracion desde visual code 
**1. Nos ubicamos en la carpeta github/worflows**

* En pipelines y hacemos un 
* git pull
* Nos habilitara el azure-static-web app
<img width="891" height="664" alt="Image" src="https://github.com/user-attachments/assets/7fe711ed-2b49-4b5b-838e-c4ae1a553ae0" />

**2.  Luego en nos ubicamos en src**
* creamos una carpeta llamada **Staticwebapp.config,json** donde agregaremos nuestra seguridad para **pokedex**
 
* content-seguritu-policy
* Strict-trasport-segurity
* x-frame-options
* x-contect-type-options
* referrerpolicy
* permissions-policy
* Abrimos la terminal y introduciremos el siguiente comando 
* git add.
* git commit m- "seguridad x fullback"
* git push

<img width="983" height="634" alt="Image" src="https://github.com/user-attachments/assets/a3b85ddd-8eca-4d70-8804-7e9bd90caf1a" />




**3. esperamos que cargue en "action en nuestro github" Nos muestra el chulo y listo! Ya implementamos nuestra seguiridad en nuestro despliegue de pokedex**

<img width="1146" height="632" alt="Image" src="https://github.com/user-attachments/assets/127b4eee-00a7-4755-aa29-81c9bc4b132c" />

---
**4.  Abrimos nuestro URL y listo tenemos nuestro despliegue correctamente!**

<img width="1357" height="675" alt="Image" src="https://github.com/user-attachments/assets/fc5cff4c-326f-4195-9ad2-8fd156067c7a" />



---

### Verificacion de nuestro url en segurity Headers
* Resultados A+

<img width="1346" height="651" alt="Image" src="https://github.com/user-attachments/assets/d0da9425-4722-4d17-bfd6-ae4f33d301bf" />



































