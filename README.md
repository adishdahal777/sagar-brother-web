# HTML and CSS

## What is HTML?

**HTML (HyperText Markup Language)** is the standard language used to create the structure of web pages. It defines elements such as headings, paragraphs, images, links, tables, forms, and more.

### Basic HTML Example

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Website</title>
</head>
<body>

    <h1>Welcome to My Website</h1>
    <p>This is a paragraph written in HTML.</p>

</body>
</html>
```

### Common HTML Tags

| Tag | Description |
|------|-------------|
| `<h1>` to `<h6>` | Headings |
| `<p>` | Paragraph |
| `<a>` | Link |
| `<img>` | Image |
| `<div>` | Container |
| `<ul>` / `<ol>` | Lists |
| `<table>` | Table |
| `<form>` | Form |

---

# What is CSS?

**CSS (Cascading Style Sheets)** is used to style and design HTML elements. It controls colors, layouts, fonts, spacing, animations, and responsiveness.

### Basic CSS Example

```css
body {
    background-color: #f4f4f4;
    font-family: Arial, sans-serif;
}

h1 {
    color: red;
    text-align: center;
}

p {
    font-size: 18px;
    color: #333;
}
```

---

# Connecting CSS with HTML

There are 3 ways to use CSS in HTML:

## 1. Inline CSS

```html
<p style="color: blue;">Hello World</p>
```

## 2. Internal CSS

```html
<style>
    p {
        color: green;
    }
</style>
```

## 3. External CSS

### HTML File

```html
<link rel="stylesheet" href="style.css">
```

### CSS File (`style.css`)

```css
body {
    background: white;
}
```

---

# Complete Example of HTML + CSS

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML & CSS Example</title>

    <style>
        body {
            font-family: Arial;
            background-color: #f5f5f5;
            text-align: center;
        }

        h1 {
            color: crimson;
        }

        button {
            background: black;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
        }

        button:hover {
            background: crimson;
        }
    </style>
</head>
<body>

    <h1>Hello World</h1>
    <p>This webpage is styled using CSS.</p>

    <button>Click Me</button>

</body>
</html>
```

---

# Difference Between HTML and CSS

| HTML | CSS |
|------|-----|
| Creates structure | Adds styling |
| Defines content | Defines design |
| Uses tags | Uses selectors |
| Example: `<p>` | Example: `p { color:red; }` |

---

# Advantages of HTML and CSS

## HTML Advantages
- Easy to learn
- Builds webpage structure
- Supported by all browsers

## CSS Advantages
- Makes websites attractive
- Enables responsive design
- Reduces repeated styling
- Improves user experience

---

# Conclusion

HTML and CSS are the foundation of web development.

- **HTML** creates the structure of a webpage.
- **CSS** makes the webpage beautiful and responsive.

Together, they help developers build modern websites and web applications.
