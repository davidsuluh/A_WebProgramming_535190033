1. remove existing git related file in the folder using rd .git /s/q
git init
git add * ( * buat add semua yg ada di folder)
git commit -m "first commit" (save changes to local repo)
those steps above , we created git local repository

now configure this to each other 

git remote add origin https://github.com/sienshens1st/A_WebProgramming_535190033.git
git push -u origin master ( pertama kali harus lengkap ) (push local repo to remote repo)


kalo ada perubahan 
git add *
git status
git commit -m "changed content"
git push
test



 kalau ada tanda arrow gitu 
 git rm --cached week1
 (Run git rm --cached path_to_submodule (no trailing slash))

 kl gamau ada file yg dimasiukin di git = .gitignore

 git branch

 git branch namabranch
 git checkout namabranch (pindah directory)
