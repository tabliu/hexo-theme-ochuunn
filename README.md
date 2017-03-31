# Ochuunn

## 特点
文章界面很清晰，很适合阅读~

## Demo
[I am Oliver](http://ochukai.me)

## Features

* Google Search Console
* Google Analytics
* Disqus
* Live2d WebGL (比较大，可能会导致页面加载变慢~)
* Hotjar
* Reward

## Install
1. In the `root` directory:

```git
$ git clone https://github.com/ochukai/hexo-theme-ochuunn.git themes/ochuunn
```

2. Change the `theme` property in the `config.yml` file.

```yml
# theme: landscape
theme: ochuunn
```

3. Run: `hexo generate` and `hexo server`


## Tips
Add these code to your package.json

```js

"scripts": {
  "deploy": "hexo clean && hexo generate && hexo deploy",
  "start": "hexo clean && hexo s --debug"
},

```

After you do this, just run `npm start` to debug your site and run `npm run deploy` to deploy your site.
