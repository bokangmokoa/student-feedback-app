# Deployment Plan for Student Feedback App

## Step 1: Switch Backend from SQLite to MongoDB

- [ ] Update backend/package.json to include mongoose and remove sqlite3
- [ ] Update backend/config/database.js to connect to MongoDB
- [ ] Update backend/models/Feedback.js to use Mongoose schema
- [ ] Update backend/controllers/feedbackController.js for MongoDB operations
- [ ] Create backend/.env file with MongoDB URI placeholder
- [ ] Test backend with MongoDB locally

## Step 2: Push to GitHub

- [ ] Initialize git repository
- [ ] Create .gitignore files for backend and frontend
- [ ] Add all files to git
- [ ] Commit changes
- [ ] Create GitHub repository
- [ ] Push to GitHub

## Step 3: Deploy Backend

- [ ] Deploy backend to Railway (or Render)
- [ ] Set environment variables in Railway
- [ ] Get backend URL

## Step 4: Update Frontend for Production

- [ ] Update frontend/package.json proxy to production backend URL
- [ ] Build frontend for production

## Step 5: Deploy Frontend

- [ ] Deploy frontend to Vercel (or Netlify)
- [ ] Configure build settings
- [ ] Get live frontend URL

## Step 6: Final Testing

- [ ] Test live application
- [ ] Verify data persistence
- [ ] Update README with live links
