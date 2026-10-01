# Hub de soporte · lo compartido

Aquí guarda el Hub de soporte lo que el equipo comparte. No se edita a mano: lo escribe el propio hub.

- `hub/biblioteca.json`: las herramientas y las descargas marcadas como «compartir». Cada fila lleva en `de` quién la subió.
- `hub/catalogo.json`: el catálogo de fábrica que publica el superadministrador.

Todos los hubs leen estos ficheros sin token, al entrar y cada diez minutos. Para escribir hace falta un token fine-grained con permiso *Contents: read and write* solo sobre este repositorio.

Las versiones de la aplicación **no** están aquí, sino en [hub-soporte](https://github.com/FernandoPozaLastApp/hub-soporte).
