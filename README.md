## **Image Captioning with Flickr8k Dataset**

This project implements an image captioning system using deep learning techniques and the Flickr8k dataset. The system generates descriptive captions for images by combining computer vision and natural language processing. Two models are explored: a **baseline simple model** and a **more advanced model with an attention mechanism**. The project uses TensorFlow/Keras for model implementation and evaluation metrics such as BLEU scores to assess captioning performance.

---
To see more details [watch its video explanation:](https://youtu.be/K-8nzmuaCrY)

---

## **Run Locally**

Follow these steps to set up and run the project on your local machine.

### **1. Clone the Repository**
```bash
git clone <repo-url>
cd <repo-name>
```

### **2. Create a Virtual Environment**
Create a Python virtual environment to isolate the dependencies:
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: venv\Scripts\activate
```

### **3. Install Dependencies**
Install the required Python libraries using `requirements.txt`:
```bash
pip install -r requirements.txt
```

---

### **Requirements**
- Python 3.10.12
- TensorFlow 2.x
- Additional dependencies listed in `requirements.txt`
