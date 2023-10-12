# 北京开发者 [beijing.dev](https://beijing.dev/)

> 北京开发者

- [GitHub](https://github.com/): [pages](https://pages.github.com/) / [dev](https://github.com/beijingit/dev)
- [js.org](https://js.org/): [beijingdev.js.org](https://beijingdev.js.org)

## 源码管理

```bash
# 创建
mkdir -p D:\github\beijingit\
cd /d D:\github\beijingit\

# 拉取
git clone https://github.com/beijingit/dev.git

# 进入
cd /d D:\github\beijingit\dev

# 编辑
echo "Hello World" > index.html
notepad index.html

echo "beijingdev.js.org" > CNAME

# 提交
git add --all
git commit -m "Initial commit"
git push -u origin main
```

---

## 自定义域名

```bash
# Settings GitHub Pages
https://github.com/beijingit/dev/settings/pages

start https://beijingit.github.io/dev

# js.org
https://github.com/js-org/js.org
# 右上角的 Fork 按钮
https://github.com/beijingit/js.org
# pull
git clone https://github.com/beijingit/js.org.git

# edit
cnames_active.js

# 添加二级域名，以及 CNAME 到的网址。注意，约定都是按字母顺序排序
"beijingdev": "beijingit.github.io/dev"

# push 上 github

# Pull Request

#
https://beijingdev.js.org/
```
