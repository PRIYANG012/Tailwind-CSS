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




## For VSCODE settings
    - cmd+ shift + p --> Search settings.json 