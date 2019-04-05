# optionals.org

A simple cheat sheet for Swift Optionals. 

## Contributions

[Optionals.org](https://www.optionals.org) was designed to make contributing easy, you can send a pull request or create an issue.

## Pull Requests

### Headings

The site uses `h2` tags as section headings and `h3` headings for optional subheadings. Headings are lowercase. 

Example:
```html
<h2>guard</h2> 
<h3>optional subheading for guard</h3>
```


### Code Snippet

The site uses [Splash](https://github.com/JohnSundell/Splash) for syntax highlighting. 

Simply use [Splash](https://github.com/JohnSundell/Splash) or [splash.rambo.codes](https://splash.rambo.codes) to create the html code. 

For example:

**Splash Command**

```console
swift run SplashHTMLGen "guard let value = optional else { return }"
```

**Generated HTMTL**

```html
<span class="keyword">guard let</span> value = optional <span class="keyword">else</span> { <span class="keyword">return</span> }
```

### Final Result

```html
<h2>guard</h2> 
<span class="keyword">guard let</span> value = optional <span class="keyword">else</span> { <span class="keyword">return</span> }
```


Note: Use `&nbsp;&nbsp;` for indent spacing. 