# EmailJS Troubleshooting

## 412 Gmail API Error Fix:

**The 412 error means Gmail didn't grant enough permissions. Here's how to fix it:**

### Option 1: Reconnect Gmail (Recommended)
1. Go to EmailJS dashboard → Services
2. Delete your Gmail service
3. Add Gmail service again
4. **When Google asks for permissions, click "Allow" for ALL permissions**
5. Make sure "Send email on your behalf" is granted

### Option 2: Use App Password (If 2FA enabled)
1. Go to Google Account settings
2. Security → 2-Step Verification → App passwords
3. Generate app password for "Mail"
4. In EmailJS, use this app password instead of your regular password

### Option 3: Alternative Email Service
If Gmail keeps failing, try:
- **Outlook/Hotmail** (usually works better)
- **Yahoo Mail**
- **Custom SMTP** (if you have one)

### Quick Test:
After fixing, test by sending yourself an email from EmailJS dashboard before testing your website.

**Most Common Fix:** Just reconnect Gmail and allow all permissions!