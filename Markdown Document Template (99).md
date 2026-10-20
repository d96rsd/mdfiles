# BB

# Markdown Document Template

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Test Page</title>
</head>
<body>
    <h1>Hello, world!</h1>
    <p>This is an HTML test.</p>
    <a href="https://example.com">Visit example</a>
    <img src="image.png" alt="Example image">
    <button id="clickButton">Click me</button>
</body>
</html>
```
```css
/* CSS syntax highlighting test */
body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    color: #333;
    margin: 0;
    padding: 20px;
}

h1 {
    color: #0066cc;
    font-size: 2rem;
}

button:hover {
    background-color: black;
    color: white;
}

@media (max-width: 600px) {
    body {
        padding: 10px;
    }
}
```

```js
// JavaScript syntax highlighting test
const name = "Markdown";
let count = 0;

function greet(user) {
    return `Hello, ${user}!`;
}

const numbers = [1, 2, 3, 4, 5];
const doubled = numbers.map(n => n * 2);

document.querySelector("#clickButton")
    ?.addEventListener("click", () => {
        count++;
        console.log(greet(name));
        console.log("Click count:", count);
        console.log("Doubled:", doubled);
    });

if (count === 0) {
    console.log("Ready to test!");
}
```

### Get a post
GET https://jsonplaceholder.typicode.com/posts/1
Accept: application/json

### Create a post
POST https://jsonplaceholder.typicode.com/posts
Content-Type: application/json

{
  "title": "Test post",
  "body": "Testing an API request",
  "userId": 1
}
````
Testing testing
````
```
Performance
100 |             *
 80 |         *
 60 |      *
 40 |   *
 20 | *
  0 +----------------
      Jan Feb Mar Apr
```
```mermaid
xychart-beta
    x-axis [Jan, Feb, Mar, Apr]
    y-axis "Sales" 0 --> 100
    line [20, 40, 65, 90]
```
$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$
- [ ] Write a short introduction here.
- [ ] Explain the purpose of this document
- [ ] and summarize its main idea.

## 2. Image Placeholder

> Replace the example path below with the path or URL of your image.

![image](https://imglink.cc/cdn/97yBMGXAc7.png)


{%youtube jNQXAC9IVRw %}


## 3. Example Table

| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| Text     | Text     | Text     |



<iframe
  width="auto"
  height="auto"
  src="https://www.youtube.com/watch?v=jNQXAC9IVRw"
  title="YouTube video"
  frameborder="0"
  allowfullscreen>
</iframe>
## 5. Steps or Instructions

1. First, describe the initial step.
2. Next, explain what needs to happen.
3. Finally, describe the expected result.
- Note one
- Note two
- Note three

## 7. Conclusion

Summarize the main points and list any next steps.

---

*Document owner: Dusan*
*Last updated: 2026-10-20*
