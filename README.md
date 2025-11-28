# Youths Adda

**Youths Adda** is a modern blogging and content-platform focused on motorcycles, scooters, cars, accessories, technology, internet-tools (like calculators), web-stories and more. We aim to deliver well-researched, engaging content for youth and encourage community engagement through comments and social media. :contentReference[oaicite:1]{index=1}

## 🌐 What is Youths Adda

- A hub for articles on Motorcycles, Scooters, Cars, Accessories, Technology, Web-Stories, and useful online tools. :contentReference[oaicite:2]{index=2}  
- Offers a user-friendly interface for both quick reads and in-depth analyses. :contentReference[oaicite:3]{index=3}  
- Encourages community participation — readers can share opinions via comments or social media. :contentReference[oaicite:4]{index=4}  
- Aims to deliver reliable, fact-checked content. :contentReference[oaicite:5]{index=5}

## 🛠️ Tech Stack

*(Update this section based on your own implementation — example below)*  
- Front-end: [Next.js](https://nextjs.org/) / React  
- Back-end: [Strapi](https://strapi.io/) with GraphQL API  
- Database: MongoDB (or whichever DB you use)  
- Forms & Validation: Zod + React Hook Form  
- State & Data Fetching: Apollo Client (GraphQL)  
- PWA support (if implemented): e.g. using vite-plugin-pwa or next-pwa  
- Other utilities: Custom comment section, user authentication (if any), SEO optimizations, etc.

## 🚀 Setup & Local Development

*(Adjust commands and instructions as per your repo structure)*

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/youths-adda.git
cd youths-adda

# 2. Install dependencies
npm install

# 3. Setup environment variables
#    Create a .env file (or .env.local) with required variables, e.g.:
#    STRAPI_API_URL=...
#    NEXT_PUBLIC_API_URL=...
#    MONGODB_URI=...
#    (other keys as needed)

# 4. Run backend (if using Strapi)
cd backend
npm run develop

# 5. Run frontend
cd ../frontend
npm run dev
