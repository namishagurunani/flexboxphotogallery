# Flexbox Photo Gallery UI->>
![image](https://github.com/namishagurunani/flexboxphotogallery/assets/126158413/1f3271a3-ee3f-490e-96e4-701fe1df73fb)
# Explanation:
# 1. HTML Structure:
- The HTML code includes a <!DOCTYPE> declaration, opening "html" tag, "head" section, and "body" section.
- In the "head" section, there are meta tags for character encoding and viewport settings, as well as a "title" tag.
- The "link" tag includes a reference to an external CSS file named "style.css".
- Inside the "body" section, there's a header with the class "header" and a gallery div with the class "gallery".
# 2. CSS Styling:
- The * selector sets the box-sizing property to border-box for all elements, ensuring that padding and borders are included in the element's total width and height calculations.
- The overall page styling includes a sans-serif font family and a background color.
# 3. .header Class:
- .header class styles the header element.
-  It aligns text to the center, transforms text to uppercase, adds padding, sets a background color, text color, and adds a bottom border.
# 4. .gallery Class:
- .gallery class styles the gallery container.
- display: flex; makes the container a flex container, enabling flex properties to control layout.
- flex-direction: row; arranges items in a row (horizontal) direction.
- flex-wrap: wrap; allows items to wrap onto multiple lines when necessary.
- justify-content: center; centers items along the main axis.
- align-items: center; centers items along the cross-axis.
- gap: 16px; adds spacing between gallery images.
- max-width: 1400px; sets a maximum width for the gallery container.
- margin: 0 auto; centers the gallery horizontally using auto margins.
- padding: 20px 10px; adds padding to the top and bottom of the gallery.
# 5. .gallery img Class:
- .gallery img styles the gallery images within the container.
- width: 100%; ensures the images occupy the full width of their container.
- max-width: 350px; limits the maximum width of the images.
- height: 300px; sets a fixed height for the images.
- object-fit: cover; maintains the image's aspect ratio while covering the available space.
- border-radius: 10px; adds rounded corners to the images.
# 6. .gallery::after Pseudo-element:
- .gallery::after uses a pseudo-element to create additional spacing.
- content: ""; inserts an empty content element.
- width: 350px; sets a fixed width, providing extra spacing at the end of the gallery.

# Sumbission Required:
- Github Link:[click here](https://github.com/namishagurunani/flexboxphotogallery)
- Hosted Link:[click here](https://namishagurunani.github.io/flexboxphotogallery/)
- FreeCodeCamp Link:[click here](https://www.freecodecamp.org/learn/2022/responsive-web-design/learn-css-flexbox-by-building-a-photo-gallery/step-21)
- FreeCodeCamp Id:[click here](https://www.freecodecamp.org/namisha_gurunani)
