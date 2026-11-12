# Sistema de inventario SENA

Prototipo web académico para la gestión de inventario, desarrollado como parte del contexto formativo de ADSO mixto del SENA.

## Estado del proyecto

La pantalla de inicio de sesión es la vista actualmente desarrollada. El formulario realiza validaciones básicas del navegador, pero no autentica usuarios ni se conecta a un servidor. Las demás vistas están reservadas para futuras funcionalidades.

## Estructura

| Ruta | Descripción |
| --- | --- |
| `CSS/index.html` | Pantalla de inicio de sesión |
| `CSS/Estilos.css` | Hoja de estilos del proyecto |
| `CSS/dashboard.html` | Espacio previsto para el panel principal |
| `CSS/categorias.html` | Espacio previsto para la gestión de categorías |
| `CSS/registros.html` | Espacio previsto para registros |
| `CSS/usuarios.html` | Espacio previsto para la gestión de usuarios |

## Tecnologías

- HTML5
- CSS3

## Cómo abrirlo

Clona el repositorio y abre `CSS/index.html` en un navegador. No se requiere un proceso de compilación.

```bash
git clone https://github.com/Fabian693-dev/inventario.html.git
```

## Próximos pasos

- Completar las vistas de dashboard, categorías, registros y usuarios.
- Conectar el formulario a un sistema de autenticación seguro.
- Integrar almacenamiento persistente para los datos del inventario.