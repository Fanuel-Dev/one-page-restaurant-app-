# 1. Initialize git in your local project folder
git init

# 2. Stage all your files (App.jsx and README.md)
git add .

# 3. Create your first commit
git commit -m "Initial commit: High-demand restaurant app with full README documentation"

# 4. Rename your main branch to 'main'
git branch -M main

# 5. Link your local folder to your GitHub project
# (Replace the URL below with your actual GitHub repository URL)
git remote add origin https://github.com/YOUR-USERNAME/dineflow-restaurant-app.git

# 6. Push your files live to GitHub
git push -u origin main
