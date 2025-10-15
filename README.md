### 🏟️ **PitchBook Organization README**
![PitchBook Logo](https://github.com/bluepeaktechnologies/bluepeaktechnologies/blob/main/assets/logo-white.PNG)

---


```markdown
# ⚽ PitchBook

> **Connecting footballers with pitches — seamlessly.**

PitchBook is a platform designed to simplify how footballers find and book pitches — and how pitch owners manage their venues.  
Our ecosystem includes two mobile apps powered by **React Native (Expo)** and a **Firebase backend**.

---

## 🧩 Project Overview

| App | Description |
| --- | --- |
| **PitchBook Players App** | For footballers to find, book, and manage their sessions. |
| **PitchBook Owners App** | For pitch/venue owners to manage bookings, schedules, and payments. |

Both apps are built with **React Native Expo Router**, connected through a shared **Firebase backend**.

---

## 🏗️ Tech Stack

**Frontend**
- React Native (Expo)
- Expo Router
- Zustand / React Query for state & data management
- TypeScript

**Backend**
- Firebase Authentication
- Firestore (Database)
- Firebase Storage
- Firebase Cloud Functions (for automation)
- Firebase Hosting / Cloud Messaging

**Dev Tools**
- ESLint + Prettier (Code quality)
- GitHub Actions (CI/CD)
- Expo EAS (build & deploy)

---

## 🔥 Core Collections (Firebase)

| Collection | Purpose |
| ----------- | -------- |
| `profiles` | Player and owner user profiles |
| `venues` | Venue details |
| `pitches` | Individual pitch details |
| `sessions` | Session bookings & availability |
| `bookings` | User-specific bookings |
| `transactions` | Payment and financial records |
| `blocked_slots` | Owner-specified unavailable times |

---

## 🧠 Architecture

```

````

---

## 🚀 Getting Started

### Prerequisites
- Node.js ≥ 18
- Yarn or npm
- Expo CLI (`npm i -g expo-cli`)
- Firebase project setup (see `/backend/firebase`)

### Setup
```bash
# Clone the repo
git clone https://github.com/PitchBookHQ/pitchbook.git
cd pitchbook

# Install dependencies
yarn install

# Run the player app
cd apps/player-app
expo start
````

---

## 🤝 Contributing

We welcome all contributions!
Here’s how you can help:

1. **Fork** the repository
2. Create a **feature branch**
3. **Commit** your changes clearly
4. Open a **Pull Request**

Please follow our [CONTRIBUTING.md](./CONTRIBUTING.md) and coding style guidelines.


## Connect with Us
- Website: [Coming Soon]
- Email: bluepeaktechnologiesltd@gmail.com

---

> "Innovation. Transformation. Excellence."  
> **BLUEPEAK TECHNOLOGIES LTD**

---

## License
This organization and its repositories may use different licenses depending on the project. Please refer to individual repositories for specific license information.

---

*"Bringing football communities together — one pitch at a time."* ⚽

*Proudly registered under the Companies and Allied Matters Act, 2020 (Nigeria).* 🇳🇬
