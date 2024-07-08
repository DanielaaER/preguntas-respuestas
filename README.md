# DINAMICA

## ¿Realmente dominas  Git?

  Bienvenidx a la dinamica de preguntas y respuestas para ver si realmente prestaste atención 🐱

### Instrucciones para la Dinámica de Preguntas y Respuestas con Git

**Objetivo:** Encontrar las respuestas a las preguntas en diferentes ramas del repositorio y combinar las letras de cada respuesta para formar la frase secreta.

#### Pasos a Seguir:

#### 1. Clonar el Repositorio:
Primero, clona el repositorio en tu máquina local.
```bash
git clone https://github.com/DanielaaER/preguntas-respuestas.git
cd preguntas-respuestas
```

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
y anotalas en el archivo "respuestas.txt", el cual encontraras en la rama respuestas, no olvides crear tu propia rama a base de esta titulada "respuestas-<tu_nombre>" y haz un push al repositorio


