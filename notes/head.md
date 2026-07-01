# HTML Document Structure

---

# <!DOCTYPE html>

## What is it?
- A Document Type Declaration (DTD).
- It is **not** an HTML tag.
- It tells the browser that this document uses **HTML5**.

## Why do we use it?
- To make the browser render the webpage using **Standards Mode**.
- To prevent the browser from entering **Quirks Mode (Compatibility Mode)**.

## Syntax

```html
<!DOCTYPE html>
```

## Benefits
- Enables HTML5 standards.
- Prevents unexpected HTML/CSS behavior.
- Ensures consistent rendering across modern browsers.

## Example

```html
<!DOCTYPE html>
<html>
...
</html>
```

## Interview Answer
`<!DOCTYPE html>` is a document type declaration, not an HTML tag. It tells the browser that the document uses HTML5 and should be rendered in Standards Mode. Without it, the browser may use Quirks Mode (Compatibility Mode).

---

# <html lang="en">

## What is it?
- The root element of every HTML document.
- All HTML elements are placed inside this tag.

## Why do we use it?
- It wraps the entire webpage.
- The `lang` attribute tells the browser the language of the document.

## Syntax

```html
<html lang="en">
...
</html>
```

## Attributes

### lang
- Specifies the language of the webpage.
- Example:
  - `en` → English
  - `bn` → Bangla
  - `fr` → French

## Benefits
- Helps screen readers.
- Improves accessibility.
- Helps spell checking.
- Helps translation.
- Improves SEO.

## Example

```html
<html lang="en">
```

## Interview Answer
The `<html>` tag is the root element of an HTML document. The `lang` attribute specifies the language of the webpage, which helps accessibility, translation, spell checking, and SEO.

---

# <head>

## What is it?
- The `<head>` element contains metadata about the webpage.
- The content inside `<head>` is generally **not visible** on the webpage.

## Why do we use it?
- To provide information about the document.
- To include resources like CSS, fonts, icons, and metadata.

## Syntax

```html
<head>
    ...
</head>
```

## Common Elements Inside `<head>`
- `<title>`
- `<meta>`
- `<link>`
- `<style>`
- `<script>`

## Benefits
- Improves SEO.
- Stores page information.
- Loads external resources.
- Configures browser behavior.

## Example

```html
<head>
    <meta charset="UTF-8">
    <title>My Website</title>
</head>
```

## Interview Answer
The `<head>` element contains metadata about the webpage such as the title, meta tags, CSS files, favicon, and other information that is not displayed directly on the page.

---

# <meta charset="UTF-8">

## What is it?
- A meta tag that defines the character encoding of the webpage.

## Why do we use it?
- To tell the browser how to decode and display text correctly.

## Syntax

```html
<meta charset="UTF-8">
```

## Benefits
- Supports almost all languages.
- Displays special characters correctly.
- Prevents encoding issues.

## Example

```html
<meta charset="UTF-8">
```

## Interview Answer
`<meta charset="UTF-8">` specifies the character encoding of the document. UTF-8 supports almost all languages and special characters, ensuring text is displayed correctly.

---

# <meta name="viewport" content="width=device-width, initial-scale=1.0">

## What is it?
- A meta tag that controls how a webpage is displayed on different devices.

## Why do we use it?
- To make webpages responsive on mobile, tablet, and desktop devices.

## Syntax

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

## Attributes

### width=device-width
- Sets the page width equal to the device's screen width.

### initial-scale=1.0
- Sets the initial zoom level to 100%.

## Benefits
- Makes responsive design work correctly.
- Prevents unwanted zooming.
- Improves mobile user experience.

## Example

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

## Interview Answer
The viewport meta tag makes webpages responsive. `width=device-width` matches the page width to the device width, and `initial-scale=1.0` sets the initial zoom level to 100%.

---

# <title>

## What is it?
- Defines the title of the webpage.

## Why do we use it?
- To give the webpage a meaningful title.

## Syntax

```html
<title>My Website</title>
```

## Benefits
- Appears on the browser tab.
- Appears in search engine results.
- Used when bookmarking a page.
- Improves SEO.

## Example

```html
<title>Portfolio Website</title>
```

## Interview Answer
The `<title>` tag defines the title of the webpage. It appears in the browser tab, search engine results, and bookmarks, making it important for both users and SEO.