# 🚦 AI Traffic Sign Recognition With Gemini 2.0 Flash API

This project is an **AI-powered Traffic Sign Recognition Web App** that uses **Google’s Gemini 2.0 Flash API** to identify traffic signs from uploaded images and provide driving instructions.

---

## **📌 Features**

1. **Upload a traffic sign image** or Video via a simple web interface.
2. **Automatic AI detection**:

   * If the image is **not a traffic sign**, shows an **error message**.
   * If the image **is a valid sign**, provides:

     * **Sign name** (e.g., Stop, Yield, Speed Limit 50)
     * **Meaning of the sign**
     * **Driving instructions / rules**
3. **Powered by Gemini 2.0 Flash API** for **fast and accurate image analysis**.
4. **User-friendly Gradio web interface** for easy access.

---

## **🛠️ Tech Stack**

* **Python 3.x**
* **Gradio** – For creating the web interface
* **Pillow (PIL)** – For image handling
* **Requests** – For sending requests to Gemini API
* **Gemini 2.0 Flash API** – For AI-powered traffic sign analysis

---

## **📥 Installation & Setup**

1. **Clone or download this project**
2. **Install the required libraries** in your Python environment:

```bash
pip install gradio pillow requests
```

3. **Replace your Gemini API Key** in the code:

```python
GEMINI_API_KEY = "your_gemini_api_key_here"
```

4. **Run the notebook (`.ipynb` file)** and **launch the Gradio web app**.

---

## **▶️ How to Use**

1. **Open the web interface** after running the notebook.
2. **Upload an image of a traffic sign** (JPG/PNG).
3. **View the analysis result**:

   * Sign name
   * Meaning
   * Driving instructions
4. **If the image is not a valid traffic sign**, an **error message** will appear.

---

## **📸 Example Usage**

* **Upload:** An image of a **Stop Sign**
* **Output:**

```
🚦 Traffic Sign Analysis:
Sign: Stop
Meaning: Vehicle must come to a complete stop.
Driving Instruction: Proceed only when the road is clear.
```
