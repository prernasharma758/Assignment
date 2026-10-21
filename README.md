# Assignment
# Question 1 :  What happens between typing a URL and seeing the page ?
When we type a URL into a browser and press Enter, several things happen in the background before the webpage appears on our screen.
First, the browser understands the URL and identifies which website we want to visit. Then, it uses DNS to find the IP address of that website because computers use IP addresses to communicate with each other.
Once the IP address is found, the browser establishes a connection with the server. If we are visiting an HTTPS website, a secure connection is also established to protect the data being exchanged.
After that, the browser sends a request to the server asking for the webpage. The server processes the request and sends back the required content, usually starting with HTML.
The browser then reads the HTML, loads the necessary CSS and JavaScript files, and processes images and other resources. HTML provides the structure, CSS handles the design, and JavaScript adds interactivity.
Finally, the browser puts everything together and displays the webpage on our screen. All these steps happen very quickly, which is why we can open a website within seconds.
# Question 3 : Terminal Navigation Practice Sheet
Objective: Learn how to navigate folders and files using the terminal in VS Code.
1. Basic Terminal Commands
pwd – Shows the current working directory.

ls – Lists files and folders in Linux/macOS.

dir – Lists files and folders in Windows Command Prompt.

cd foldername – Opens the specified folder.

cd .. – Moves one level up to the parent directory.

mkdir foldername – Creates a new folder with the specified name.

clear – Clears the terminal screen in Linux/macOS.

cls – Clears the terminal screen in Windows Command Prompt.

touch filename – Creates an empty file in Linux/macOS or Git Bash.

# Question 4 : Repository with at least three meaningful commits
Step 1: Configure Git Identity (One-Time Setup)
git config --global user.name "Prerna Sharma"
git config --global user.email "your-github-email@example.com"
Step 2: Create a Repository
mkdir html-css-assignments
cd html-css-assignments
git init
git branch -M main
Step 3: Create the First Commit
echo "# HTML CSS Assignments" > README.md
git add README.md
git commit -m "Initial commit: Add README"
Step 4: Create the Second Commit
mkdir HTML
echo "<h1>My First Webpage</h1>" > HTML/index.html
git add .
git commit -m "Add initial HTML webpage"
Step 5: Create the Third Commit
mkdir CSS
echo "body { font-family: Arial, sans-serif; }" > CSS/style.css
git add .
git commit -m "Add basic CSS styling"

