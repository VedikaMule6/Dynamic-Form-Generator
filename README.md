# Dynamic Form Generator

A React app that generates dynamic forms based on JSON schema with live preview and validation.

---

## Setup Instructions

### Prerequisites
- **Node.js** (v16+)
- **npm** or **yarn**
- **Git**

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/VedikaMule6/Dynamic-Form-Generator.git
   cd Dynamic-Form-Generator
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Run the Project
```bash
npm start
```
Visit `http://localhost:3000` in your browser.

---

## Example JSON Schema

```json
{
  "formTitle": "Project Requirements Survey",
  "formDescription": "Please fill out this survey about your project needs.",
  "fields": [
    {
      "id": "name",
      "type": "text",
      "label": "Full Name",
      "required": true
    },
    {
      "id": "email",
      "type": "email",
      "label": "Email Address",
      "required": true
    }
  ]
}
```

---

## Development Commands

- **Start server**: `npm start`
- **Build project**: `npm run build`
- **Run tests**: `npm test`

---

## Deployment
Deployed via [Vercel](https://vercel.com). Access the live app here:  
[Dynamic Form Generator Live](https://dynamicformgenerator-seven.vercel.app/)

---
