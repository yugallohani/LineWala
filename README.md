# LineWala
# Smart Barber Queue Management System

A lightweight web-based system to help barbers manage customer queues without long in-shop waiting times. Customers can join the queue using a QR code or short URL, and barbers can approve them into the queue to avoid confusion and misuse.

## 🚀 Features
- Join queue via QR code or short URL
- Barber approval before entering queue (prevents remote misuse)
- Estimated wait time calculation
- Live queue updates for customers
- “Hold Queue” feature to pause new registrations
- Optional WhatsApp/SMS notifications
- Admin dashboard for barbers to manage queues

## 🖥 Tech Stack
- **Frontend**: React.js / TailwindCSS
- **Backend**: Node.js (Express) / Firebase Functions
- **Database**: Firebase Realtime DB / MongoDB
- **Automation**: n8n for notifications & queue automation
- **Notifications**: Twilio / WhatsApp API (Optional)
- **Hosting**: Vercel (Frontend), Render / Firebase (Backend)

## 📌 Customer Flow
1. Scan QR / visit short URL
2. Fill basic info
3. Wait for barber approval
4. Track queue status and receive notifications

## 📌 Barber Flow
1. Login to dashboard
2. Approve/reject pending customers
3. Move queue with “Next” or “Skip” buttons
4. Pause queue with “Hold Queue” toggle
5. Optionally notify customers automatically

## ⚡ Automation with n8n
- Notify customers when their turn is near
- Auto-remove no-shows after X minutes
- Daily summary email to barber

---

## 🔧 Setup Instructions
1. Clone the repository  
2. Install dependencies: `npm install`  
3. Setup `.env` with DB credentials and Twilio/WhatsApp keys (optional)  
4. Run backend: `npm start`  
5. Run frontend: `npm run dev`  

---

### 📄 License
MIT License
