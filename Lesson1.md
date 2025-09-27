# Lesson 1

## Learning Target
- I am learning how to use divs to create containers to group elements for styling

## Success Criteria
- I can put elements inside a ```<div>``` element with a class to group them as a unit
- I can use descendant selectors to style elements within div container
- I can use developer tools to inspect HTML and CSS structure

### Divide Up The Page
Uses ```<div>``` tags to create the following sections
- header
- hero
- products
- shop
- footer
#### Example For Header
```html
<div class="header">

</div>
```

### Add CSS Class Selectors
Add a class selector in your ```styles.css``` for each section you created
#### Example For Header
```css
.header {

}
```

### Add Header Content
Add the following content inside your header div
- An ```<h2>``` with the name of your business
- A ```<div>``` with the class ```nav```
- Inside the nav div, use ```<a>``` tags to create the following links. Use ```href="#"``` as a placeholder
    - Home
    - Products
    - Contact

### Style Header Content
Set the background color, color, font-family, and font-size for the header elements. Use descent selectors to select the elements inside the header. Keep all your header styles grouped together
#### Example
```css
.header {
  background-color: red;
  color: whitesmoke;
}

.header h2 {
  font-size: 30px;
}
```

### Add Hero Content
Add the following content inside your hero div
- An ```<h1>``` with your business name
- A ```<p>``` with a short *tagline* for your business
- An ```<a>``` with ```href="#"``` as a placeholder and the display text *Shop*

### Add Products Content
Add the following inside your products div
- A ```<div>``` with the class ```card```
- Inside card div, add the following
    - An ```<img>``` tag with one of your product images
    - A ```<p>``` tag with a short description of the product in the image
    - An ```<a>``` tag with ```href="#"``` and the display text *More info*
- Make two copies of your card div for a total of three inside the products div
- Update the images and descriptions for the second two cards

### Add Shop Content
Add the following inside your shop div
- An ```<a>``` tag with ```href="#"``` as a placeholder URL and the display text *Shop*

### Add Footer Content
Add the following inside your footer div
- A ```<p>``` tag with "```Copyright &copy *Your Name* 2025```". ```&copy``` is the character code for the copyright symbol
