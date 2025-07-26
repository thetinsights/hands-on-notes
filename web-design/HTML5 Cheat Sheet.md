### Document Structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Document</title>
</head>
<body>

</body>
</html>
```

### Semantic Elements

| Element        | Description                       |
| -------------- | --------------------------------- |
| `<header>`     | Page or section header            |
| `<nav>`        | Navigation links<br>              |
| `<main>`       | Main content of the document<br>  |
| `<article>`    | Independent content block<br>     |
| `<section>`    | Group of related content<br>      |
| `<aside>`      | Sidebar or complementary info<br> |
| `<footer>`     | Page or section footer<br>        |
| `<figure>`     | Container for media/illustration  |
| `<figcaption>` | Caption for `<figure>`            |
| `<mark>`       | Highlighted/marked text           |
| `<time>`       | Date or time                      |
### Text Formatting

| Tag            | Description               |
| -------------- | ------------------------- |
| `<h1>`–`<h6>`  | Headings                  |
| `<p>`          | Paragraph                 |
| `<br>`         | Line break                |
| `<hr>`         | Horizontal line           |
| `<strong>`     | Strong importance         |
| `<em>`         | Emphasis                  |
| `<b>`          | Bold (no importance)      |
| `<i>`          | Italic (no importance)    |
| `<u>`          | Underline                 |
| `<small>`      | Smaller text              |
| `<sup>`        | Superscript               |
| `<sub>`        | Subscript                 |
| `<code>`       | Inline code               |
| `<pre>`        | Preformatted text         |
| `<blockquote>` | Quoted content            |
| `<abbr>`       | Abbreviation (with title) |
### Links & Anchors

```html
<a href="https://example.com" target="_blank" rel="noopener">Visit</a>
```

|Attribute|Purpose|
|---|---|
|`href`|Link target|
|`target`|`_blank`, `_self`, etc.|
|`rel`|Relationship (e.g. `noopener`)|
|`download`|Download linked file|
### Images & Media

```html
<img src="img.jpg" alt="Description" width="300" loading="lazy" />
<video controls>
  <source src="video.mp4" type="video/mp4" />
</video>
<audio controls>
  <source src="audio.mp3" type="audio/mpeg" />
</audio>
```

### Lists

#### Unordered List

```html
<ul>
  <li>Item</li>
</ul>
```

#### Ordered List

```html
<ol>
  <li>Item</li>
</ol>
```

#### Definition List

```html
<dl>
  <dt>Term</dt>
  <dd>Definition</dd>
</dl>
```

### Tables

```html
<table>
  <thead>
    <tr><th>Header</th></tr>
  </thead>
  <tbody>
    <tr><td>Data</td></tr>
  </tbody>
</table>
```

### Forms

```html
<form action="/submit" method="POST">
  <input type="text" name="username" required />
  <input type="email" name="email" />
  <input type="password" name="password" />
  <input type="submit" value="Submit" />
</form>
```

### Input Types (HTML5)

- `text`, `email`, `password`, `number`, `tel`, `url`, `search`
    
- `checkbox`, `radio`, `range`, `color`, `file`, `hidden`
    
- `date`, `datetime-local`, `month`, `week`, `time`

### Common Attributes

|Attribute|Description|
|---|---|
|`required`|Makes field mandatory|
|`placeholder`|Hint text|
|`readonly`|Read-only input|
|`disabled`|Disables field|
|`maxlength`|Maximum characters allowed|
|`pattern`|RegEx pattern to match|

### Input Elements

```html
<select>
  <option value="1">One</option>
</select>

<textarea rows="4" cols="30"></textarea>

<button type="button">Click</button>
```

### APIs (Basic HTML5)

|API|Description|
|---|---|
|Geolocation|Get user’s location|
|Drag and Drop|Drag files or items|
|Web Storage|LocalStorage, SessionStorage|
|Web Workers|Multithreading support|
|Canvas API|Drawing 2D graphics|
|Audio/Video API|Control media elements|

### Global Attributes
These can be used on most elements:

|Attribute|Description|
|---|---|
|`class`|CSS class|
|`id`|Unique identifier|
|`style`|Inline CSS|
|`title`|Tooltip text|
|`lang`|Language (e.g., `en`)|
|`dir`|Text direction (`ltr`, `rtl`)|
|`data-*`|Custom data attributes|
|`hidden`|Hide element|
|`tabindex`|Keyboard navigation order|
|`accesskey`|Shortcut key for accessibility|
### Meta Tags (SEO & Mobile)

```html
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<meta name="description" content="Page Description" />
<meta name="author" content="Your Name" />
<meta name="robots" content="index, follow" />
```

### 💡 Tips

- Always use `<!DOCTYPE html>`
    
- Use semantic tags for accessibility and SEO
    
- Use `aria-*` attributes for assistive technologies
    
- Prefer `loading="lazy"` on images
    
- Group and structure content with `<section>` and `<article>`
    
- Use HTTPS and validate your HTML (W3C Validator)
