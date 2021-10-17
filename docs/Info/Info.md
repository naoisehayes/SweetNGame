title: Website and Info
description: Information on the website.

![](https://fontmeme.com/permalink/211008/eefe45107b1d0bb6ef25810f3cbb3e4e.png)

This website is made using [MkDocs](https://www.mkdocs.org/) with a custom theme. Site is hosted on [CloudFlare Pages](https://pages.cloudflare.com/) and has a custom domain with [SSL](https://www.ssl.com/faqs/faq-what-is-ssl/) using [Cloudflare](https://www.cloudflare.com/). Source code for the website can be found on [GitHub](https://github.com/naoisehayes/SweetNGame).

The site supports Dark mode and Amoled (Black) mode by pressing the 'moon' icon in the corner.

The site supports [HLJS](https://highlightjs.org/):

```js
const currentTheme = localStorage.getItem("theme");
function switchTheme() {
  if (document.documentElement.getAttribute("data-theme") === "dark") {
    document.documentElement.setAttribute("data-theme", "light");
    localStorage.setItem("theme", "light");
  } else {
    document.documentElement.setAttribute("data-theme", "dark");
    localStorage.setItem("theme", "dark");
  }
}
if (currentTheme) {
        document.documentElement.setAttribute("data-theme", currentTheme);
        if (currentTheme === "dark") {
                document.documentElement.setAttribute("data-theme", "dark");
        }
}
```
