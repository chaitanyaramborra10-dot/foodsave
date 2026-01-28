# How to Run FoodSave Locally


Because this app uses **Firebase** and **JavaScript Modules**, you cannot simply double-click the `index.html` file. Browsers block secure features (like Login) when you use the `file://` protocol.

### 🚀 The "One-Command" Fix
1. Open your terminal (Command Prompt or PowerShell).
2. Type this command and press Enter:
   ```bash
   npx serve "C:\Users\chaitanya ram Borra\.gemini\antigravity\scratch\foodsave"
   ```
3. You will see a link like `http://localhost:3000`. 
4. **Copy and paste that link into your browser.**

### 🛠️ Why do I have to do this?
- **Security**: Google Login requires a "Secure Origin" (like `localhost` or a real website). `file://` is not considered secure by browsers.
- **Modules**: The code uses `import/export` statements which only work through a server.

### 🌐 Ready to go live?
If you want a link that works for everyone else (not just on your computer), follow the **[Deployment Guide](file:///C:/Users/chaitanya%20ram%20Borra/.gemini/antigravity/scratch/foodsave/.agent/workflows/deploy.md)** I created for you!
