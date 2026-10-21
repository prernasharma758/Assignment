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
| Command            | Purpose                               | Example            |
| ------------------ | ------------------------------------- | ------------------ |
| `pwd`              | Shows the current directory           | `pwd`              |
| `ls`               | Lists files and folders (Linux/macOS) | `ls`               |
| `dir`              | Lists files and folders (Windows CMD) | `dir`              |
| `cd foldername`    | Opens a folder                        | `cd Projects`      |
| `cd ..`            | Moves one folder back                 | `cd ..`            |
| `mkdir foldername` | Creates a new folder                  | `mkdir Practice`   |
| `clear`            | Clears the terminal (Linux/macOS)     | `clear`            |
| `cls`              | Clears the terminal (Windows CMD)     | `cls`              |
| `touch filename`   | Creates a file (Linux/macOS/Git Bash) | `touch index.html` |
