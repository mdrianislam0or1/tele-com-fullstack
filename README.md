# Tele-Com Full Stack Application

## Live

https://stock-trades-dashboard.vercel.app/

## Description

This is a full-stack application for managing trade data using Flask for the backend and React for the frontend.

## Features

- CRUD operations for trade data.
- Data validation and error handling.
- Integration with MongoDB using Flask-PyMongo.
- Environment variable management using dotenv.

## Lessons Learned

During this project, I learned:

- How to set up a full-stack application using Flask and React.
- Managing environment variables securely.
- Handling data validation and parsing in both backend and frontend.
- Interacting with a MongoDB database using Flask-PyMongo.
- Implementing CORS to handle cross-origin requests.

## Challenges Faced

- **Date Formatting Issues**: Initially faced issues with date formatting when updating trade data. Resolved by correctly parsing date strings.
- **Handling Immutable Fields in MongoDB**: Encountered errors when trying to update immutable fields like `_id`. Learned to exclude these fields from update operations.
- **State Management in React**: Managing the state for edit and view modes in the React component was challenging but taught me more about state management.

## How to Run

1. **Backend**:

   - Install dependencies: `pip install -r requirements.txt`
   - Run the Flask server: `python server.py`

2. **Frontend**:
   - Install dependencies: `npm install`
   - Run the React application: `npm run dev`

## Contact

- **Name**: Rian Islam
- **Phone**: +8801794193425
