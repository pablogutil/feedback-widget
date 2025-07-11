# 📣 Feedback Widget

Embed this lightweight feedback collector into any web app to gather user insights, feature ratings, and comments — with a clean dashboard for reviewing submissions.

## 🎯 Features

- Floating "Feedback" button
- Modal form with:
  - Star or emoji rating
  - Optional comments
  - Auto-filled page URL
- Admin dashboard with:
  - Feedback table
  - Filter by rating/date
  - Ratings chart

## 🧱 Tech Stack

- React (Vite + TypeScript)
- TailwindCSS
- Feedback state stored locally or to backend (pluggable)

## 📁 Folder Highlights

src/
├── components/
│ └── FeedbackButton, FeedbackModal, AdminDashboard
├── lib/
│ └── useFeedbackStore.ts

markdown
Copy
Edit

## 📦 Use Cases

- In-product feedback for SaaS
- Landing page experiments
- Public beta feedback collection

## 🛠️ Extendable With

- NPS surveys  
- Screenshot uploads  
- Zapier/Webhook triggers
