## 📝 Product Requirements Document (PRD)

### **Product Name (suggestion):**

**LingoLink** – “Grow your app with native language support.”

---

### **Overview**

LingoLink is a web application designed to streamline the translation of iOS apps. App developers can upload their `.strings` or `.xliff` files, manage languages, and invite native speakers or professional translators to contribute. The platform uses AI to auto-suggest translations and ensures high-quality UX for both developers and translators.

---

### **Target Audience**

- Indie iOS Developers
- iOS App Development Agencies
- Localization teams
- Open-source iOS app maintainers

---

### **Core Features**

#### 🔧 Developer Features

- Upload iOS localization files (`.strings`, `.xliff`)
- Auto-detect and preview localization keys
- AI-powered pre-translation (OpenAI or Google Translate)
- Team & collaborator invites (via email or invite link)
- Role-based access (admin, translator, reviewer)
- Real-time comments on strings
- Export localized files in iOS-compatible format

#### 🌍 Translator Features

- Friendly, simple translation UI
- Language-specific views
- Context-aware suggestions
- AI-assisted suggestions with editable output
- Flag items needing developer context

#### 📊 Dashboard

- Overview of translation status by language
- Activity log
- Reviewer notes and feedback

#### 🔐 Authentication

- Clerk integration for secure auth
- OAuth + magic links
- Role management (via Clerk teams)

#### ⚙️ Tech Stack

- **Frontend**: Next.js 14 App Router, ShadCN UI, TailwindCSS
- **Auth**: Clerk
- **Database**: PostgreSQL (via Drizzle ORM)
- **Server-side**: Server Actions
- **AI**: GPT for translation suggestions

---

## 🎨 Color Palette

| Color Name     | Hex     | Use                           |
| -------------- | ------- | ----------------------------- |
| Primary Blue   | #3B82F6 | Buttons, CTAs                 |
| Slate Dark     | #0F172A | Background                    |
| Soft White     | #F8FAFC | Primary text background       |
| Accent Green   | #22C55E | Success states, progress bars |
| Warning Yellow | #FACC15 | Warnings, AI suggestions      |
| Error Red      | #EF4444 | Errors, conflicts             |

Use TailwindCSS utility classes to apply the color palette cleanly.

---

## 💸 Subscriptions & Pricing

| Plan        | Monthly Price | Features                                                                 |
| ----------- | ------------- | ------------------------------------------------------------------------ |
| **Free**    | $0            | 1 project, 2 languages, 1 collaborator, 100 AI translations/month        |
| **Starter** | $12/month     | 5 projects, 10 languages, unlimited collaborators, 1,000 AI translations |
| **Pro**     | $29/month     | 25 projects, unlimited languages, priority AI access, export history     |
| **Team**    | $99/month     | Everything in Pro, teams with role management, audit logs, API access    |

---

## 📈 MRR (Monthly Recurring Revenue) Projections (Example)

Let’s assume this growth:

| Month | Users  | Conversion Rate | Paying Users | ARPU | MRR     |
| ----- | ------ | --------------- | ------------ | ---- | ------- |
| 1     | 500    | 3%              | 15           | $15  | $225    |
| 2     | 1,500  | 5%              | 75           | $18  | $1,350  |
| 3     | 3,000  | 6%              | 180          | $20  | $3,600  |
| 6     | 10,000 | 7%              | 700          | $23  | $16,100 |

> ARPU increases as more teams choose higher-tier plans.

---
