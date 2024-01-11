# Tailwind CSS

## What is Tailwind CSS?

    - Tailwind is a CSS framework that uses low-level "utility" classes to create layouts. This is know as a utility-first framework.
    - Traditional CSS frameworks like Bootstrap use classes that are directly correlated to components (eg.Alerts, Navbars). Tailwind uses classes as utilities to put together to build your own custom components.

## What are utility classes & their advantage?

    - Utility classes are simple HTML classes typically scoped to a single and specific CSS property.
    - For Eg.

```html
<div class="max-w-xl mx-auto p-1">
    <h2 class="text-2xl font-bold mb-2">Hello Wolrd</h2>
</div>
```

    - Named according to their purpose 
    - Easy to understand and remember
    - You know exactly what it does
    - No naming inconsistenties
    - Allows for very fast layout creation and testing

## How is Tailwind Different From Bootsrap

### Tailwind CSS
    - Newer framework that is gaining popularity 
    - Low-level classes for fast UI development
    - More flexibility and uniqueness
    - Customizable with directives & functions 
    - You need to know quite a bit about CSS
    - HTML usually has a lot of classes

### Boostrap 
    - Popular framework that has been around a while
    - High-level pre-designed components 
    - Some Boostrap sites looks very similar 
    - Customizable through Sass
    - Easier for beginners
    - Higher level components usually means less classes

## Responsive Classes & State Classes 
    - Tailwind has conditional class naming for breakpoints as well as states such as hover, focus, etc.

```html
<div class="flex flex-col md:flex-row">
<div><a href="#" class="hover:text-blue-500">Item 1</a></div> 
<div><a href="#" class="hover:text-blue-500">Item 1</a></div> 
</div>
```



## Understanding Tailwind CSS Utilities

In Tailwind CSS, a **utility** is a specific, single-purpose class that provides styling or functionality. Rather than writing custom CSS rules, Tailwind offers a set of pre-defined utility classes that you can directly apply in your HTML.

For instance, instead of creating a custom CSS rule for a button:

```css
.button {
  padding: 8px 16px;
  background-color: #3490dc;
  color: #ffffff;
  border-radius: 4px;
  cursor: pointer;
}
```
In Tailwind CSS, you can achieve the same styling using utility classes in your HTML:

```html
<button class="p-2 px-4 bg-blue-500 text-white rounded cursor-pointer">Click me</button>
```

Here, each class (p-2, px-4, bg-blue-500, etc.) corresponds to a specific style defined by Tailwind. This approach facilitates quick and modular styling without the need for extensive custom CSS, promoting efficient and maintainable development.


## Example 1
Go to example 1 [Example 1 - Utility First](01-utility-first/index.html)
    - creating a alert dailouge box similar to css with the use of tailwind CSS


## Example 2
Go to example 2 [Example 2 - Colors](02-colors/index.html)
    - Exploring different colors available in Tailwind CSS

## Example 3
Go to example 3 [Example 3 - Containers & Spacing](03-container-spacing/index.html)
    - Exploring different size and Spacing values for containers in Tailwind CSS

## Example 4
Go to example 4 [Example 4 - Typography](04-typography/index.html)
    - Exploring different size, font-family, font-weight, alignment, spacing, decoration and style of typography in Tailwind CSS

## Example 5
Go to example 4 [Example 5 - Sizing](05-sizing/index.html)
    - Exploring different width and height classes in Tailwind CSS

## Example 6
Go to example 6 [Example 6 - layout and positions](06-layout-position/index.html)
    - Exploring different layout and position classes in Tailwind CSS

## Example 7
Go to example 7 [Example 7 - backgrounds and shadows](07-backgrounds-shadows/index.html)
    - Exploring background,images and shadaws classes in Tailwind CSS

## Example 8
Go to example 8 [Example 8 - borders](08-borders/index.html)
    - Exploring borders classes in Tailwind CSS

## Example 9
Go to example 9 [Example 9 - filters](09-filters/index.html)
    - Exploring filters classes like blur, brightness, contrast, grayscale, invert and hue rotate in Tailwind CSS

## Example 10
Go to example 10 [Example 10 - interactivity](10-interactivity/index.html)
    - Exploring interactivity classes for hover, active, present state, pseudo classes, cursor, user select, etc in Tailwind CSS

## Example 11
Go to example 11 [Example 11 - breakpoints](11-breakpoints/index.html)
    - exploring breakpoints for responsive layouts in Tailwind CSS
## For VSCODE settings
    - cmd+ shift + p --> Search settings.json 