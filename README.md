# Gestor de Usuarios

Aplicación Android hecha con Flutter para administrar clientes y contactos.
Proyecto educativo de código abierto.

## Funciones

- Cuenta local (correo y contraseña) guardada solo en el dispositivo (SQLite).
- Alta, edición y baja de clientes (nombre, teléfono y correo).
- Clasificaciones propias que se asignan a cada cliente.
- Consulta de los contactos del teléfono y apertura de un chat de WhatsApp.
- Escáner de códigos QR (ZXing) que abre enlaces http/https.

La app no usa servicios de Google, Firebase, anuncios ni rastreadores, y no
necesita conexión a internet.

## Compilar

```
flutter pub get
flutter run
```

## Licencia

Consulta el archivo `LICENSE`.
