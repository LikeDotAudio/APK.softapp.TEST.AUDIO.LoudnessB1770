# 🔊 ITU-R BS.1770 Loudness Monitor (`TEST.AUDIO.LoudnessB1770`)

> **Category**: Test & Measurement · Audio Scopes
> **Launcher manifest**: [`display.json`](./display.json)
> **Standalone entrypoint**: [`index.html`](./index.html)

Broadcast loudness compliance meter implementing ITU-R BS.1770 / EBU R128 algorithms (Integrated, Short-term, Momentary LUFS).

---

## 🏛 Architecture & Philosophy

This application is decoupled from the monolithic SPOG test bench (`meter-input`) as an independent, modular Softapp conforming to the APK Softapps SDK. It operates both as:
1. An autonomous, embeddable micro-frontend iframe / component within SPOG.
2. A standalone web portal application with built-in signal simulation, WebRTC media capture, and MQTT databus telemetry.

**Remote repository**: `https://github.com/LikeDotAudio/APK.softapp.TEST.AUDIO.LoudnessB1770.git`

---

## 🧪 Smoke Tests

```bash
npm test
```

## 📚 Documentation
- Philosophy & Principles: [Documentation/🏛Philosophy/PRINCIPLES.md](Documentation/🏛Philosophy/PRINCIPLES.md)
- Architecture & Artifacts: [Documentation/🧩Manual and Artifacts/ARCHITECTURE.md](Documentation/🧩Manual%20and%20Artifacts/ARCHITECTURE.md)
- Delivery & Publishing: [Documentation/🌍Publishing/DELIVERY.md](Documentation/🌍Publishing/DELIVERY.md)
