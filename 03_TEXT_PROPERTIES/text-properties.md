## CSS Text Properties

Text is more than just words on a screen; it's a crucial element for conveying information, guiding users, and shaping the overall user experience. CSS (Cascading Style Sheets) provides a plethora of text properties that enable designers and developers to manipulate text in diverse ways, from adjusting its appearance to enhancing its readability and accessibility. In this comprehensive guide, I'll explore the myriad CSS text properties and how they can be leveraged to create visually stunning and user-friendly web typography.


## Font Properties Overview

- `font-family`: Specifies the font family for text.

- `font-size`: Sets the size of the font.

- `font-weight`: Determines the thickness or boldness of the font.

- `font-style`: Specifies the style of the font (italic, oblique, normal).



## Font Family

```
selector {
    font-family: family-name;
}
```

There are two types of font family properties.

- **Generic Family:** : `serif`, `sans-serif`, `monospace`, `cursive`, `fantasy`.

- **Specific Family**: Specific font names like `Times New Roman`, `Arial`, `Courier New`.



### Specific Font Families

- Provide a specific font name enclosed in quotes.

- Use commas to list multiple fonts. The browser will try to apply the first font and move to the next if unavailable.

```
body {
    font-family: "Arial", sans-serif;
}
```


### Google Fonts

(Google Fonts)[https://fonts.google.com/] offer a vast collection of free, open-source fonts that can be easily embedded into web pages.


### Custom Fonts

You can use @font-face rule to specify custom fonts hosted on your server. Check example below : 

```
@font-face {
  font-family: myFirstFont;
  src: url(sansation_light.woff);
}
```


## Font Stylization

- **font-weight** : Thickness of the characters. Values can be `normal`, `bold`, `bolder`, `lighter`, or `a numeric value (100-900)`.

- **font-style** : Italicizing or normalizing the font. Values can be `normal`, `italic`, or `oblique`.


## Font Size and Line Height

- **font-size**: Sets the size of the font

- **line-height**: Sets the height of the line boxes within an element.


## Best Practices

- Use a combination of generic and specific font families for robust font fallbacks.

- Optimize loading times by selecting a minimal number of font families.

- Consider the readability and aesthetics of your chosen font family for your website's design.
