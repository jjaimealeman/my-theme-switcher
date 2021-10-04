## My Theme Switcher

### With live updating favicon, also!

---

It seems that now just about every website has a "Theme Switcher" ability.

Well, here's my version of the same thing 😉

    SVGs were created in designer.gravit.io
        ![favicon.svg!](docs/images/favicon.svg "favicon.svg")
        ![dark.svg!](docs/images/dark.svg "dark.svg")
        ![light.svg!](docs/images/light.svg "light.svg")
        ![icon-moon.svg!](docs/images/icon-moon.svg "icon-moon.svg")
        ![icon-sun.svg!](docs/images/icon-sun.svg "icon-sun.svg")

    SVGs have been optimized using [jakearchibald.github.io/svgomg](https://jakearchibald.github.io/svgomg/).

    Original source for the theme switcher came from [Luke Lowrey](https://lukelowrey.com/css-variable-theme-switcher/).

    But I came up with the favicon switching by sourcing from Stackoverflow, CSS Tricks, and various other places.

    If you would rather use png to support older browsers, you can use https://convertio.co/svg-png/

The one thing I could NOT figure out - how to preload the appropriate favicon based on localStorage. That's why I have favicon.svg set as the default.

Here are the icons to make it easier to get started with in your project.

docs/images/favicon.svg

```
<svg xmlns="http://www.w3.org/2000/svg" style="isolation:isolate" viewBox="68 10 14 14" width="14pt" height="14pt"><circle vector-effect="non-scaling-stroke" cx="75" cy="17" r="7" fill="#A3B7CC"/><path d="M75 10c-3.863 0-7 3.137-7 7s3.137 7 7 7V10Z" fill-rule="evenodd" fill="#FFEC38"/></svg>
```

---

docs/images/dark.svg

```
<svg xmlns="http://www.w3.org/2000/svg" style="isolation:isolate" viewBox="9 8.5 14 14" width="14pt" height="14pt"><circle vector-effect="non-scaling-stroke" cx="16" cy="15.5" r="7" fill="#A3B7CC"/></svg>
```

---

docs/images/light.svg

```
<svg xmlns="http://www.w3.org/2000/svg" style="isolation:isolate" viewBox="30.686 8.5 14 14" width="14pt" height="14pt"><circle vector-effect="non-scaling-stroke" cx="37.686" cy="15.5" r="7" fill="#FFEC38"/></svg>
```

---

docs/images/icon-moon.svg

```
<svg xmlns="http://www.w3.org/2000/svg" style="isolation:isolate" viewBox="34 30 22 22" width="22pt" height="22pt"><circle vector-effect="non-scaling-stroke" cx="45" cy="41" r="11" fill="#EBEBEB"/><path d="M43.122 30.164A10.657 10.657 0 0 1 45 30c6.071 0 11 4.929 11 11s-4.929 11-11 11a10.92 10.92 0 0 1-6.752-2.323c.971.32 2.008.49 3.085.49 5.565 0 10.084-4.519 10.084-10.084 0-4.954-3.581-9.078-8.295-9.919Z" fill-rule="evenodd" fill="#A3B7CC"/><circle vector-effect="non-scaling-stroke" cx="40.708" cy="44.208" r="1.833" fill="#A3B7CC"/><circle vector-effect="non-scaling-stroke" cx="45.749" cy="38.25" r="1.375" fill="#A3B7CC"/><circle vector-effect="non-scaling-stroke" cx="39.103" cy="37.104" r="1.146" fill="#A3B7CC"/></svg>
```

---

docs/images/icon-sun.svg

```
<svg xmlns="http://www.w3.org/2000/svg" style="isolation:isolate" viewBox="39 39 22 22" width="22pt" height="22pt"><path d="M46.778 42.222h-4.556v4.556L39 50l3.222 3.222v4.556h4.556L50 61l3.222-3.222h4.556v-4.556L61 50l-3.222-3.222v-4.556h-4.556L50 39l-3.222 3.222Z" fill-rule="evenodd" fill="#FF9B07"/><circle vector-effect="non-scaling-stroke" cx="50" cy="50" r="6.806" fill="#FFEC38"/></svg>
```

---
