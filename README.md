# CodinQuest - Online Coding Interview Platform

> CodinQuest is a coding interview platform built with **Next.js**, featuring realtime video calls, screen sharing, and a live code editor for online interviews. Optimized for both **interviewers and candidates**.

---

## Features

- Realtime video calls and screen sharing using **Stream.io SDK**
- Live code editor for candidates to write and share code with interviewers
- Two user roles: **Interviewer** and **Candidate**
- Candidates can view scheduled interviews
- Interviewers can schedule interviews, leave comments, and review candidates
- User authentication with **Clerk**
- Realtime database powered by **Convex**
- Optimized for modern web browsers

---

## Tech Stack

| Feature | Technology |
|---------|------------|
| Framework | Next.js |
| Authentication | Clerk |
| Database | Convex (Realtime) |
| Video Call & Screen Share | Stream.io SDK |
| Code Editor | Monaco Editor |
| Platform | Web (Responsive) |

---

## Screenshots

## Screenshots

| Home | Dashboard | New Call Screen | Join Meeting Tab |
|------|-----------|-----------------|-----------------|
| <img width="350" src="https://github.com/user-attachments/assets/b6320650-a48b-4a16-b6c8-034c5d1909d6" /> | <img width="350" src="https://github.com/user-attachments/assets/0bfd2b5d-13bc-4542-b637-099f174d2ce5" /> | <img width="350" src="https://github.com/user-attachments/assets/5d358fb4-3d54-40fb-a045-2a970167cc7b" /> | <img width="350" src="https://github.com/user-attachments/assets/c74bc58d-5c49-41d8-9d7c-a554870fd679" /> |

---

| Interview Call | Scheduled Interview | Schedule New Interview | Recordings |
|----------------|----------------------|------------------------|------------|
| <img width="350" src="https://github.com/user-attachments/assets/709a18a2-0652-4e6e-a57c-405eab52563f" /> | <img width="350" src="https://github.com/user-attachments/assets/89ee72c6-e254-47f7-b1e5-66f515f52ace" /> | <img width="350" src="https://github.com/user-attachments/assets/5b4cdd66-8b94-4a60-bf50-627651be2d8b" /> | <img width="350" src="https://github.com/user-attachments/assets/51e35db2-4f4f-4702-841f-57db7c31586a" /> |


---
##Candidate
| Candidate Dashboard |
|---------------------|
| <img width="300" src="https://github.com/user-attachments/assets/4574570a-5f4a-43a7-8691-a57c959bbdca" /> |

---


---

## Installation & Setup

1. **Clone the repository and install dependencies**

```bash
git clone https://github.com/yourusername/codinquest.git
cd codinquest
npm install
# or
yarn install
```
2. Create a .env.local file in the root directory and add your environment variables:
```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
CONVEX_DEPLOYMENT=your_convex_deployment
NEXT_PUBLIC_CONVEX_URL=your_convex_url
NEXT_PUBLIC_STREAM_API_KEY=your_stream_api_key
STREAM_SECRET_KEY=your_stream_secret_key
CLERK_FRONTEND_API_URL=your_clerk_frontend_api_url
```
3. Start the development server
   ```bash
   npm run dev
   # or
   yarn dev
   ```
## 📖 Documentation & Useful Links

- [Next.js Documentation](https://nextjs.org/docs)
- [Clerk Documentation](https://clerk.com/docs)
- [Convex Documentation](https://docs.convex.dev)
- [Stream.io Documentation](https://getstream.io/video/docs/)
