# Laravel 10 & Vue 3 Startkit

Este es un startkit para desarrollar aplicaciones web modernas utilizando [Laravel 10](https://laravel.com/), [Vue 3](https://v3.vuejs.org/), y [Bootstrap](https://getbootstrap.com/). Está diseñado para proporcionar una base robusta que te permita comenzar rápidamente el desarrollo de aplicaciones con una arquitectura escalable y componentes reutilizables.

## Características

- **Laravel 10**: Framework PHP potente y flexible para el backend, con herramientas para autenticación, enrutamiento, migraciones y más.
- **Vue 3**: Framework de JavaScript progresivo para la construcción de interfaces de usuario reactivas y componentes modulares.
- **Bootstrap**: Framework CSS que facilita la creación de diseños responsivos y modernos.

## Instalación

Para comenzar, clona este repositorio y navega al directorio del proyecto:

```
git clone https://github.com/kuanticacl/startkit-laravel10-vue3-bootstrap
cd startkit-laravel10-vue3-bootstrap
```

Instala las dependencias de Composer y NPM:

```
composer install
npm install
```

Configura el archivo de entorno `.env`:

```
cp .env.example .env
php artisan key:generate
```

## Uso

Inicia el servidor de desarrollo para Laravel y compila los assets de Vue 3 y Bootstrap:

```
php artisan serve
npm run dev
```

Esto iniciará la aplicación en `http://localhost:8000`. Ahora puedes empezar a personalizar los componentes y el diseño según tus necesidades.

## Componentes Incluidos

- **Autenticación**: Sistema de login y registro básico implementado con Laravel Breeze y Vue 3.
- **Componentes Reutilizables**: Varios componentes de Vue 3 listos para usar, como modales, formularios dinámicos, y más.
- **Diseño Responsivo**: Estilos preconfigurados con Bootstrap para garantizar una experiencia óptima en cualquier dispositivo.

## Personalización

Cada componente y vista está diseñado para ser fácilmente personalizable. Puedes modificar los estilos, vistas, y lógica según tus necesidades específicas.

## Contribuciones

Este proyecto es **opensource** y las contribuciones son bienvenidas. Si tienes ideas, mejoras o encuentras algún problema, no dudes en abrir un issue o enviar un pull request.

## Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE).

## Agradecimientos

Gracias por utilizar este startkit. Esperamos que te ayude a comenzar rápidamente con tu desarrollo web y facilite tu flujo de trabajo.

**Desarrollado con ❤️ por Equipo Kuantica.cl**
