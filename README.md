![Image alt](https://github.com/flaain/cryptocurrency-crappo/raw/master/images/logo.svg) 
# Project: Cryptocurrency Crappo

### Preview
* Project description
* Technologies
* Links
* Screenshots of project

**Project description**

Проект представляет из себя краткий путеводитель по красивым местам России.<br>
Проект полностью адаптивен под следующие разрешения (320px, 768px, 1024px, 1280px)

**Technologies**

1. Flexbox
```css
.header{
    max-width: 1200px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
```
2. BEM
```html
<header class="header page__header">
    <a href="#" class="logo">
        <img src="images/logo.svg" alt="" class="logo__image" />
    </a>
    <nav class="header__nav">
        <ul class="header__list">
            <li class="header__item">
                <a href="#" class="header__link">Products</a>
            </li>
            <li class="header__item">
                <a href="#" class="header__link">Features</a>
            </li>
            <li class="header__item">
                <a href="#" class="header__link">About</a>
            </li>
            <li class="header__item">
                <a href="#" class="header__link">Contact</a>
            </li>
            <li class="header__item header__item_login">
                <a href="#" class="header__link header__link_login">Login</a>
            </li>
            <button class="btn header__button">Register</button>
        </ul>
    </nav>
</header>
```
3. BEM Nested
[Image alt](https://github.com/Flaain/cryptocurrency-crappo/blob/master/images/bem-nested-screenshot.png) 
4. Variables
```css
:root{
    --dark-bg: #0D0D2B;
    --blue-bg: #3671E9;
    --purple-bg: #2B076E;
    --white: #FFF;
}
```
**Links**

1. [Figma template](https://www.figma.com/file/5S2WSbEFL6awjVWJ0NWL8Q/Sprint-3_-Russia-_-desktop-mobile?node-id=28503%3A0)
2. [GitHub Pages](https://flaain.github.io/russian-travel/)
