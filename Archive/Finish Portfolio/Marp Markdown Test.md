---
marp: true
theme: gaia
paginate: true
footer: "Marp Features Showcase | @YourName"
backgroundColor: #f9f9f9
---

# 🌟 Welcome to Marp

Create **beautiful presentations** with simple Markdown syntax.

---

## 🛠 Features of Marp

- 🎨 **Themes**: Use predefined themes or create custom ones.
- 📄 **PDF Export**: Export presentations as PDFs or PowerPoint slides.
- ✨ **Styling**: Add custom CSS for unique layouts.
- 📊 **Diagrams**: Integrate diagrams and visuals.
- 💡 **Syntax Highlighting**: Highlight code beautifully.
- 🖼 **Backgrounds**: Add custom image or color backgrounds.

---

<!-- _class: lead -->

# 🎨 **Themes and Styling**

Change themes, add styling, and control the look and feel of your slides.

```yaml
theme: gaia
backgroundColor: #f9f9f9
footer: "Custom Theme Example"
```

---

# 🌟 Welcome to Columns in Marp

Showcasing:
- Columns of **text**
- Columns of **text and images**
- Columns of **images**

---

## 📜 Columns of Text

Using Markdown tables for text columns:

| **Column 1**            | **Column 2**           | **Column 3**            |
| ----------------------- | ---------------------- | ----------------------- |
| This is the first cell. | This is the second.    | And this is the third.  |
| More text in column 1.  | Some text in column 2. | Extra info in column 3. |

---

## 🖼 Columns of Text and Images

Combine images and text in a table:

| ![Alt Text](https://via.placeholder.com/100) | **Title**: Column 2 | ![Alt Text](https://via.placeholder.com/100) |
|---------------------------------------------|---------------------|---------------------------------------------|
| Description for image 1                     | Centered text       | Description for image 3                     |
| ![Alt Text](https://via.placeholder.com/100) | More text here      | ![Alt Text](https://via.placeholder.com/100) |

---

## 🖼 Columns of Images

Use Markdown tables to display images in columns:

| ![Image 1](https://via.placeholder.com/150) | ![Image 2](https://via.placeholder.com/150) | ![Image 3](https://via.placeholder.com/150) |
|---------------------------------------------|---------------------------------------------|---------------------------------------------|
| Caption 1                                   | Caption 2                                   | Caption 3                                   |
| ![Image 4](https://via.placeholder.com/150) | ![Image 5](https://via.placeholder.com/150) | ![Image 6](https://via.placeholder.com/150) |

---

## 🌈 Creative Column Designs

Experiment with spacing and alignment:
- Right-align images:
  - ![bg right:50%](https://via.placeholder.com/150)

---

## 🔄 Mix and Match Columns

Combine text, images, and alignment creatively:

| **Left Aligned Text**       | ![Right Aligned Image](https://via.placeholder.com/150) |
|------------------------------|--------------------------------------------------------|
| This is descriptive text for the image. |                                                |

---

## 🔗 Resources

- [Marp Official Documentation](https://marp.app/)
- [Marpit Theme Customization](https://marpit.marp.app/theme)
- [GitHub Repository](https://github.com/marp-team/marp)

---

# 🚀 Thank You!

Explore the power of columns in your Marp presentations. Any questions?

---

## 🎨 Slide with Text in Different Colors

```css
<style>
  h1 { color: #0073e6; }
  h2 { color: #e63946; font-family: "Georgia, serif"; }
  p { color: #2a9d8f; font-size: 1.2em; }
</style>
```

---
Here’s a detailed Marp Markdown example showcasing slides with **text in different colors and fonts** as well as **highlighted text**:

---

### Full Marp Markdown Example

````markdown
---
marp: true
theme: gaia
paginate: true
footer: "Marp Text Styles Showcase | @YourName"
backgroundColor: #f9f9f9
---

# 🌈 Marp Text Styles Showcase

Explore:
- **Text in different colors and fonts**
- **Highlighted text**
- **Creative designs**

---

## 🎨 Slide with Text in Different Colors

```css
<style>
  h1 { color: #0073e6; }
  h2 { color: #e63946; font-family: "Georgia, serif"; }
  p { color: #2a9d8f; font-size: 1.2em; }
</style>
````

### Text Example:

- **Heading in Blue** (h1)
- **Heading in Red with Georgia font** (h2)
- **Paragraph in Green** (p)

---

## 🌟 Highlighted Text

> **Highlights** can draw attention to important points:
> 
> - **Default Highlight**: Highlighted like this.
> - `Inline Code Highlight`: Use backticks for inline highlighting.
> - **Custom Background**: Use a callout for a more impactful style.

---

## 🔍 Inline Custom Styles for Highlighting

Use Marp syntax:

- **Bold Text**
- _Italicized Text_
- Custom Highlighted Text

---

## ✨ Font Styling

```css
<style>
  h1 { font-family: "Times New Roman, serif"; font-size: 2.5em; }
  h2 { font-family: "Arial, sans-serif"; font-size: 2em; font-weight: bold; }
  p { font-family: "Courier New, monospace"; font-size: 1.5em; }
</style>
```

- **Heading 1**: Times New Roman
- **Heading 2**: Arial Bold
- **Paragraph**: Courier New

---

## 💡 Highlighted Sections Example

> [!INFO] **This is an information callout**  
> Use callouts to highlight key sections effectively.

> [!WARNING] **Warning Highlight**  
> Make critical warnings stand out with this style.

> [!SUCCESS] **Success Highlight**  
> Show success or completed sections prominently.

---

## 🎨 Multi-Colored Slide

```css
<style>
  body { background-color: #f9f9f9; }
  h1 { color: #ff5722; font-size: 2.5em; }
  h2 { color: #3f51b5; font-size: 2em; }
  p { color: #4caf50; font-size: 1.5em; }
</style>
```

- **Orange Header** (h1)
- **Blue Subheader** (h2)
- **Green Paragraph Text** (p)

---

## 🖍 Custom Highlight Examples

- **Yellow Background**: Highlighted like this.
- **Pink Background**: Highlighted like this.
- **Blue Background**: Highlighted like this.

---

## 🔗 Resources

- [Marp Official Documentation](https://marp.app/)
- [Markdown Styling in Marp](https://github.com/marp-team/marp)
- [CSS in Marp](https://marpit.marp.app/css)

---

# 🚀 Thank You!

Experiment with these text styles and make your Marp presentations visually engaging.

```

### Key Features
1. **Text in Different Colors and Fonts**:
   - Use `<style>` tags in Markdown to style specific text elements like headings, subheadings, and paragraphs.

2. **Highlighted Text**:
   - Inline CSS for highlighting text with specific background colors and rounded edges.
   - Use Marp callouts (`[!NOTE]`, `[!INFO]`, etc.) for impactful sections.

3. **Multi-Colored Slides**:
   - Experiment with custom colors for backgrounds and text.

This approach demonstrates the versatility of Marp for styling text and making presentations visually appealing. Let me know if you'd like additional features!
```


---

### **1. Text Styling (Colors and Fonts)**

In Marp, you can use inline CSS via `<style>` tags, but only certain styles are supported depending on the theme (`gaia`, `default`, `uncover`). For custom colors and fonts, here's what you can do:

```markdown
---
marp: true
theme: gaia
---

# 🌈 Text in Colors

### Default Styling
- **Bold**: `**Bold Text**`
- _Italic_: `_Italic Text_`
- **Custom Color**:
  <span style="color: #e63946;">This is red text!</span>

---

# 🖋 Fonts

<style>
h1 {
  font-family: "Georgia", serif;
  color: #2a9d8f;
}
</style>

# Heading with Custom Font

---

# 🌟 Highlighted Text

Highlight with inline styles:

- Yellow: <span style="background-color: #ffd54f; padding: 2px;">This is highlighted text</span>.
- Blue: <span style="background-color: #90caf9; color: white; padding: 2px;">Another highlight</span>.
```

---

### **2. Layouts with Columns (Text and Images)**

Marp doesn't support advanced CSS `flexbox` or `grid` layouts. Instead, you can approximate columns using **`--columns`** syntax from Marp themes.

```markdown
---
marp: true
theme: gaia
paginate: true
---

<!-- _class: split -->

# 📝 Column Layout

**Left Column**:
- Point 1
- Point 2

**Right Column**:
![Image](https://via.placeholder.com/150)

---

<!-- _class: split -->

# 🌅 Image and Text Side-by-Side

**Description**:
- Key insights
- Recommendations

**Visual**:
![Image](https://via.placeholder.com/200)
```

### **3. Callouts**

Marp doesn’t have native support for Markdown callouts (`[!NOTE]` or `[!INFO]`), but you can approximate them using bold text, emojis, or horizontal rules:

```markdown
---
marp: true
theme: gaia
---

# 💡 Highlight Section

---

> 💡 **Insight**  
> This is a key insight.

---

> ❗ **Warning**  
> Be careful with these results.
```

---

### **4. Highlighted Text**

Use `<span>` for inline highlighted text.

```markdown
---
marp: true
theme: gaia
---

# 🌟 Highlighted Text

This is <span style="background-color: #ffd700; color: black;">highlighted</span> text.

---

# 🎨 Background Color Example

This is <span style="background-color: #90caf9; color: white;">another highlighted example</span>.
```

---

### **5. How to Apply and Run**

1. **Install Marp:**
    
    - Use the [Marp for VS Code extension](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode).
    - Ensure Marp CLI is installed if you want to convert Markdown to PDF or PowerPoint.
2. **Themes:**
    
    - Use the built-in `gaia`, `default`, or `uncover` themes.
    - For custom themes, create a CSS file and reference it in your Markdown.
3. **Check for Compatibility:**
    
    - Not all HTML or CSS will work. Use Marp's built-in features (`--columns`, themes) for best results.
4. **Preview:**
    
    - Use the `Marp: Preview` command in VS Code to see live updates.

---

### Example Full Markdown Presentation

```markdown
---
marp: true
theme: gaia
---

# 🌟 Welcome to Marp!

---

# 🖍 Styling Text

This is <span style="color: #e63946;">red</span> text.  
This is <span style="background-color: #ffd54f;">highlighted</span> text.

---

# 🖼 Layouts

<!-- _class: split -->

**Text Column**:
- Insight 1
- Insight 2

**Image Column**:
![Image](https://via.placeholder.com/200)
```

### **Tips**

- Marp uses CSS features but is sandboxed, so some advanced styling won't work.
- Use Marp's built-in split and theme features instead of external CSS for consistency.

Let me know if you need further assistance!