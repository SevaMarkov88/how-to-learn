# Проектная работа: "How to learn".

## Создана в рамках учебы в [Яндекс.Практикум](https://praktikum.yandex.ru/) на курсе ["Веб-разработчик"](https://praktikum.yandex.ru/web/).


## Описание:
Первый проект сделанный в процессе обучения. Краткий рассказ как научиться учиться)) На странице добавлены видео со сторонних ресурсов и добавлена анимация элементов.

[Посмотреть на GitHub Pages](https://sevamarkov88.github.io/how-to-learn/)

## Технологии:
![HTML](https://img.shields.io/badge/-HTML-05122A?style=flat&logo=HTML5)&nbsp;
![CSS](https://img.shields.io/badge/-CSS-05122A?style=flat&logo=CSS3&logoColor=1572B6)&nbsp;
![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git)&nbsp;
![GitHub](https://img.shields.io/badge/-GitHub-05122A?style=flat&logo=github)&nbsp;
![Visual Studio Code](https://img.shields.io/badge/-Visual%20Studio%20Code-05122A?style=flat&logo=visual-studio-code&logoColor=007ACC)&nbsp;


1. Flex.
```css
.kaufman {
  display: flex;
  flex-direction: column;
  align-items: center;
}
  ```
2. BEM.
```html
<div class="footer__columns">
        <div class="footer__column footer__column_content_copyright">
          <a href="index.html" class="logo logo_place_footer"></a>
          <p class="footer__author">&copy;2021. Seva Markov</p>
        </div>
  ```
4. HTML.
```html
     <section class="video">
        <h2 class="section-title">Видео нa TED</h2>
        <p class="section-subtitle">Для тех, кто любит прокрастинировать</p>
        <div class="video__iframes">
          <iframe class="video__iframe" src="https://www.youtube.com/embed/arj7oStGLkU" allowfullscreen>
          </iframe>
          <iframe class="video__iframe" src="https://www.youtube.com/embed/5MgBikgcWnY" allowfullscreen>
          </iframe>
        </div>
      </section>
  ```
6. CSS.
```css
@keyframes rotation {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}

.rotation {
  animation: rotation 20s infinite linear;
}

  ```
  
    ## Инструкция по установке:

Клонировать репозиторий:

`
git clone https://github.com/SevaMarkov88/how-to-learn.git
`

