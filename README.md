
# CSS - Cascading Style Sheet

- CSS defines how HTML elements are to be displayed

**Easy Maintenance**
- To make a global change, simply change the style, and all elements in all the web pages will be updated automatically.

**CSS saves time**
- write CSS once and then reuse same sheet in multiple HTML pages. You can define a style for each HTML element and apply it to as many Web pages as you want.


## CSS Syntax

- CSS rule set consists of a selector and a declaration block.

- CSS declaration always ends with a semicolon, and declaration groups are surrounded by curly braces.

`h1{
	color:blue;
	font-size:12px;
}`

- This rule-set applies the style to all `<h1>` elements, setting the font color to blue and font size to 12 pixels.

- A CSS rule-set consists of a selector and a declaration block.A style rule is made of three parts :

`selector {property:value;}`

eg: 

```h1{color:blue;}```

## CSS Selector

1. Element Selector (tagname)
- Example: 
```h1{color:blue}```

2. ID Selector (#)
- Example: 
```#nav{color:green}```

3. Class Selector (.)
- Example: 
```.nav{color:violet}```

4. Universal Selector (*)
- Exmple: 
```*{margin: 0px;}```

5. Descendant Selector
- Example: 
```ul li{font-family:roboto;}```

6. Child Selector
- Example: 
```div > p {color:red;}```

7. Attribute Selector
- Example:
```input[type = "text"] { border: 1px solid blue;}```

8. Grouping Selector
- Example: 
```h1,h2,h3,h4,h5,h6,b{color:red;}```