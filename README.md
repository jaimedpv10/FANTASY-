# Fantasy entre Amigos — MVP

App tipo Fantasy, pero con tus amigos como jugadores reales. 🎉

## 🚀 Stack técnico
- **Frontend móvil**: Flutter (iOS + Android)
- **Backend**: Supabase (Postgres + Auth + Realtime)
- **Storage**: Supabase Storage (fotos/actas)
- **Notificaciones**: FCM/APNs (via Supabase functions o OneSignal)

## 📂 Estructura del proyecto
fantasy_amigos/
├─ lib/
│  ├─ main.dart
│  ├─ src/
│  │  ├─ pages/
│  │  │  ├─ home_page.dart
│  │  │  ├─ league_page.dart
│  │  │  ├─ draft_page.dart
│  │  │  ├─ match_page.dart
│  │  │  └─ standings_page.dart
│  │  ├─ widgets/
│  │  ├─ services/
│  │  │  ├─ supabase_service.dart
│  │  │  └─ realtime_service.dart
│  │  └─ models/
│  └─ assets/
└─ pubspec.yaml

## ⚙️ Instalación
```
git clone https://github.com/tuusuario/fantasy_amigos.git
cd fantasy_amigos
flutter pub get
echo "SUPABASE_URL=tu_url" > .env
echo "SUPABASE_ANON_KEY=tu_key" >> .env
flutter run
```

## 🗄️ Base de datos (Supabase)
```
users (jugadores)
league (ligas)
team (equipos)
team_member
match (partidos)
match_event
scoring_rule
user_round_points
audit_log
```

## 🔑 Funcionalidades MVP
```
Crear liga + invitar amigos (código)
Crear equipos
Draft simple (turnos manuales al inicio)
Registrar partido + evidencias
Clasificación automática
```

## 📌 Roadmap corto
```
Autenticación (email + Google)
Crear/Unirse a ligas
Draft inicial
Registro y validación de partidos
Clasificación básica
Notificaciones push
```

## 👨‍💻 Contribuir
```
Haz fork del repo
Crea tu branch: git checkout -b feature/nueva-feature
Commit: git commit -m 'feat: añade nueva-feature'
Push: git push origin feature/nueva-feature
Crea un Pull Request
```

## 📜 Licencia
```
MIT License — libre para usar y modificar con atribución.
```

