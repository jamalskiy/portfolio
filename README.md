# Портфолио

### Красивый, минималистичный и доступный шаблон портфолио для разработчиков ✨.

Чтобы посмотреть сайт вживую, нажмите [  &rarr;](http://userbots.ru)

## Возможности

- Чистый, простой и современный дизайн интерфейса.
- Построен только на HTML, CSS и немного JavaScript 🔨.
- Полностью адаптивный.

### Вклад приветствуется ❤️.

## Начало работы 🚀

Вам потребуется [Git](https://git-scm.com) , установленный на вашем компьютере.
```
# Склонируйте этот репозиторий
$ git clone https://github.com/jamalskiy/portfolio
```

## Редактирование шаблона 🔨

Откройте `index.html` и заполните вашу информацию.

### Заголовок

Во всех местах, где необходимо заполнить вашу информацию, вы найдете HTML-комментарии. Как показано ниже, просто замените содержимое внутри открывающих и закрывающих тегов под комментарием на вашу информацию.
```html
    <div class="header__text-box row">
      <div class="header__text">
        <h1 class="heading-primary">
          <span>Рома Иванов</span>
        </h1>
        <!-- Напишите пару слов о себе -->
        <p>Разработчик ботов в телеграмм, основанный в Чувашии, Чебоксары.</p>
        <a href="#contact" class="btn btn--pink">Связаться</a>
      </div>
    </div>
```

### Рабочий раздел

Каждый div с классом `work__box` представляет проект, замените содержимое всех тегов информацией о ваших проектах.

```html
<div class="work__box">
            <div class="work__text">
              <h3>Шаблон портфолио</h3>
              <p>
                Бесплатный открытый исходный код портфолио для всех желающих использовать.
              </p>
              <ul class="work__list">
                <li>HTML</li>
                <li>SCSS</li>
                <li>JavaScript</li>
                <li>Parcel</li>
              </ul>

              <div class="work__links">
                <a href="https://userbots.ru" target="_blank" class="link__text">
                  Посетить сайт <span>&rarr;</span>
                </a>
                <a href="https://github.com/jamalskiy/portfolio" title="Посмотреть исходный код" target="_blank">
                  <img src="./images/github.svg" class="work__code" alt="GitHub">
                </a>
              </div>
            </div>
            <div class="work__image-box">
              <img src="./images/project-1.png" class="work__image" alt="Проект 1" />
            </div>
          </div>
```

Для изменения скриншота:
- сначала поместите изображение в `images/` папку, а затем в HTML замените имя на `src` мя вашего изображения.

- Рекомендуемый размер изображения проекта (1366 x 767 пикселей). Также убедитесь, что размер всех изображений проекта одинаковый.

```html
<img
    src="./images/name-of-your-image.png"
    class="work__image"
    alt="Project 1"
/>
```

### Раздел контактов

- Измените абзац по своему усмотрению.
- Замените адрес электронной почты на свой в `href` свойстве привязки и в тексте.

```html
  <section class="contact background-overlay" id="contact">
    <div class="row">
      <h2 class="cente-text">Связаться</h2>
      <div class="contact__info">
        <p>
          Ищете удобного бота в telegram для представления вашего продукта или бизнеса? Хотите задать вопрос? В любом случае, не стесняйтесь, свяжитесь со мной. Самый быстрый способ связаться со мной - через telegram.
        </p>
        <a href="https://t.me/abanentick" class="btn btn--pink">telegram</a>
        <a href="mailto:ska304niykobanchik@gmail.com" class="btn btn--pink">mail</a>
      </div>
    </div>
  </section>
```
