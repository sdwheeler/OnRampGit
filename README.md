# OnRampGit repository

This repo was created locally then pushed to GitHub.

```powershell
git init -b main
# Create the README.md file
copy ~/Downloads/README.md
git add -A
git commit -m "initial commit"
gh repo create -s . -r origin -h https://github.com/sdwheeler/OnRampGit.git -d 'Test repo for OnRamp class' --public --push
```