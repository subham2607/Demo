#Demo
install Homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install git
mkdir Demo
cd Demo
echo "#Demo" >> README.md
cat README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/<your_username>/Demo.git
