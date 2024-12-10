# Git Commands Reference

## 1. **Creating and Initializing a Git Repository**
```bash
mkdir git-demo
cd git-demo/
git init
```

## 2. **Listing Files and Viewing Hidden Files**
```bash
ls -la
```

## 3. **Creating and Deleting Files**
```bash
touch hello.txt
rm hello.txt
```

## 4. **Reinitializing a Git Repository**
```bash
rm -fr .git/
git init
```

## 5. **Checking the Status of the Repository**
```bash
git status
```

## 6. **Staging Files**
```bash
git add hello*
git add hello.txt
```

## 7. **Unstaging Files**
```bash
git rm --cached hello.txt
git restore --staged hello.txt
```

## 8. **Removing Files**
```bash
git rm hello.txt
```

## 9. **Restoring Files**
```bash
git restore hello.txt
```

## 10. **Committing Changes**
```bash
git commit -m "adding hello files"
git commit -m "adding new changes in hello-1 file"
```

## 11. **Configuring User Information**
```bash
git config --global user.name "belwadkar-rajesh"
git config --global user.email
```

## 12. **Editing Files**
```bash
vim hello-1.txt
```

## 13. **Viewing Command History**
```bash
history
```
