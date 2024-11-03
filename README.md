# How to run the application
1. Download the zip file and extract the zip
2. Go to the terminal of your folder
3. Check the node and npm version by typing this on the terminal:
  a. node --version
  b. npm --version
4. If it's not showing the version, you need to install the node.js
5. Type "npm init -y" in the terminal
6. Type "npm install express" in the terminal
7. Type "npm install mongodb" in the terminal
8. Type "npm install ejs" in the terminal
9. Type "npm install body-parser" in the terminal
10. Type "node server.js" in the terminal
11. Open browser and go to "http://localhost:3000"
12. If there is an error related to mongodb after loading the "http://localhost:3000":
  a. Downgrade the mongodb version by running this in the terminal "npm install mongodb@6.3.0"
  b. Try to run again "node server.js"
  c. Open the browser again and load "http://localhost:3000"
