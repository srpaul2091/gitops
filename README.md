```bash
cd /d01/MyWork/1/K8s/NATIVE/TF/aws-k8s-basic-setup-CKA/gitops-main
echo "# gitops" >> README.md
git init
git add .
git commit -m "first commit at $(date '+ %A, %B %d, %Y at %I:%M %p')"
git branch -M main
git remote add origin https://srpaul2091@github.com/srpaul2091/gitops.git
git push -u origin main
```
