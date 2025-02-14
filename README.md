# Assessment Skill 3 Level 1: Flexbox, Accessibility and SEO
Below is the basic HTML & CSS for Accessibility and SEO. Please read and improve the website related to Flexbox layout, Accessibility and SEO.

---

## Basic HTML & CSS for Accessibility and SEO

SEO (Search Engine Optimization) helps websites rank higher on search engines like Google. Proper HTML and CSS structure play an important role in making your site SEO-friendly. Here’s a beginner-friendly guide:

---

### **1. HTML Best Practices for SEO**

### **a) Use Semantic HTML**

Semantic tags improve accessibility and SEO by helping search engines understand your content.

✅ **Good Example:**

```html
<header>
    <h1>Welcome to My Website</h1>
    <nav>
        <ul>
            <li><a href="/about">About Us</a></li>
            <li><a href="/services">Services</a></li>
            <li><a href="/contact">Contact</a></li>
        </ul>
    </nav>
</header>

<main>
    <article>
        <h2>Best Practices for SEO</h2>
        <p>SEO helps websites rank higher on search engines...</p>
    </article>
</main>

<footer>
    <p>&copy; 2024 My Website</p>
</footer>
```

🚫 **Avoid using non-semantic elements like**:

```html
<div id="header">...</div>
<div id="footer">...</div>
```

(Search engines may not properly understand the content structure.)

---

### **b) Use Proper Headings (h1-h6)**

Each page should have **one `<h1>` tag** for the main topic and use `<h2>`, `<h3>`, etc., for subheadings.

✅ **Good Example:**

```html
<h1>Top 10 Web Development Tips</h1>
<h2>1. Use Semantic HTML</h2>
<h3>Why Semantic Tags Matter</h3>
```

🚫 **Avoid:**

```html
<h3>Main Title</h3>
<h1>Subheading</h1>
```

(Search engines may misinterpret the structure.)

---

### **c) Meta Tags for SEO**

Meta tags provide important information to search engines.

✅ **Example:**

```html
<head>
    <title>Best SEO Tips for Beginners | My Website</title>
    <meta name="description" content="Learn the best SEO tips for optimizing your website with HTML and CSS.">
    <meta name="keywords" content="SEO, HTML, CSS, Web Optimization">
    <meta name="author" content="John Doe">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
```

**Key Meta Tags:**

- **`<title>`**: The page title (appears on Google search results).
- **`<meta name="description">`**: A short summary (recommended: 150-160 characters).
- **`<meta name="keywords">`**: Not as important today but still useful.
- **`<meta name="viewport">`**: Makes your site responsive for mobile users.

---

### **2. CSS Best Practices for SEO**

CSS does not directly affect SEO, but it improves **user experience (UX)**, which impacts rankings.

### **a) Mobile-Friendly Design (Responsive)**

Google ranks mobile-friendly sites higher.

✅ **Example (CSS for Mobile Responsiveness):**

```css
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

img {
    max-width: 100%;
    height: auto;
}

@media (max-width: 768px) {
    nav ul {
        display: block;
    }
}
```

---

### **b) Optimize Page Load Speed**

Fast websites rank better. Reduce CSS file size and avoid unnecessary animations.

✅ **Tips:**

- **Use external CSS instead of inline CSS** (`<link rel="stylesheet" href="styles.css">`)
- **Minify CSS** (remove spaces/comments using tools like [CSS Minifier](https://cssminifier.com/))
- **Use CSS Sprites** (combine images into one file to reduce HTTP requests)

---

### **c) Use Alt Text for Images**

Google can’t "see" images, so use `alt` attributes to describe them.

✅ **Example:**

```html
<img src="seo-tips.jpg" alt="SEO Tips for Better Rankings">
```

🚫 **Avoid:**

```html
<img src="seo-tips.jpg">
```

(This does not provide context to search engines.)

---

### **3. Additional SEO Tips**

✔ Use **clean and readable URLs** (`example.com/seo-tips` instead of `example.com/page?id=123`).

✔ Add **internal links** (link to your own pages).

✔ Create **sitemaps** (`sitemap.xml`) for search engines.

✔ Optimize page speed with **lazy loading** (`loading="lazy"` on images).

---

### **Conclusion**

By following these **basic HTML and CSS SEO practices**, you improve your site's visibility and user experience