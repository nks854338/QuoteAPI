# 📜 Quote API Project

Welcome to the **Quote API Project**! This project is designed to provide a simple yet powerful quote management system, featuring both a backend API and a frontend interface. Below you'll find detailed instructions for setting up and running both parts of the project.

## Demo Links
- **Frontend Demo**: [Click here](https://quote-api-frontend-lt1d.vercel.app/)
- **Backend Demo**: [Click here](https://quote-api-backend.vercel.app/)
- **Frontend Repository Link**: [Click here](https://github.com/nks854338/QuoteAPIFrontend)
- **Backend Repository Link**: [Click here](https://github.com/nks854338/QuoteAPIBackend)

## 🖥️ Frontend

The frontend is a React application that allows users to search for, view, and manage quotes.

### 🚀 Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/quote-api-project.git
   cd quote-api-project/frontend
   
## 🔧 Features
- Search Quotes: Search for quotes by author name.
- View Quotes: Display a list of quotes fetched from the backend.
- Filter Quotes: Filter quotes based on their state.
- Add Quotes: Option to add new quotes via the form (if enabled).
  
## 📂 Project Structure
- src/: Contains all the source files for the frontend application.
- components/: React components used in the application.
- context/: Context API setup for managing global state.
- App.js: Main application component.
- index.js: Entry point for the React application.
- 
## 🗄️ Backend
The backend is a Node.js application with Express.js that provides RESTful endpoints for managing quotes.

### API Endpoints
- GET /: Fetch all quotes.  ||  /quotes/:id fetch quote by id
- POST /api/quotes: Add a new quote.
- PATCH /quotes/:id: Add a new quote.
- DELETE /quotes/:id: Delete a quote by ID.

## 📂 Project Structure
- src/: Contains all the source files for the backend application.
- routes/: Defines the API routes.
- models/: Database models.
- index.js: Entry point for the backend application.
  
## 🛠️ Technologies Used
- Frontend: React, CSS, Axios
- Backend: Node.js, Express.js, MongoDB (if used)
