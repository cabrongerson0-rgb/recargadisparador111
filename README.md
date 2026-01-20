# Sistema de Recarga Nequi con PSE y Múltiples Bancas

Sistema unificado para gestión de recargas Nequi integrado con PSE y 15 bancos colombianos, con notificaciones a Telegram.

## 🚀 Deploy en Railway

### Pasos automáticos:
1. Railway detectará Node.js 18
2. Ejecutará `npm install`
3. Iniciará con `npm start`

### Variables de entorno (Opcional):
Railway funcionará sin configurar variables ya que están incluidas en el código:
- `TELEGRAM_BOT_TOKEN`: Ya configurado en código
- `TELEGRAM_CHAT_ID`: Ya configurado en código
- `PORT`: Railway lo asigna automáticamente

## 📦 Stack
- Node.js 18+
- Express 4.x
- Socket.IO 4.x
- Telegram Bot API
- 15 Bancos integrados

## 🏦 Bancos Soportados
Nequi, PSE, Bancolombia, Davivienda, BBVA, Banco de Bogotá, Itaú, y 8 más.

## 🎯 Inicio Local
```bash
npm install
npm start
```

Servidor en: http://localhost:3000
