# ENDES_T2_tarea

## Paso 1: Crear un perfil en GitHub
- Regístrate en [GitHub](https://github.com/).

## Paso 2: Configurar la clave SSH
- Sigue las para configurar tu clave SSH.
- `ssh-keygen -t rsa -C "your_email@example.com"`
(https://github.com/rubojkl/ENDES_T2_tarea/assets/125838940/3d955545-d08f-4db5-9880-b4c378202715)
- Copia la key
- clip < ~/.ssh/id_rsa.pub
(https://github.com/rubojkl/ENDES_T2_tarea/assets/125838940/8bdbc43b-657c-4aec-a130-68bd92b33606)
Pegala en github
(https://github.com/rubojkl/ENDES_T2_tarea/assets/125838940/7df7bd06-46c8-4c8a-9053-f84cb67fb49f)
(https://github.com/rubojkl/ENDES_T2_tarea/assets/125838940/02af5f7f-87d1-446e-912e-5d5e32f53ba6)

## Paso 3: Crear un repositorio público
- Crea un nuevo repositorio llamado "ENDES_T2_tarea" en GitHub.
(https://github.com/rubojkl/ENDES_T2_tarea/assets/125838940/a8064799-acb9-4bdc-aaf9-920c8a6507c1)

## Paso 4: Clonar el repositorio
- Abre Git Bash.
- Ejecuta: `git clone git@github.com:tu-usuario/ENDES_T2_tarea.git` (reemplaza `tu-usuario` con tu nombre de usuario).
(https://github.com/rubojkl/ENDES_T2_tarea/assets/125838940/058403fb-3a47-45a5-8f9b-5a98b2bd71b1)

## Paso 5: Mostrar contenidos de la carpeta
- En la carpeta del repositorio, ejecuta: `ls`.
(https://github.com/rubojkl/ENDES_T2_tarea/assets/125838940/041f21f3-f938-45da-b4a8-cc230ff3893a)

## Paso 6: Captura de git status (repositorio al día)
- Ejecuta: `git status`.
(https://github.com/rubojkl/ENDES_T2_tarea/assets/125838940/903d4ef2-08c2-41be-a68d-a9f0454cbfd1)

## Paso 7: Captura de git status (archivo nuevo)
- Crea un archivo.
- Ejecuta: `git status`.
(https://github.com/rubojkl/ENDES_T2_tarea/assets/125838940/3d4a7a11-e90d-4b60-aa6f-643298fec4f2)

## Paso 8: Captura de git status (archivos en staged)
- Agrega el archivo con: `git add nombre-del-archivo`.
- Ejecuta: `git status`.
(https://github.com/rubojkl/ENDES_T2_tarea/assets/125838940/01c4eaa5-24ac-4940-8fa5-1d34d652a365)

## Paso 9: Captura de git status (repositorio local no sincronizado)
- Realiza cambios.
- Ejecuta: `git status`.
(https://github.com/rubojkl/ENDES_T2_tarea/assets/125838940/30da2ba5-ce4c-4de6-aef7-930e3d4bceed)

## Paso 10: Sincronizar con GitHub
- Ejecuta:
  ```bash
  git add .
  git commit -m "Mensaje del commit"
  git push origin main
(https://github.com/rubojkl/ENDES_T2_tarea/assets/125838940/a3c33cdf-a22a-4bc0-a53a-8cec6f13f2f9)

