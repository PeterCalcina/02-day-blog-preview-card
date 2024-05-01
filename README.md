# 02 Blog Preview Card - 100daysofprojects

Blog Preview Card es el segundo proyecto de 100 por haber, construido con HTML, CSS y JavaScript. Este proyecto es parte del desafío #100daysofprojects promovido por [Frontend Club](https://www.facebook.com/frontendclubfb).

![Screenshot](https://cdn.hashnode.com/res/hashnode/image/upload/v1713842391726/5b6cfd33-1c03-40c3-9e97-e105784b6f4c.png?w=1600&h=840&fit=crop&crop=entropy&auto=compress,format&format=webp)

### Tabla de contenidos

- [Descripcion](#descripcion)
  - [Capturas](#capturas)
  - [Enlaces](#enlaces)
- [Flujo de trabajo](#flujo-de-trabajo)
  - [Desarrollo](#desarrollo)
  - [Recursos](#recursos)
- [Agradecimientos](#agradecimientos)
- [Contacto](#contacto)

## Descripción

### Capturas

**-- Desktop --**

![Captura](https://github.com/PeterCalcina/01-day-profile-card/blob/master/images/capturas/desktop.png)

**-- Mobile --**

![Captura](https://github.com/PeterCalcina/01-day-profile-card/blob/master/images/capturas/mobile.png)

### Enlaces

Agrega los enlaces de la solución del proyecto y el repositorio.

- [Proyecto](https://02-blogpreview-card.netlify.app/)
- [Repositorio](https://github.com/PeterCalcina/01-day-profile-card.git)

## Flujo de trabajo

### Desarrollo

Primeramente se hizo la maquetación HTML con las clases necesarias para pasar a realizar el estilo respectivo con CSS, añadiendo pequeñas animaciones al cargar la página, hover en el título y el box-shadow.

**Estructura del proyecto**

```txt
/
📂
├── 📂css/
│ ├── normalize.css
│ └── style.css
├── 📂images/
└── index.html
└── README.md
```

**Tecnologías**

1. HTML Semántico
2. Estilos CSS
3. Animaciones CSS
4. Responsively App


**Fragmentos de codigo**

Etiquetas `meta` para el SEO.

```html
    <meta name="author" content="Peter Calcina">
    <meta name="description" content="Tarjeta de información">
    <title>Blog Preview Card - Frontend Club</title>
```

Animaciones CSS.

```css
/* Animación inicial del card */

.card {
	transition: box-shadow .45s ease, transform 0.3s ease-in-out;
	animation: rotate_card 1s;
}

.card:hover {
	transform: translate(-5px, -5px);
	box-shadow: 10px 10px 0 1px rgba(0, 0, 0, 1);
}


@keyframes rotate_card {
	0% {
		transform: rotateY(0)
	}

	100% {
		transform: rotateY(360deg)
	}
}
```

## Agradecimientos

- A mi madre que siempre fue el pilar fundamental para que sea la persona que soy, apoyandome en cada momento de mi vida.
- A mi padre (✞) que gracias a su arduo esfuerzo pude estudiar la carrera que me gusta y seguir formandome profesionalmente.
- A toda mi familia y amigos que siempre estan presente en mi vida.
- A la comunidad Frontend Club que siempre están apoyando con cualquier mínima cosa que surja y por esta gran iniciativa para acojer a los que queremos practicar nuestras habilidades en el desarrollo web día a día.

## Contacto

Agrega los medios de contacto para que cualquiera pueda encontrarte y hablar sobre tus siguientes grandes proyectos.

- [LinkedIn](https://www.linkedin.com/in/peter-c12)
- [Facebook](https://www.facebook.com/rodrigo.calcina.1)
- [GitHub](https://github.com/PeterCalcina)

---

> _La mejor manera de aprender a programar es practicando todos los días._ — **Frontend Club**
