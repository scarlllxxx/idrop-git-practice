# API Plan — IDrop

## Планируемые эндпоинты

### Auth
- POST /api/auth/steam — вход через Steam

### Skins
- GET /api/skins — список скинов
- GET /api/skins/{id} — информация о скине



cat > api-plan.md << 'EOF'
# API Plan — IDrop

## Планируемые эндпоинты

### Auth
- POST /api/auth/steam — вход через Steam

### Skins
- GET /api/skins — список скинов
- GET /api/skins/{id} — информация о скине

### Inventory
- GET /api/inventory — инвентарь пользователя
- POST /api/inventory/sell — выставить предмет на продажу

### Battles
- POST /api/battles/create — создать кейс-баттл
- POST /api/battles/{id}/join — присоединиться

### WebSocket (план)
- ws://api.idrop/battles/{id} — live-обновления баттла
