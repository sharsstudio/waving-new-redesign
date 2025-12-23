# waving-new-redesign / New Wave GmbH - E-Commerce Redesign
Re-design of the UI/UX for a B2B-Website using a new CI/CD which includes new logo, new colors and new fonts. The new colors were chosen with the purpose to reach a better look and feel on the website and making the user experience a better one.
## 🎨 Design System & Identity
To maintain the visual consistency of "New Wave," the following style guidelines were implemented in the CSS:

**New Color Palette (RGB references):**
* `#002b49` (Primary Navy)
* `#8b734e` (Gold Accent)
* `#dbd9cc` (Neutral Beige)
* `#f3f3f1` (Background Light)

** New Typography:**
* Headings: `Source Serif Pro` (Serif)
* Body/UI: `Futura` / `Century Gothic` (Sans-serif)

## 💡 The Challenge (Problem Solving)
The original design lacked visual feedback (responsiveness) and did not reflect the brand's elegance.

**Objectives:**
1.  Create a functional slider using only HTML/CSS -> the reason: We have limited options since we are limited to use some blocks from CMS-Optimizely so I am trying to get the best out of it.
2.  Ensure corporate colors have sufficient contrast for accessibility.
3.  Improve visual hierarchy by combining Serif and Sans-serif fonts.

## 🛠️ Technical Solution
I used **CSS Grid and Flexbox** for the layout, avoiding heavy frameworks to improve load speed. I implemented CSS variables (`:root`) to manage corporate colors efficiently.

```css
:root {
  --primary-color: #002b49;
  --accent-color: #8b734e;
  --font-serif: 'Source Serif Pro', serif;
}
