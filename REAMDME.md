## init
```
hugo new site hongsheng-tich
git init
git submodule init
git submodule add https://github.com/themefisher/bigspring-hugo.git themes/bigspring-light

cp -R themes/bigspring-light/exampleSite/config ./
cp -R themes/bigspring-light/exampleSite/content ./
cp -R themes/bigspring-light/exampleSite/static ./
cp -R themes/bigspring-light/exampleSite/resources ./

git remote add origin git@github.com:fanfever/hongsheng-tich.git

mkdir .github/workflows
```
