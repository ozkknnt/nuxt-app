# vue-nuxt-app

* 参考URL　　
  * Nuxt.js 初期設定  
    https://zenn.dev/catch/articles/install_nuxtjs
  * github page使い方  
    https://qiita.com/Anderiens/items/a4c5783b5197de682329　  
  * cross-env  
    https://qiita.com/TakahiRoyte/items/c152ad8baa191ed1f8ae
  * Nuxt.js 公式  
    https://develop365.gitlab.io/nuxtjs-2.8.X-doc/ja/faq/github-pages/
  * GithubPageの使い方  
    https://qiita.com/Ancient_Scapes/items/fe18bae043e4d35f1e39
  * master ブランチから　gh-pagesブランチへの同期　　
    https://senooken.jp/post/2020/01/24/

* 起動  
 npm run genarate を実行しないとBuildできない  
 npm run start 


## master ブランチから gh-pagesブランチへ同期するために 
プロジェクトフォルダ直下に ```.git/hooks/post-commit``` ファイルを作成し、下記のスクリプトを記述する。
```
git push -f origin main:gh-pages
```
