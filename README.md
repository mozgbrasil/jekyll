[checkmark]: https://raw.githubusercontent.com/mozgbrasil/mozgbrasil.github.io/refs/heads/main/docs/logo-mini.png "MOZG"

![valid XHTML][checkmark]

# Jekyll

- https://mozg.com.br/jekyll/

## Run

```bash
git clone ☝️

cd /home/marcio/dados/jekyll/
code --new-window .

ruby --version
bundle --version

rm Gemfile.lock
bundle install

JEKYLL_ENV=dev bundle exec jekyll serve --watch --verbose
JEKYLL_ENV=production bundle exec jekyll serve --watch --verbose
```

## Executando no container

```bash
├── Terminal
│   ├── Run Task
│       ├── Serve
│       ├── OR
│       ├── Build
```

## release

```bash
gh release create v1.0.0 --generate-notes
```

## publish - angular dist

```bash

rm -fr /home/marcio/dados/mozgbrasil.github.io/docs

# cp -r /home/marcio/dados/nx-ionic-angular/dist/apps/main-app/browser /home/marcio/dados/jekyll/docs
# cp -r /home/marcio/dados/nx-ionic-angular/dist/apps/material.angular.io/browser /home/marcio/dados/jekyll/docs
cp -r /home/marcio/dados/vitepress/docs/.vitepress/dist /home/marcio/dados/mozgbrasil.github.io/docs

cp /home/marcio/dados/mozgbrasil.github.io/CNAME /home/marcio/dados/mozgbrasil.github.io/docs

git status
git add --all
git commit -m "angular ssg"
git status
git push --verbose
```




## Sinopse

Site insitucional da MOZG

## Motivação

Portfólio pessoal

## Contribuição

Caso queira contribuir para melhoria da documentação de um Fork no repositório e envie um pull request ou edite no github

## Requerimentos

- https://www.docker.com/
- https://code.visualstudio.com/
- https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack

## Links

- https://www.freeformatter.com/html-formatter.html
- https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fmozg.com.br%2F
- https://github.com/primer/primer
- https://github.com/pages-themes/primer

### Backend

- https://pages.github.com/
- https://pages.github.com/versions/
- http://jekyllrb.com/
- https://talk.jekyllrb.com/
- https://github.com/jekyll/jekyll/wiki/Themes
- http://jekyllthemes.org/
- https://help.github.com/articles/setting-up-a-custom-domain-with-github-pages/
- https://github.com/plusjade/jekyll-bootstrap/blob/master/_plugins/debug.rb

### Frontend

- http://getbootstrap.com/

### Add-ons

- http://jch.penibelst.de/
- https://github.com/bryanbraun/anchorjs
- https://code.google.com/apis/console/
- https://cse.google.com/
- https://www.google.com/analytics/web/
- https://developers.facebook.com/
- https://disqus.com/
- http://www.freeformatter.com/html-formatter.html
- https://pt.wikipedia.org/wiki/Estrela_vermelha
- https://cloudconvert.com/svg-to-ico
- http://willianjusten.com.br/dominio-proprio-no-github-pages/
- http://mozgbrasil.github.io/
- http://mozg.com.br/
- https://support.google.com/plus/answer/2676340?hl=pt-BR
- http://all-free-download.com/free-vector/download/obama_58569.html
- http://all-free-download.com/free-vector/download/barack_obama_58568.html
- https://archive.org/
- https://archive.org/web/
- https://cards-dev.twitter.com/validator

###

- https://wiredcraft.com/blog/make-jekyll-fast/
- https://github.com/dimitri-koenig/jekyll-gulp-optimizations
- https://dillinger.io/

### plugin

- https://github.com/tnhu/jekyll-include-absolute-plugin

:cat2:
