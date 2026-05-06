# Public APIs

Una lista colaborativa de APIs públicas y gratuitas, organizadas por categoría. Ideal para cuando estás buscando datos para un proyecto y no querés pagar ni registrarte en ningún lado.

---

## ¿De qué se trata?

Es básicamente una lista enorme (más de 1400 entradas) de APIs que cualquiera puede usar. Están ordenadas por categoría: clima, animales, chistes, música, noticias, etc. Para cada una se indica si necesitás una clave de API, si soporta HTTPS y si tiene CORS habilitado.

El proyecto lo mantiene la comunidad, así que si encontrás una API que no está, podés agregarla vos mismo.

---

## Objetivo del proyecto

Juntar en un solo lugar todas las APIs públicas que existen, para que no tengas que perder tiempo buscándolas por separado. La idea es que puedas entrar, buscar por categoría o palabra clave, y salir con la URL que necesitás en menos de un minuto.

---

## Cómo usarlo

### Buscar en GitHub

La forma más rápida es abrir el `README.md` del repositorio y usar `Ctrl+F` para buscar lo que necesitás.

```
Ctrl+F → "weather"
Ctrl+F → "music"
Ctrl+F → "sports"
```

### Clonar el repositorio

```bash
git clone https://github.com/public-apis/public-apis.git
cd public-apis

# Buscar desde la terminal
grep -i "joke" README.md
```

---

## Ejemplos

### Chiste aleatorio (JokeAPI)

```bash
curl "https://v2.jokeapi.dev/joke/Programming?type=single"
```

```json
{
  "joke": "Why do Java developers wear glasses? Because they don't C#.",
  "type": "single"
}
```

---

### Foto de gato aleatorio (The Cat API)

```bash
curl https://api.thecatapi.com/v1/images/search
```

```
[{"id":"smuGD4z2U","url":"https://cdn2.thecatapi.com/images/smuGD4z2U.jpg","width":960,"height":799}]

```

---

### Foto de perro aleatorio (Dog CEO API)

```
bash
curl "https://dog.ceo/api/breeds/image/random"

json
{
"message": "https://images.dog.ceo/breeds/labrador/n02099712_7954.jpg",
"status": "success"
}
```

---

## Estructura del repositorio

```
public-apis/
├── README.md           # La lista completa de APIs
├── CONTRIBUTING.md     # Cómo contribuir
├── LICENSE             # Licencia MIT
└── scripts/
    └── validate/       # Validación automática de nuevas entradas
```

---

## Cómo contribuir

1. Hacé un fork del repositorio
2. Creá una rama: `git checkout -b agregar-api-nueva`
3. Editá el `README.md` siguiendo el formato de la tabla
4. Abrí un Pull Request

---

## Licencia

MIT — podés usar, modificar y distribuir el contenido libremente siempre que mantengas el aviso de copyright original.
