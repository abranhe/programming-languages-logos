<p align="center">
    <br>
    <img src="src/programming-languages.gif" alt="List of programming languages logos">
    <br>
    <br>
    <br>
    <br>
    <!-- 
        Plese don't fix the world 'porgramming' it is not a typo.
        Well it is a typo but a working typo :) 
    -->
    <img src="https://cdn.abranhe.com/projects/porgramming-languages-logos/logo.svg" alt="programming gif">
    <br>
    <br>
    <b>High Resolution Programming Languages Logos</b>
    <br>
    <br>
    <a href="https://languages.abranhe.com"><code>languages.abranhe.com</code></a>
</p>

<p align="center">
    <a href="https://github.com/abranhe/programming-languages-logos/actions"><img src="https://github.com/abranhe/programming-languages-logos/workflows/publish/badge.svg" /></a>
    <a href="https://github.com/abranhe/programming-languages-logos"><img src="https://img.shields.io/npm/v/programming-languages-logos.svg?logo=npm" /></a>
	<a href="https://github.com/abranhe/programming-languages-logos/blob/master/license"><img src="https://img.shields.io/github/license/abranhe/programming-languages-logos.svg" /></a>
    <a href="https://github.com/abranhe/programming-languages-logos"><img src="https://img.shields.io/github/repo-size/abranhe/programming-languages-logos.svg?logo=github"></a>
    <br>
    <br>
    <b><a href="https://github.com/react-pll">Using React?</a></b>
    <br>
</p>

**Programming languages** are the way we developers talk with the machine, but what happens when we want to talk about them? Probably in a blog post, in a Medium story, in a presentation, or 🤔 well something else ..., **the thing** is that we want to include them in our life and the best way to do it is with a logo.

<img src="src/programming-languages.png" alt="Some programming languages logos">

This project include high resolution `.png` with transparent backgrounds programming languages logos with different dimensions and also a vector `.svg` version of them.

A complete list of the logos can be found int the [`src/`](https://github.com/abranhe/programming-languages-logos/blob/master/src) directory or in the [`src/languages.json`](https://github.com/abranhe/programming-languages-logos/blob/master/src/languages.json) file.

##### Dimensions

- `16 x 16`
- `24 x 24`
- `32 x 32`
- `48 x 48`
- `64 x 64`
- `128 x 128`
- `512 x 512`

Default logo: `2048 x 2048`

What to help? Start by reading the [contributing guidelines](https://github.com/abranhe/programming-languages-logos/blob/master/.github/contributing.md).

## Usage

###### All logos

```
$ npm install programming-languages-logos
```

You can then import the logos from `./node_modules/programming-languages-logos`.

###### Example:
 
 ```js
 import swift from 'programming-languages-logos/src/swift/swift.svg'
 ```

 Use the hosted version on
 [**jsdelivr**](https://www.jsdelivr.com/package/npm/programming-languages-logos).


###### Example:

```html
<img src="https://cdn.jsdelivr.net/npm/programming-languages-logos/src/javascript/javascript.png" height="100">
```

<img src="https://cdn.jsdelivr.net/npm/programming-languages-logos/src/javascript/javascript.png" height="100">

Otherwise [download the zip](https://github.com/abranhe/programming-languages-logos/releases/latest) from the Github releases.

We have created a simple way to use those logos in your **HTML**. First include the library & then include the `<i>` where you want it and that's it!

```html
<link href="https://languages.abranhe.com/logos.css" rel="stylesheet">
```

*Usage*

```html
<i class="programming lang-ruby"></i>
<i class="programming lang-javascript"></i>
<i class="programming lang-cpp"></i>
<i class="programming lang-typescript"></i>
<i class="programming lang-python"></i>
<i class="programming lang-kotlyn"></i>
```

*Result*

<img src="https://cdn.abranhe.com/projects/programming-languages-logos-site/example.png" alt="example" width="50%">

Search logos on [languages.abranhe.com](https://languages.abranhe.com).

###### Individual logos

```
$ npm install @programming-languages-logos/<logo>
```

Example: (Java)

*I recommend to install it as a developer dependency*:  `--save-dev`

```
$ npm install @programming-languages-logos/java --save-dev
```

### Credits

Mainly inspired by [Browser logos](https://github.com/alrra/browser-logos/). I would be imposible

### Related

- [browser-logos](https://github.com/alrra/browser-logos/): 🗂 High resolution web browser logos.
- [react-pll](https://github.com/react-pll): (`react-programming-languages-logos`) A Programming Language Logo component for React.

### License

**All logos and trademarks are the property of their respective owners!**

If you represent the entity that has the rights over a logo and you
want, for whatever reason, that logo removed from this project,
[open an issue](https://github.com/abranhe/programming-languages-logos/issues/new)
requesting its takedown and we will remove it as soon as possible.

[MIT](https://github.com/abranhe/programming-languages-logos/blob/master/license) License © [Carlos Abraham](https://github.com/abranhe)