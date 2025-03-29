
# Virtual-AI-calculator
---
# About
This virtual AI Calculator represents a cutting-edge application that combines OpenCV with Google's Gemini AI to tackle mathematical problems across all complexity levels. Users can manually sketch mathematical expressions on the interface, after which the AI system interprets these visual inputs to deliver comprehensive solutions. While conceptually similar to the Apple iPad calculator, this project distinguishes itself by implementing sophisticated AI technologies to achieve superior functionality and precision.
---
# Features

- Draw Math Problems: Use your finger to draw any mathematical problem on the screen.
- Move Around: Move the pointer around the screen by lifting two fingers.
- Reset Canvas: Erase the current drawing by lifting the thumb.
- Send to AI Model: Send the visual drawing to the model by lifting the little finger.
- Detailed Solutions: The model interprets the drawing and displays a detailed solution.
---
# Installation
1. Obtain the Gemini API Key:

Visit AI Studio to get your Gemini API key.

2. Create a virtual environment using the command 
```
python -m venv myenv
```
and activate it using
on Windows:
```
myenv\Scripts\activate
```
on macOS/Linux:
```
source myenv/bin/activate
```

3. Install Dependencies:

Run the following command to install the required packages:
```
pip install -r requirements.txt
```

4. Configure the API Key:

Add your API key to  ```videoapp/view.py ```.

5. Run the Web Application:

Start the web server with
```
python manage.py runserver
```

6. Access the Web Application:

Open your web browser and navigate to http://127.0.0.1:8000 to use the app.

---
# Drawing Rules
To interact with the calculator, follow these drawing rules:

- Draw math problems only when the pointer finger is up.
- Move around the screen by lifting two fingers.
- Reset/erase the canvas by lifting the thumb.
- Send the visual drawing to the AI model by lifting the little finger.
The AI model will then interpret the drawing and display a detailed solution.

---
You can access the demo video here: [demo video](https://drive.google.com/drive/folders/1AEL24X6pgOshKlU1WQ2cYHiF2BRtp-no?usp=sharing)

