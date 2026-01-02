# ASCII Image Generator in Python 

##  Project Purpose

The **ASCII Image Generator** is a Python-based project that converts any digital image into **ASCII art**, which is a visual representation of an image using text characters.

The main purpose of this project is to:
- Understand **basic image processing** concepts
- Learn how pixel intensity can be mapped to characters
- Practice Python programming using a real-world mini project
- Build a creative and resume-worthy project for beginners

This project is suitable for **students, beginners, and Python learners**.

---

##  How the Code Works

The program follows a simple and logical pipeline:

### 1️ Image Loading
- The image is loaded using the **Pillow (PIL)** library.
- Any common image format such as JPG or PNG is supported.

### 2️ Image Resizing
- The image is resized to fit properly in the terminal.
- Aspect ratio is maintained so the image does not look stretched.

### 3️ Grayscale Conversion
- The image is converted into grayscale.
- Each pixel now has a value between **0 (black)** and **255 (white)**.

### 4️ Pixel to ASCII Mapping
- A predefined set of ASCII characters is used:

@ % # * + = - . :

- Darker pixels are mapped to dense characters (`@`, `%`)
- Lighter pixels are mapped to lighter characters (`.` or space)

### 5️ ASCII Art Generation
- Each pixel is converted into a corresponding ASCII character.
- Characters are arranged row by row to recreate the image shape.
- The final ASCII art is printed in the terminal and saved to a text file.

---

##  How to Run the Program

### Step 1: Install Required Library

Make sure Python is installed, then install Pillow:

```bash
pip install pillow


⸻

 Step 2: Prepare the Files
	•	Place your image in the project folder
	•	Example image name:

image.jpg



⸻

 Step 3: Run the Script

Update the image path in the code:

image_path = "image.jpg"

Run the program:

python ascii_image.py


⸻

 Step 4: View Output
	•	ASCII art will be displayed in the terminal
	•	Output will also be saved as:

ascii_image.txt



Open the file using any text editor (use a monospace font for best results).

⸻

 Applications of This Project
	•	Python mini project
	•	College assignment or lab submission
	•	Image processing practice
	•	Creative coding experiment
	•	Resume / GitHub portfolio project

⸻

 Future Improvements
	•	Colored ASCII art
	•	Webcam to ASCII conversion
	•	Web application using Streamlit
	•	Save ASCII output as an image

⸻
 License

This project is open-source and intended for educational use.

⸻
 If you found this project helpful, feel free to star the repository!

