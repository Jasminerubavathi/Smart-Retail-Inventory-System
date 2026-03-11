# SmartRetail Frontend (Static)

This is a frontend-only static version of the SmartRetail sample site converted from JSPs to plain HTML/CSS/JS.

Contents
- `public/` — static site files (HTML, CSS, JS)

Quick start (Python)

1. Open a shell in the `public` folder:

```powershell
cd c:\Users\dell\Videos\Smartretail\Smartretail\smartretail-frontend\public
python -m http.server 8001
# open http://localhost:8001/index.html
```

Quick start (Node)

1. (Optional) If you prefer Node, run:

```powershell
cd c:\Users\dell\Videos\Smartretail\Smartretail\smartretail-frontend
npm install
npm start
# open http://localhost:8080
```

Notes
- This project is frontend-only. The login flow in `welcome.html` is a client-side demo and NOT secure.
- For production, wire the login form to a backend authentication endpoint and remove client-side credential checks.
