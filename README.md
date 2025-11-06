# 1. Initial setup
git add .
git commit -m "Initial commit: setup project structure"

# 2. Add homepage HTML
echo "<!DOCTYPE html><html><head><title>My WebApp</title></head><body><h1>Welcome!</h1></body></html>" > index.html
git add index.html
git commit -m "Add basic homepage structure"

# 3. Add CSS file
echo "body { font-family: Arial; background: #f5f5f5; }" > style.css
git add style.css
git commit -m "Add main stylesheet"

# 4. Link CSS in HTML
echo "<link rel='stylesheet' href='style.css'>" >> index.html
git add index.html
git commit -m "Link stylesheet to homepage"

# 5. Add JavaScript file
echo "console.log('App started');" > script.js
git add script.js
git commit -m "Add JavaScript entry file"

# 6. Add navigation bar
echo "<nav><a href='#'>Home</a> | <a href='#'>About</a></nav>" >> index.html
git add index.html
git commit -m "Add simple navigation bar"

# 7. Improve page layout
echo "nav { background: #333; color: white; padding: 10px; }" >> style.css
git add style.css
git commit -m "Style navigation bar and improve layout"

# 8. Add footer section
echo "<footer><p>© 2025 My WebApp</p></footer>" >> index.html
git add index.html
git commit -m "Add footer to homepage"

# 9. Add interactive button
echo "<button onclick='sayHello()'>Click Me</button>" >> index.html
echo "function sayHello() { alert('Hello from WebApp!'); }" >> script.js
git add index.html script.js
git commit -m "Add interactive button with JavaScript alert"

# 10. Optimize code and finalize structure
git add .
git commit -m "Refactor HTML/CSS/JS for better readability"
