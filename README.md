# React-Node Technical Assessment – Food Ordering App

This is a full stack food ordering web application built with the MERN stack (MongoDB, Express, React, Node.js).

It consists of a customer-facing app and an admin panel for managing menu items, orders, and users.

---

## ✅ Completed Fixes (Per Technical Test)

1. **Authentication Error Handling**

   - Login returns `401 Unauthorized` if credentials are incorrect
   - Register returns `401 Unauthorized` if user already exists
   - Returns appropriate `400` and `500` status codes for validation/server errors

2. **UI Enhancement**

   - Menu images now have a smooth **hover zoom-in effect**

3. **Order UI Fix**
   - Quantity buttons (`+`/`–`) are vertically aligned and visually consistent

---

## 🛠️ Tech Stack

- **Frontend:** React, Context API, CSS
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Auth:** JWT + Bcrypt
- **Payments:** Stripe (test mode)
- **Deployment:** Local only

---

## 🚀 How to Run Locally

### Backend

```bash
cd backend
npm install
npm run server
```
