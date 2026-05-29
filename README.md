# Expo Registration System

A simple web-based registration and attendee management system built with HTML, CSS, and JavaScript.

## Contents

- `index.html` - main landing page
- `register.html` - attendee registration page
- `registration-desk.html` - registration desk interface
- `admin.html` - admin dashboard
- `directory.html` - attendee directory
- `css/style.css` - styling
- `js/` - client-side scripts

## Run locally

Install [http-server](https://www.npmjs.com/package/http-server) or use the included npm script:

```bash
npm install
npm run dev
```

The server will start on port 8000. Access the app using:

### On your PC (localhost):
- Hub/Dashboard: http://localhost:8000
- Registration Kiosk: http://localhost:8000/register.html
- Registration Desk: http://localhost:8000/registration-desk.html
- Admin Panel: http://localhost:8000/admin.html
- Directory: http://localhost:8000/directory.html
- Display: http://localhost:8000/display.html

### On mobile devices or other PCs (local network):

Find your machine IP first:

**Windows (PowerShell):**
```powershell
ipconfig
```
Look for "IPv4 Address" (e.g., `192.168.1.193`)

**Mac/Linux:**
```bash
ifconfig
```

Then replace `YOUR_IP` with your actual IP address:
- Hub: http://YOUR_IP:8000
- Registration: http://YOUR_IP:8000/register.html
- Admin: http://YOUR_IP:8000/admin.html

**Example:** http://192.168.1.193:8000/register.html

### Admin Dashboard

Default admin password: `admin123` (change this in admin settings for security)

The admin dashboard auto-syncs data in real-time across all connected devices.

## License

MIT
