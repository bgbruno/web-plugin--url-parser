# js-url-parser

### Usage

input
```html
<script src="url-parser.js"></script>
```
```js
console.log(parseURL('#'));
console.log(parseURL(document.location.href));
console.log(parseURL('https://console.webcloud.io/index.html'));
```

output
```
absoluteUrl: "/index.html"
file:        "index.html"
hash:        ""
domainHost:  "console.webcloud.io",
domain:      "webcloud.io"
domainTld:   "io"
params:      Object
path:        "/index.html"
pathName:    "/index.html"
port:        ""
protocol:    "https"
query:       ""
relative:    "/index.html"
segments:    Array(9)
source:      "https:// ... /login.html"
```
