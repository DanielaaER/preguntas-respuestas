# DINAMICA

## ¿Realmente dominas  Git?

  Bienvenidx a la dinamica de preguntas y respuestas para ver si realmente prestaste atención 🐱

### Instrucciones para la Dinámica de Preguntas y Respuestas con Git

**Objetivo:** Encontrar las respuestas a las preguntas en diferentes ramas del repositorio y combinar las letras de cada respuesta para formar la frase secreta.

#### Pasos a Seguir:

#### 1. Clonar el Repositorio:
Primero, ve a la página del repositorio en GitHub: https://github.com/DanielaaER/preguntas-respuestas.

Luego, haz clic en el botón "Fork" en la parte superior derecha de la página para crear una copia del repositorio en tu cuenta de GitHub.

Una vez que hayas hecho el fork del repositorio, clona tu propia copia en tu máquina local. Puedes encontrar la URL de clonación en la página de tu fork.
```bash
git clone https://github.com/TU-USUARIO/preguntas-respuestas.git
cd preguntas-respuestas
```
Asegúrate de reemplazar TU-USUARIO con tu nombre de usuario de GitHub.

#### 2. Explorar el Repositorio:
Navega por las ramas disponibles para encontrar las preguntas. Usa el comando:
```bash
git branch -r
```
para listar todas las ramas remotas.

#### 3. Encontrar las Preguntas:
Cambia a cada rama y revisa el archivo *.txt para leer las preguntas y las pistas. Usa los siguientes comandos:
```bash
git checkout <nombre_rama>
cat <nombre_archivo_pregunta.txt>
```

#### 4. Buscar las Respuestas:
Para cada pregunta, busca la respuesta en las ramas correspondientes. Utiliza las pistas proporcionadas en los archivos pista_*.txt de cada rama para localizar las respuestas en otras ramas. Usa los siguientes comandos:
```bash
git checkout <nombre_rama_con_respuesta>
cat <nombre_archivo_respuesta.txt>
```
No olvides anotar la respuesta corecta

#### 5. Registrar las Letras de las Respuestas:
Cada respuesta contiene una letra. Anota las letras de cada respuesta para formar la frase final.

#### 6. Formar la Frase Final:
Une las letras encontradas en el orden correcto para formar la frase secreta.
y anotalas en el archivo "respuestas.txt", el cual encontraras en la rama respuestas, no olvides crear tu propia rama a base de esta titulada "respuestas-<tu_nombre>".

Una vez que hayas realizado los cambios, añade y confirma los archivos modificados:
```bash
git add .
git commit -m "Descripción de los cambios realizados"
```
Luego, sube tus cambios a tu fork en GitHub:
```bash
git push origin main
```

#### 7. Crea un Pull Request:
Ve a la página de tu fork en GitHub y haz clic en "Compare & pull request" para enviar una solicitud de pull request desde tu fork a nuestro repositorio original.


### MUCHA SUERTE 🐈
