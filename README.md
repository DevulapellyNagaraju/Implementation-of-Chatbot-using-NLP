# YogaBot: Implementation of chatbot using NLP

YogaBot is a conversational chatbot designed to assist users with yoga poses, meditation techniques, breathing exercises, and other yoga-related queries. Built using Natural Language Processing (NLP), YogaBot provides an intuitive and user-friendly interface to enhance your yoga practice.

---

## **Features**
- Provides suggestions for beginner, intermediate, and advanced yoga poses.
- Guides users through meditation and breathing exercises.
- Explains the benefits of different yoga styles (e.g., Hatha, Vinyasa, Kundalini).
- User-friendly interface built with **Streamlit** for easy deployment.

---

## **Getting Started**

### **1. Clone the Repository**
To get started with YogaBot, clone the GitHub repository to your local machine.

```bash
git clone https://github.com/yourusername/YogaBot.git
cd YogaBot
```

---

### **2. Install Dependencies**
Ensure you have Python installed on your system. Then, install the required libraries using:

```bash
pip install -r requirements.txt
```

---

### **3. Run YogaBot Locally**
You can run YogaBot locally using Streamlit. Execute the following command:

```bash
streamlit run app.py
```

The application will open in your web browser at `http://localhost:8501`.

---

## **Deployment on Streamlit Sharing**

### **Step 1: Push Your Code to GitHub**
1. Ensure all your code, including the `app.py` file and `requirements.txt`, is committed to a GitHub repository.
   ```bash
   git add .
   git commit -m "Initial commit of YogaBot"
   git push origin main
   ```

### **Step 2: Create a Streamlit Sharing Account**
1. Sign up for a free account on [Streamlit Cloud](https://streamlit.io/sharing).
2. After signing in, link your GitHub account.

### **Step 3: Deploy the App**
1. Click on **New App** in Streamlit Sharing.
2. Select your YogaBot GitHub repository.
3. Specify the file path for your Streamlit app (e.g., `app.py`).
4. Click **Deploy**.

Streamlit will set up the environment and deploy your app. Your YogaBot will be live with a public URL!


## **Technologies Used**
- **Python**: Programming language.
- **NLTK/Spacy**: For natural language processing.
- **TensorFlow/Keras**: Model training (optional, if using ML).
- **Streamlit**: Frontend for chatbot deployment.

---

## **Contributing**
Feel free to fork the repository and make your contributions. Open a pull request with details about your changes.
