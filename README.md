# Meds.

A privacy-first medication tracking app for iOS. Your data never leaves your device.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 🔒 Privacy First

| Principle             | Implementation                                    |
| --------------------- | ------------------------------------------------- |
| **Local Storage**     | SQLite database stored on-device only             |
| **No Network**        | Zero API calls, no cloud sync                     |
| **No Tracking**       | No analytics, no telemetry                        |
| **Complete Deletion** | Deleting a medication removes ALL associated data |

📖 **[Read our full privacy documentation →](https://www.ahto.com/blog/meds-privacy)**

## 📱 Features

- Track daily medications with flexible schedules
- Visual history with calendar view
- Progress rings show daily completion
- Haptic feedback for interactions
- Dark mode optimized UI

## 🛠️ Development

```bash
cd mobile
npm install
npx expo start
```

## 🧪 Testing

```bash
cd mobile
npm test
```

See [`mobile/README.md`](mobile/README.md) for detailed architecture and technical documentation.

## 📄 License

MIT License - see [LICENSE](LICENSE) for details.
