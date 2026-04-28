git init
git add .
git commit -m "Initial frontend commit"
git remote add origin [Frontend_Repo_Link]
git branch -M main
git push -u origin main

git add .
git commit -m "Connected to Render backend"
git push origin main

npm init -y
npm install express mongoose dotenv cors

frontend eke api.js ekt thmi backend host url ek denna ona.

1. Render (Backend Hosting)

Build Command: npm install
Start Command: node server.js

2. Vercel (Frontend Hosting)
Vercel ekata frontend repo eka connect karama me details danna:

Framework Preset: Vite (Meka automatic detect wei)
Root Directory: ./ (Repo eka athulema thiyena nisa)
Build Command: npm run build
Output Directory: dist
Environment Variables:

PORT=5000
MONGO_URI=mongodb+srv://userTest:user123@cluster0.edubbih.mongodb.net/?appName=Cluster0 
