# EmailJS Setup Guide

## Quick Setup (5 minutes):

1. **Go to [EmailJS.com](https://www.emailjs.com/)**
2. **Create free account**
3. **Add Email Service:**
   - Click "Add New Service"
   - Choose Gmail
   - Connect your Gmail account

4. **Create Email Template:**
   - Go to "Email Templates"
   - Click "Create New Template"
   - Use this template:
   ```
   Subject: {{subject}}
   
   New message from your portfolio:
   
   Name: {{from_name}}
   Email: {{from_email}}
   Subject: {{subject}}
   
   Message:
   {{message}}
   ```

5. **Get Your Keys:**
   - Copy your Public Key from Account settings
   - Copy Service ID from Services
   - Copy Template ID from Templates

6. **Update script.js:**
   - Replace `YOUR_PUBLIC_KEY` with your public key
   - Replace `YOUR_SERVICE_ID` with your service ID  
   - Replace `YOUR_TEMPLATE_ID` with your template ID

## Why This Impresses Recruiters:
✅ **Real functionality** - Form actually works
✅ **API integration** - Shows technical skills
✅ **User experience** - Professional feedback messages
✅ **Problem solving** - Made static site dynamic
✅ **Attention to detail** - Proper error handling

Your contact form will now send real emails to diyalidaniel@gmail.com!