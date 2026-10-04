# setup identitas (sekali saja)
git config --global user.name "Adema Areta"
git config --global user.email "aretamdza@gmail.com"

# mulai repo pertama
mkdir oee-calculator && cd oee-calculator
git init -b main
# buat README.md, .gitignore, LICENSE dulu
git add .
git commit -m "chore: initial commit with README and license"
git remote add origin https://github.com/USERNAME/oee-calculator.git
git push -u origin main
