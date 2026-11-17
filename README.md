# My Debt 💸

**My Debt** is a professional-grade, mobile-first Progressive Web App (PWA) designed to easily and securely track informal loans, manage payment schedules, and handle receipts. Built with a sleek fintech aesthetic, it features real-time calculations, secure user authentication, unique custom `@usernames`, and public read-only sharing via WhatsApp.

---

## ✨ Key Features

* **Fintech UI/UX**: Deep dark mode aesthetics (`#0b0f19`), high-impact centered balances, rounded widget cards, and a native-feeling bottom navigation bar.
* **Secure Authentication & Profiles**: Powered by Supabase Auth with custom unique `@username` registration and onboarding.
* **Advanced Loan Metrics**: Automatic tracking of remaining balances, interest/inflation adjustments, periodic quotas, income allocation percentages, and payment punctuality index.
* **Payment History & Receipts**: Record periodic payments, add notes, and upload transfer receipts directly to secure Supabase storage buckets.
* **Public Read-Only Sharing**: Generate secure token-based links (`#/v/[share_token]`) that let creditors review balances and payment history instantly via WhatsApp **without requiring a login**.

---

## 🛠️ Tech Stack

* **Frontend**: Single-file HTML5, CSS3 (Modern Flexbox/Grid, CSS Variables), and Vanilla JavaScript (ES6+).
* **Backend & Database**: Supabase (PostgreSQL, Auth, Storage, Row Level Security, and custom PL/pgSQL RPC functions).
* **Hosting**: Static web deployment (GitHub Pages, Vercel, etc.).

---

## 🚀 Quick Setup & Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/my-debt.git](https://github.com/your-username/my-debt.git)
