# Tobis Rezeptbuch

---

This repository is a collection of recipes which I like. I either figured them out by myself or I got them from other people (shoutout especially to my mum and my grandma).

I want to expand this collection only by myself, so recipe pull requests are quite unnnessesary, but for some technical improvements, feel free to create one.

As you can see, all contents are in German and so it shall remain.

Shoutout to [Marie](https://github.com/NyCodeGHG) who did all the fancy CI stuff for me.

All recipes are licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

## Build

I use [mdbook](https://github.com/rust-lang/mdBook) for building the website and generating a printable PDF version of the whole book. For PDF generation, make sure you also have the [mdbook-pdf](https://github.com/HollowMan6/mdbook-pdf) package installed.

While developing, you can start a live server using the following command:

```
mdbook serve
```

For building the actual website, including the PDF, use:

```
mdbook build
```
