# Practical-


# 🧠 How to Install and Run Jupyter Notebook on Ubuntu

This guide explains how to **install and run Jupyter Notebook** on Ubuntu using different methods — either with `pip` or via **Anaconda**.

---

## ⚙️ Option 1: Install Using pip (Recommended)

### Step 1: Update System Packages
```bash
sudo apt update && sudo apt upgrade -y
Step 2: Install Python and pip
Make sure Python 3 and pip are installed:

bash
Copy code
sudo apt install python3 python3-pip -y
Step 3: Install Jupyter Notebook
bash
Copy code
pip install notebook
Step 4: Run Jupyter Notebook
bash
Copy code
jupyter notebook
This will open Jupyter in your web browser automatically:

arduino
Copy code
http://localhost:8888
🧱 Option 2: Install via Anaconda (Alternative)
Step 1: Download Anaconda Installer
bash
Copy code
wget https://repo.anaconda.com/archive/Anaconda3-latest-Linux-x86_64.sh
Step 2: Run the Installer
bash
Copy code
bash Anaconda3-latest-Linux-x86_64.sh
Follow the on-screen prompts and then restart your terminal.

Step 3: Run Jupyter Notebook
bash
Copy code
jupyter notebook
🧩 Optional: Create a Shortcut or Alias
To make launching Jupyter easier:

bash
Copy code
echo "alias jn='jupyter notebook'" >> ~/.bashrc
source ~/.bashrc
Now you can simply start it by typing:

bash
Copy code
jn
🧰 Troubleshooting
🔹 Command Not Found
If you get an error like command not found: jupyter, run:

bash
Copy code
pip install --upgrade pip
pip install notebook
🔹 Virtual Environment Setup (Optional)
If you prefer an isolated environment:

bash
Copy code
python3 -m venv myenv
source myenv/bin/activate
pip install notebook
💻 Run Jupyter in VS Code (Optional)
You can also use VS Code for an integrated notebook experience:

Install the Python and Jupyter extensions in VS Code.

Open a .ipynb file or create a new one.

Select your Python interpreter.

Start coding interactively!

✅ Summary
Method	Installation Command	Run Command
pip	pip install notebook	jupyter notebook
Anaconda	Preinstalled	jupyter notebook
Alias	jn	jn

👨‍💻 Author
Surendra Kamble
Created for easy setup of Jupyter Notebook on Ubuntu.

pgsql
Copy code

---

✅ **How to use this:**
1. Create a file named `README.md` in your GitHub repository.  
2. Copy and paste the above Markdown content.  
3. Commit and push — GitHub will automatically render it with perfect formatting.  

Would you like me to include a **“Run Output Preview” section** at the bottom (showing what the terminal or Jupyter start page looks like) so you can later add screenshots there?
