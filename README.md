# NH's Watch App 🕒

**My first native Win32 desktop application written in C++**  
A complete desktop assistant featuring: Clock, Timer, Stopwatch, Alarm, Calendar, Weather, and more.

---

## 🚀 Features

- 🕒 **Clock** — Displays current time and date (with optional seconds).
- ⏱️ **Timer** — Countdown timer with Start/Pause/Reset controls and sound alert.
- ⏲️ **Stopwatch** — Precision timing with Lap tracking support.
- 🛎️ **Alarm** — Add/Delete alarms with repeat by day of the week support.
- 📅 **Calendar** — Simple month navigation.
- 🌤️ **Weather** — Automatic weather updates using the free wttr.in API (no key required).
- 💬 **Daily Quote** — Inspirational quotes via the zenquotes.io API.
- 💱 **Currency** — Live exchange rates (e.g., USD → RUB) via exchangerate-api.com.
- ⌨️ **Hotkeys** — Quick tab switching:
  - `Win + Shift + C` → Clock
  - `Win + Shift + T` → Timer
  - `Win + Shift + S` → Stopwatch
- 🗂️ **System Tray & Toasts** — Minimize to system tray with popup notifications.
- 🎨 **Settings** — Switch between Dark/Light themes, toggle seconds, and "Always on Top" mode.

---

## 🛠️ Technical Stack

- **Language:** C++ (Win32 API, no MFC/ATL)
- **Compiler:** MinGW (MSYS2), static linking for portability
- **Installer:** Inno Setup (with custom icon and EULA)
- **APIs:** wttr.in, zenquotes.io, exchangerate-api.com
