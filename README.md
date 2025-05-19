## Usage

### Step1. Clone
```
git clone git@github.com:rentarouapp/scripts.git
```

### Step2. Pass the path or linking
#### ~/.zshrc
```
echo 'export PATH="$HOME/scripts:$PATH"' >> ~/.zshrc
```
#### /usr/local/bin
```
sudo ln -s ~/scripts/${scripts_name} /usr/local/bin/${scripts_name}
```
### Step3. Use Scripts
#### e.g. git-copy-branch
If you type the following command:
```
cd ${your_project}
git-copy-branch
```
This will copy the git current branch name to your clipboard.
