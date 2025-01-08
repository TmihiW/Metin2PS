# Metin2 Private Server
InshaAllah Vs Code eklentilerinden yüklemenizi tavsiye ettiklerim;
- Git Project Manager
- GitHub Repositories
- GitHub Pull Requests
- GitHub Codespaces
- Git History
- gitignore
- vscode-icons

InshaAllah kullanırken sol altta main branch'a tıklayıp yeni branch oluşturabilirsin, oluşturduysan oradan değiştirebilirsin ; github web'den veya gitbash'den yeni branch oluşturup gene oradan değiştirebilirsiniz.

InshaAllah Remote Explorer sekmesinden de Githuh Codespaces değil Remote Repositories üzerinden çalışmanızı tavsiye ederim, start isimli bir branch oluşturup ona "Commit & Push" edip github web sitesi üzerinden main branch'a :

This branch is 1 commit ahead of 'a tıklayıp "Create pull request" deyip "Add a title" kısmına  örn: "4 Readme Changes" gibi not düşebilirsiniz, tabi merge ve confirm ile sonlandırmak kaydıyla requestleriniz yan branch'ınızın "Pull requests" sekmesinde "Closed" bölümünde listeleyebilirsiniz İnşAllah.


[click here to go "How to embed video-on-github" / click image to go "Github version control" video](https://stackoverflow.com/questions/11804820/how-can-i-embed-a-youtube-video-on-github-wiki-pages "video-on-github")

[![Github version control](https://img.youtube.com/vi/6ebE_XxmDWY/3.jpg)](https://www.youtube.com/watch?v=6ebE_XxmDWY "Github version control")


***
#using gitbash terminal on vs code 
[How to][https://www.geeksforgeeks.org/how-to-integrate-git-bash-with-visual-studio-code/]

git config --global user.email "kadirfindik3871@gmail.com"
git config --global user.name "TmihiW"

H5 çalışmadı
cd C:\Users\kadir\.vscode\MyRepos
H5 çalıştı
cd C:/Users/kadir/.vscode/MyRepos

(en başta 1kere) git clone https://github.com/TmihiW/Metin2PS.git
cd Metin2PS
git status

cd Metin2PSlocal
git pull https://github.com/TmihiW/Metin2PS.git Start --allow-unrelated-histories

(Programs Dosyası Oluşturdum)
git lfs install
git lfs track Programs
(Programs Klasörüne Bir Dosya Attım)
git status

git add -A
git status
git commit -m "Add files via gitBash"
git remote add origin https://github.com/TmihiW/Metin2PS.git
git push origin master

git lfs track VirtualBox-6.1.12-139181-Win.exe

git reset --hard HEAD
git clean -f -x -d -n
git status

(Branch değiştirdim)
git checkout Start
git push --set-upstream origin Start

cd C:/Users/kadir/.vscode/MyRepos/Metin2PS
git merge --abort
rm ~/.vscode/MyRepos/Metin2PS/.git/.MERGE_MSG.swp
