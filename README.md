# mnist_project
✅ STEP 1 — 
Create a Project Folder
Terminal command:
mkdir mnist_project
cd mnist_project

What it does:
mkdir mnist_project → makes a folder
cd mnist_project → goes inside the folder
This keeps your ML project clean and organized.

✅ STEP 2 — 
Create a Python Virtual Environment
Terminal command:
python -m venv venv

Activate it:
source venv/bin/activate

Why:
Keeps your project libraries separate
Prevents TF from conflicting with system Python
All ML projects use virtual environments

✅ STEP 3 — 
Install ML Libraries Inside the venv
Terminal command:
pip install --upgrade pip
pip install numpy matplotlib tensorflow

What this does:
Updates pip
Installs NumPy (math), Matplotlib (images), TensorFlow (AI brain)

✅ STEP 4 — 
Create Your Main Project File
Terminal command:
nano main.py
This opens a text editor.
