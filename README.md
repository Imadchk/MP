brew install git
sudo apt-get install git
mkdir my-python-app
cd my-python-app
git init
touch app.py
print("Hello, World!")
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/yourusername/my-python-app.git
git push -u origin master
