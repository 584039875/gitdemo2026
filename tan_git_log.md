>git init
>git add .
>git commit -m "first commit"
>git branch -M main
>git remote add origin https://github.com/username/repository-name.git
>git push -u origin main

vpn proxy set:
>git config --global http.proxy 127.0.0.1:10808
>git config --global https.proxy 127.0.0.1:10808

vpn proxy unset:
>git config --global --unset http.proxy
>git config --global --unset https.proxy

git config set user:
>git config --global user.name "gltan123"
>git config --global user.email "584039875@qq.com"

reset from remote:
>git reset --hard origin/main

fetch from remote:
>git fetch origin main


