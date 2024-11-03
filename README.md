### **Lesson 6: Creating Personalized Shapes with SVG**

#### **Objective:**  
Students will learn to create and customize basic SVG shapes by creating a new HTML file, `shapes.html`, and using different attributes to personalize their designs.

---

### **Instructions**

#### **Step 1: Create a New HTML File**
1. In your `media-gallery` folder and create a new HTML file and name it `shapes.html`.

#### **Step 2: Set Up the Basic HTML Structure**
2. Open `shapes.html` in your text editor and add the following basic HTML structure:
   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Personalized SVG Shapes</title>
   </head>
   <body>
       <h1>My Unique SVG Shapes</h1>
   </body>
   </html>
   ```

#### **Step 3: Add an SVG Container**
3. Inside the `<body>` tag, add an `<svg>` container. Set its width and height to accommodate your shapes:
   ```html
   <svg width="500" height="500">
       <!-- Your shapes will go here -->
   </svg>
   ```

#### **Step 4: Choose and Personalize Three Shapes**
4. Choose **three** shapes from the following list to create inside the `<svg>` container. Each shape includes an example and descriptions of its main attributes:

---

### **SVG Shape Options and Attributes**

#### **1. Rectangle**
   ```html
   <rect x="60" y="80" width="120" height="70" rx="15" ry="15" fill="teal" stroke="black" stroke-width="3" />
   ```
   - **x**: Horizontal position of the rectangle’s top-left corner.
   - **y**: Vertical position of the rectangle’s top-left corner.
   - **width**: Width of the rectangle.
   - **height**: Height of the rectangle.
   - **rx** and **ry**: Rounded corner radii for the x and y axes. Setting both creates rounded corners.
   - **fill**: Fill color of the rectangle.
   - **stroke**: Outline color of the rectangle.
   - **stroke-width**: Thickness of the rectangle’s outline.

#### **2. Circle**
   ```html
   <circle cx="200" cy="100" r="50" fill="coral" stroke="navy" stroke-width="4" />
   ```
   - **cx**: X-axis center of the circle.
   - **cy**: Y-axis center of the circle.
   - **r**: Radius of the circle.
   - **fill**: Fill color of the circle.
   - **stroke**: Outline color of the circle.
   - **stroke-width**: Thickness of the circle’s outline.

#### **3. Ellipse**
   ```html
   <ellipse cx="250" cy="150" rx="80" ry="40" fill="darkorange" stroke="black" stroke-width="2" />
   ```
   - **cx**: X-axis center of the ellipse.
   - **cy**: Y-axis center of the ellipse.
   - **rx**: Radius on the x-axis.
   - **ry**: Radius on the y-axis.
   - **fill**: Fill color of the ellipse.
   - **stroke**: Outline color of the ellipse.
   - **stroke-width**: Thickness of the ellipse’s outline.

#### **4. Line**
   ```html
   <line x1="70" y1="350" x2="250" y2="350" stroke="purple" stroke-width="5" />
   ```
   - **x1** and **y1**: Starting coordinates of the line.
   - **x2** and **y2**: Ending coordinates of the line.
   - **stroke**: Color of the line.
   - **stroke-width**: Thickness of the line.

#### **5. Polygon**
   ```html
   <polygon points="150,50 250,150 50,150" fill="gold" stroke="black" stroke-width="2" />
   ```
   - **points**: A list of x,y coordinates for each vertex of the polygon.
   - **fill**: Fill color of the polygon.
   - **stroke**: Outline color of the polygon.
   - **stroke-width**: Thickness of the polygon’s outline.

#### **6. Text / tspan**
   ```html
   <text x="120" y="450" font-family="Courier" font-size="28" fill="darkgreen">My SVG Art</text>
   ```
   - **x**: Horizontal position of the text.
   - **y**: Vertical position of the text.
   - **font-family**: Font used for the text.
   - **font-size**: Size of the text.
   - **fill**: Color of the text.

---

#### **Step 5: Personalize Your Shapes**
5. Personalize each shape by adjusting its attributes. Experiment with different colors, sizes, positions, and features to make your design unique.

#### **Step 6: Save and Preview**
6. Save `shapes.html` and open it in a web browser to preview your customized SVG shapes. You should see at least 3 SVG shapes.

#### Step 7: Submit Your Work
7. Once you've confirmed that the shapes looks good, submit the following:
   - Zip or upload the shapes.html file to the classwork assignment on Google Classroom

### **Outcome**
- Students will have created a new HTML file, `shapes.html`, and drawn three SVG shapes, each with personalized attributes that reflect their unique style.