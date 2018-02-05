# SVG Animations

### **Requirement** Changing background SVG

* Background PNG is replaced in CSS with the background svg

> You have switched out the PNG with the SVG, but there is just a small problem with the path to your file. This is what's called a relative path, and it is relative to the file that is using it. In this case, styles.css is looking for the SVG, so the path has to go up one level and then over into the svg folder. To go up one level, we add two periods in front of the path. So the final path should lokk something like `../svg/background.svg` Real close though!

---

### **Requirement** Logo

* The logo SVG is added as an inline svg
* The logo is the same size as the original PNG (140px x 120px)

##### Exceeds

* A CSS transition is added to the logo SVG

> The logo has been switched from a PNG to an inline SVG and looks good. You have kept the size of the original logo, and the 360deg spin when you hover over it looks great!

---

### **Requirement** Responsive logo

* Text on logo disappears and H1 tag appears when browser window is less than 425 pixels.
* H1 tag should be hidden when browser window is greater or equal to 425 pixels.
* Breakpoint for logo text uses a mobile-first approach

> Good job using a `min-width` media query to switch out the headline logo title for the SVG logo title. There is just one small thing to fix, the instructions are very specific about the media query being set to 425px, whereas yours is set to 768px

---

### **Requirement** Dog Images

* A symbol element for the dog SVG has been added to the HTML inline
* Dog colors have been added in the CSS file and each dog has a different coat color.
* Dog SVG is replicated 4 times with the “use” element

> Truly excellent work switching using the `symbol` element to create the Corgi once and then using the `use` tags to repeat it for each Corgi rather than having 4 inline SVGs which can get messy to read.

---

### **Requirement** Dog Styling

* Dog colors have been added in the CSS file and each dog has a different coat color.
* The main color of each dog is different

> Awesome, each Corgi has a different color coat, and thanks to the `current color` property, you were able to use CSS to do it!

---

### **Requirement** Menu icon replacement and hover states

* Menu has been created from the provided SVG icons
* When a user hovers over a nav menu item, use CSS to change the color of both the text and the inline SVG.
* Hovering over the nav text or icon triggers hover state for both elements at the same time

##### Exceeds

* Add a CSS transition effect to the hover state.

> Awesome looking color Changing and scaling effects on the Navigation. It really turned out nice looking ease-in-out CSS transition was the perfect finishing touch. Well done!

---

### Final comments

> Your Corgi project really looks good! You are about 99% there, just a couple of quick touch ups and you'll be done! The first, like I mentioned earlier, is adding the 2 periods in your `background-image` url for your bone SVG. The other is just changing the size of your media query. Other than those littl bugs, you really showed some real prowess in the way you handled your SVGs, the inline ones, especially the use of symbol, and current color, can throw people off the first time they work them, but you handled like a pro. Keep up the good work, and good luck with the last little fixes!

---
