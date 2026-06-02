# Will You Go Out With Me? 💕

A fun interactive web app that makes it nearly impossible to say "No" to a date request! The "No" button moves away when you try to click it, encouraging a "Yes" response.

## ✨ What it does

- Ask someone out in a playful way
- "No" button moves around to avoid clicks  
- Shows celebration GIFs when they say "Yes"
- Generates random date ideas
- Sends you email notifications when they accept (optional)

## 🚀 Quick Start

1. Open `index.html` in a web browser
2. Share with your crush!

## 📧 Email Setup (Optional)

Want to know when they accept? Set up email notifications:

1. **Get Web3Forms access key**:
   - Go to https://web3forms.com
   - Enter your email address
   - Get your free access key instantly (no signup required)

2. **Configure your app**:
   - Edit `config.json`
   - Add your crush's name to `crushName` (optional)
   - Replace `YOUR_WEB3FORMS_ACCESS_KEY_HERE` with your actual key
   - Customize the `dateIdeas` array with your own ideas

3. **Done!** You'll get emails when they select date activities

### config.json format:
```json
{
  "crushName": "Their Name Here",
  "dateIdeas": [
    "Cook dinner together",
    "Go for a walk",
    "Watch a movie"
  ],
  "web3forms": {
    "accessKey": "your-actual-key-here",
    "fromName": "Date App Notification",
    "subject": "💕 She Selected a Date Activity!"
  }
}
```

## 🎮 How It Works

1. Shows "Will you go out with me?" question
2. "No" button runs away when clicked/hovered
3. "Yes" shows celebration and date ideas
4. Email sent when date idea is accepted (if configured)

## 📁 Files

- `index.html` - Main page
- `style.css` - Styling  
- `script.js` - Interactive features
- `config.json` - Your email and personalization settings
- `*.gif` - Animation files

---

💡 **Inspired by**: https://github.com/sidpro-hash/doyouwannagooutwithme.git

*Made with 💖 for memorable moments!*