# Full Stack URL Shortener

## Overview
This is a full-stack URL shortener application built using **React JS**, **Tailwind CSS**, **Supabase**, and **Shadcn UI**. The project includes user authentication, URL shortening, QR code generation, and analytics tracking. It is designed to enhance a developer's skill set and can be showcased to potential employers.

---

## 🚀 Technologies Used
- **React JS** (Frontend)
- **Vite** (Project scaffolding)
- **Tailwind CSS** (Styling and responsive design)
- **Shadcn UI** (Modern UI components)
- **Supabase** (Backend, authentication, and PostgreSQL database)
- **QR Code Generator** (For sharing URLs easily)

---

## ⚙️ Features
- **User Authentication**: Users can sign up/log in using Supabase authentication.
- **URL Shortening**: Converts long URLs into short, shareable links.
- **Custom Links**: Users can set custom URLs instead of auto-generated ones.
- **Analytics Tracking**: Tracks clicks, user locations, and device types.
- **QR Code Generation**: Creates QR codes for shortened URLs.
- **User Dashboard**: Displays total links created, clicks, and detailed analytics.

---

## 📌 Project Setup
1. **Clone the repository**
   ```sh
   git clone https://github.com/Abhishek-raj-292002/url-shortener.git
   cd url-shortener
   ```
2. **Install dependencies**
   ```sh
   npm install
   ```
3. **Set up environment variables** (Create a `.env` file and add Supabase credentials)
   ```env
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_anon_key
   ```
4. **Run the development server**
   ```sh
   npm run dev
   ```

---

## 🗄️ Database Schema
The application uses Supabase with the following schema:

- **URLs Table**: Stores original and shortened URLs, user ID, and creation timestamp.
- **Clicks Table**: Stores analytics on each shortened URL visit, including timestamp, location, and device type.
- **Users Table**: Manages authentication and user details.

---

## 🚀 Deployment
You can deploy to **Vercel** or **Netlify** for easy hosting.
1. Build the project:
   ```sh
   npm run build
   ```
2. Upload the `dist` folder to your hosting provider's public directory.
3. Ensure proper routing configuration to prevent refresh-related crashes.



---

## 🛠 Future Enhancements
- User profile customization.
- Payment integration for premium users.
- API access for developers to shorten links programmatically.

---

## 📩 Contributing
Contributions are welcome! Feel free to fork the project and submit pull requests.

---

## 📬 Contact
For any inquiries or collaboration opportunities, reach out via:
- **GitHub**: Abhishek-raj-292002(https://github.com/Abhishek-raj-292002)
- **Email**: abhishek.raj292002@gmail.com

