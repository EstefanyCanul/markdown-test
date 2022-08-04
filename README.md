<!-- Headings -->

# my title
## my title h2
### my title h3
#### my title h4
#### my title h5
##### my title h6

<!-- Italic -->
this is an *italic* text

<!-- Storng -->
this is an **italic** text

<!-- Strinkethrough -->
este es un ~~texto~~ tachado

<!-- UL -->
* Apple
    * Apple 2
* Orange
    * asdasdasd
* etc

1. Apple
    * 1.1 Apple 2
2. Orange
3. etc

[faztweb.com](https://www.faztweb.com)

[faztweb.com](https://www.faztweb.com "asdasdasdas")

> this is a quote

---
___

`console.log('Hello World')`

```javascript
const mongoose = requiere('mongoose');

mongoose.set('useFindAndModify', false);
mongoose.connect('mongodb://localhost/node-nodes-db', {
    useCreateIndex: true,
    useNewUrlParser: true,
})
    .then(db => console.log('DB is connected'))
    .catch(err => console.error(err))
```

```python
print("Hello World")
```

```html
<h1>Hello World</h1>
```

| Tables        | Are           | Cool      |
| --------      | :--------:    | --------: |
| col 3 is      | right-aligned |     $1600 |
| col 2 is      | centered      |       $12 |
| zebra stripes | are neat      |        $1 |

![visual studio code logo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/2048px-Visual_Studio_Code_1.35_icon.svg.png )

![visual studio code logo](vscode.png "vscode logo")

<!-- GitHub Markdown -->
* [x] Task 1
* [] Task 1
* [] Task 1
* [x] Task 1