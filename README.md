# 🛍️ Product Page Design

A responsive and interactive **Product Page Design** that showcases a product gallery, dynamic image switching, and customizable options for size, color, and quantity. This project provides a sleek and modern design perfect for e-commerce applications.

---

## Features
- 🖼️ **Product Image Gallery:** Switch between multiple product images with dynamic button controls.
- 🎨 **Customizable Options:**
  - **Size Selector:** Choose from multiple size options (S, M, L, XL, XXL).
  - **Color Selector:** Select the desired product color with visual indicators.
  - **Quantity Selector:** Input the desired product quantity.
- 💻 **Responsive Design:** Works seamlessly on desktops, tablets, and mobile devices.
- 🛒 **Buy Now Button:** Direct call-to-action button for purchasing the product.
- ✨ **Modern Aesthetics:** Neumorphic design with smooth hover effects and color-coded selections.

---

## Technologies Used
- 🎨 **HTML:** Provides the structure for the product gallery, details, and form inputs.
- 🎨 **CSS:** Styles the product page with responsive layouts, modern colors, and animations.
- ✨ **JavaScript:** Implements dynamic image switching and interaction logic.

---

## How to Use

1. **Browse the Product:**
   - View the product image in the gallery.
   - Click on the gallery controls to switch between images.

2. **Customize the Product:**
   - Select a size by clicking the desired option.
   - Pick a color from the color palette.
   - Enter the desired quantity in the quantity input field.

3. **Purchase the Product:**
   - Click the **Buy Now** button to proceed with the purchase.

4. **Responsive Design:**
   - The page is optimized for all devices, ensuring a seamless shopping experience.

---

## Key Code Snippets

### JavaScript for Image Switching
```javascript
let productImg = document.getElementById("productImg");
let btn = document.getElementsByClassName("btn");

btn[0].onclick = function() {
    productImg.src = "images/image1.png";
    for (bt of btn) {
        bt.classList.remove("active");
    }
    this.classList.add("active");
};
btn[1].onclick = function() {
    productImg.src = "images/image2.png";
    for (bt of btn) {
        bt.classList.remove("active");
    }
    this.classList.add("active");
};
btn[2].onclick = function() {
    productImg.src = "images/image3.png";
    for (bt of btn) {
        bt.classList.remove("active");
    }
    this.classList.add("active");
};
```
## Demo.gif

