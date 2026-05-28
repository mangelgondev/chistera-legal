# 🎩 Chistera — Juego de Papelitos

> El juego del papelito en tu móvil.
> Sin anuncios. Funciona offline. En español.

## 📱 Descarga

Disponible próximamente en Google Play Store.

## 🎮 Cómo se juega

Cada jugador escribe palabras en secreto y las mete
en la chistera. Por turnos, un jugador intenta que
su equipo adivine el máximo de palabras posible
en rondas con dificultad creciente:

| Ronda | Mecánica |
|-------|----------|
| 1 | 🗣️ Descripción libre |
| 2 | 💬 Una sola palabra |
| 3 | 🤐 Mímica |
| 4 | 🔊 Sonidos |
| 5 | 🎨 Dibujar |

## ✨ Características

- Sin anuncios, nunca
- Funciona 100% offline
- Sin registro ni cuenta
- De 2 a 12 jugadores en 2 a 4 equipos
- 5 modos de juego incluyendo dibujar
- Rondas configurables y reordenables
- Selección estratégica de describidor por ronda
- Temporizador configurable
- Gráfica de progresión por ronda
- Revancha con mismos equipos

## 🛠️ Stack técnico

| Tecnología | Uso |
|-----------|-----|
| Flutter 3.x | Framework principal |
| Riverpod 2.x | Gestión de estado |
| Hive | Persistencia local |
| go_router | Navegación |
| flutter_animate | Animaciones |
| fl_chart | Gráficas de progresión |
| Phosphor Icons | Iconografía |

## 🏗️ Arquitectura

Clean Architecture con estructura feature-first:
lib/
core/          → Tema, router, constantes
features/      → Pantallas organizadas por feature
domain/        → Modelos, GameManager, lógica de juego
services/      → Audio, haptic, almacenamiento
ui/            → Widgets reutilizables

## 🚀 Ejecutar el proyecto

```bash
flutter pub get
dart run build_runner build --delete-conflicting-outputs
flutter run
```

## 📄 Legal

- [Política de Privacidad](PRIVACY_POLICY.md)
- [Términos de Uso](TERMS_OF_USE.md)

---
*Desarrollado con Flutter 💙*
