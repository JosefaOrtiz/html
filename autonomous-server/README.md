# Autonomous HTML Server

Servidor HTTP real con frontend HTML separado del runtime Node.

## Ejecutar

```bash
cd autonomous-server
npm start
```

Abrir `http://127.0.0.1:8787`.

## Componentes

- `Server_REAL.html`: cliente web y panel de estado.
- `server.js`: servidor HTTP, API REST, almacenamiento persistente, cola, snapshots, recuperación de trabajos y apagado controlado.
- `package.json`: comando de arranque sin dependencias externas.

Los datos persistentes se guardan en `~/.autonomous-html-server/`.
