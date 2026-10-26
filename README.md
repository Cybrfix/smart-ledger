# 📖 Smart Ledger & Personal Khata (স্মার্ট লেনদেন খাতা)

A modern, fast, and secure personal ledger web application designed to track day-to-day transactions, manage personal khata accounts, and securely sync your financial data in real-time. Developed with a sleek UI using **Tailwind CSS** and powered by **Firebase**.

🌐 **Live Demo:** [https://cybrfix.github.io/smart-ledger/](https://cybrfix.github.io/smart-ledger/)  
📌 **Project by Cybrfix**

---

## ✨ Key Features (মূল বৈশিষ্ট্যসমূহ)

*   👥 **Person-wise Khata:** Maintain separate transaction ledgers for different individuals with their names and phone numbers.
*   🔄 **Smart Transaction Logic:** Simple and intuitive transaction flow:
    *   **দিলাম (Gave):** Increases your receivable amount (পাওনা বাড়ল).
    *   **পেলাম (Received):** Decreases your balance/settles dues (হিসাব কমল).
*   ☁️ **Cloud Sync & Google Login:** Securely sign in with your Google account to sync and store your transaction records safely in Firebase Firestore.
*   🌍 **Multilingual Support:** Fully switchable interface between **Bangla (বাংলা)** and **English**.
*   📱 **Mobile-First & Responsive UI:** Designed cleanly to fit mobile and desktop screens without horizontal scrolling issues.
*   📊 **Global & Active Summaries:** Quick glance at total receivables, payables, and net balance at any time.
*   🗑️ **Full Management Controls:** Edit or delete individual entries or completely delete a person's ledger when needed.
*   📥 **Backup & Restore:** Easily export your ledger data as a `.json` backup file or restore it anytime via the Import feature.

---

## 🛠️ Tech Stack (প্রযুক্তিসমূহ)

*   **Frontend:** HTML5, Tailwind CSS (CDN), Phosphor Icons
*   **Scripting:** Vanilla JavaScript (ES6+)
*   **Backend & Database:** Firebase Authentication (Google Sign-In) & Cloud Firestore
*   **Hosting:** GitHub Pages

---

## 🚀 Getting Started Locally (লোকালি রান করার নিয়ম)

If you want to run or test this project locally, follow these simple steps:

1. Clone the repository:
   ```bash
   git clone [https://github.com/cybrfix/smart-ledger.git](https://github.com/cybrfix/smart-ledger.git)


Open the project folder in your favorite code editor (e.g., VS Code).

Use a local server extension (like Live Server in VS Code) to open index.html. (Note: Direct file opening file:/// might restrict Firebase authentication popups).

🔒 Firebase Configuration
This app uses Firebase for user authentication and cloud storage. Ensure your Firebase project has Google Sign-In enabled under Authentication providers and your domain is added to Authorized Domains.

📄 License
This project is open-source and available under the MIT License.

Developed with ❤️ by Cybrfix


   
