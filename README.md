
# **HTML Tags & Usage Guide**  

## **Introduction**  
This repository contains various HTML-only projects demonstrating different HTML tags and their usage in structuring web pages.  

## **Basic HTML Structure**  
Every HTML document follows this basic structure:  
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My HTML Project</title>
</head>
<body>
    <h1>Welcome to My HTML Repository</h1>
</body>
</html>
```

---

## **Commonly Used HTML Tags**  

### **1. Document Structure Tags**  
- `<!DOCTYPE html>` – Defines the document type.  
- `<html>` – The root element of an HTML page.  
- `<head>` – Contains metadata, title, and links to styles/scripts.  
- `<body>` – Contains the visible content of the webpage.  

### **2. Text Formatting Tags**  
- `<h1> to <h6>` – Headings (largest to smallest).  
- `<p>` – Paragraphs.  
- `<b>`, `<strong>` – Bold text.  
- `<i>`, `<em>` – Italic text.  
- `<u>` – Underlined text.  
- `<mark>` – Highlighted text.  
- `<small>` – Small text.  
- `<sup>` / `<sub>` – Superscript and subscript.  
- `<br>` – Line break.  
- `<hr>` – Horizontal rule (divider).  

### **3. Lists**  
- **Ordered List:**  
  ```html
  <ol>
      <li>Item 1</li>
      <li>Item 2</li>
  </ol>
  ```
- **Unordered List:**  
  ```html
  <ul>
      <li>Item 1</li>
      <li>Item 2</li>
  </ul>
  ```
- **Description List:**  
  ```html
  <dl>
      <dt>Term</dt>
      <dd>Definition</dd>
  </dl>
  ```

### **4. Links & Navigation**  
- **Hyperlink:**  
  ```html
  <a href="https://www.example.com">Visit Example</a>
  ```
- **Open link in new tab:**  
  ```html
  <a href="https://www.example.com" target="_blank">Open in new tab</a>
  ```
- **Email Link:**  
  ```html
  <a href="mailto:example@email.com">Send Email</a>
  ```

### **5. Images & Media**  
- **Image:**  
  ```html
  <img src="image.jpg" alt="Description" width="300">
  ```
- **Audio:**  
  ```html
  <audio controls>
      <source src="audio.mp3" type="audio/mpeg">
  </audio>
  ```
- **Video:**  
  ```html
  <video controls width="400">
      <source src="video.mp4" type="video/mp4">
  </video>
  ```

### **6. Tables**  
```html
<table border="1">
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>John</td>
        <td>25</td>
    </tr>
</table>
```

### **7. Forms & Input Fields**  
```html
<form action="submit.php" method="POST">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email">
    
    <button type="submit">Submit</button>
</form>
```

### **8. Semantic Elements**  
- `<header>` – Defines the header section.  
- `<nav>` – Navigation menu.  
- `<section>` – Section of content.  
- `<article>` – Standalone article.  
- `<aside>` – Sidebar content.  
- `<footer>` – Footer section.  

### **9. Other Important Tags**  
- `<iframe>` – Embeds another webpage.  
  ```html
  <iframe src="https://www.example.com" width="500" height="300"></iframe>
  ```
- `<details>` & `<summary>` – Expandable content.  
  ```html
  <details>
      <summary>Click to Expand</summary>
      <p>Hidden content here.</p>
  </details>
  ```

---

## **Contributing**  
Feel free to contribute by adding more HTML projects or improving documentation.  

## **License**  
This repository is open-source and free to use under the MIT License.  
