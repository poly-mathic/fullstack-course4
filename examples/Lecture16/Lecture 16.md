# STYLE PLACEMENT
Choice of placing syles in one place or another effects both reusability and which style declerations override others

## Inline Styling
NOT reusable, usually for testing
```html
<p style="text-align: center;">...</p>
```

## Style Tag in Head Tag
usually used to overide style sheet
```html
<style>
    h2 {color: maroon;}
</style>
```

## External Style Sheet
best practice, can apply same style to all pages in same dir
```html
<link rel="stylesheet" href="styles.css">
```


