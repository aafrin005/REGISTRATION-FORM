
# REGISTRATION FORM

A simple web application that allows users to submit a registration form, and all submitted data is automatically stored inside a connected Google Sheet using Google Apps Script as a backend API.

---

##  Tech Stack Used

### Frontend
- **HTML5** – Page structure
- **CSS3** – Styling and layout
- **JavaScript** – Form submission + API calls

### Backend
- **Google Apps Script Web API** – Acts like a backend server
- **Google Sheets** – Used as the database

---

## How to Set Up and Run

1. **Create a Google Sheet**
   - Rename the sheet to `UsersDB`
   - Add headers: `ID`, `Full Name`, `Email`, `Phone`, `Address`, `Extra`

2. **Open Apps Script**
   - Go to Extensions → Apps Script
   - Paste the provided backend code
   - Replace `"YOUR_SHEET_ID_HERE"` with your actual Sheet ID

3. **Deploy as Web App**
   - Click Deploy → New Deployment → Web App
   - Set access to: `Anyone`
   - Copy the Web App URL

4. **Update HTML**
   - Paste the Web App URL into your `index.html` and `list.html` files

5. **Test the App**
   - Open `index.html` in browser
   - Submit sample data
   - Open `list.html` to view, update, or delete users



