# 🚀 Text Analytics

This project leverages advanced NLP techniques to improve text data quality for analytics and machine learning applications. It focuses on automated preprocessing, semantic understanding, and domain-specific adaptations.  

## ✨ Features  
- 🔍 **Enhanced Preprocessing**: Reduces noise, inconsistencies, and ambiguities.  
- 🏷 **Named Entity Recognition (NER)**: Extracts entities like names, dates, and organizations.  
- 😊 **Sentiment Analysis**: Classifies text as Positive, Negative, or Neutral.  
- 🧹 **Text Cleaning**: Removes special characters and standardizes text.  
- 📈 **Scalability**: Handles large datasets efficiently with cloud deployment.  

## 📥 Installation  
1. **Clone the repository**:  
   ```bash  
   git clone https://github.com/prajnashankarimn/Text_Analytics.git
   
2. **Navigate to the project directory**:  
   ```bash  
   cd Text_Analytics  

3. **Install dependencies**

4. **Run the application**
   ```bash  
   python app.py

## 🚀 Usage  

🔹 **Step 1:** Open the app in your browser  

```cpp
http://127.0.0.1:5000/
```  

🔹 **Step 2:** Enter text into the input field  
🔹 **Step 3:** Click **"Analyze"**  
🔹 **Step 4:** View the results  

---

## 📜 Example Inputs & Outputs  

### 1️⃣ Sentiment Analysis  

📜 **Input** → 😊 **Sentiment Output**  

| Input Sentence | Sentiment |
|---------------|------------|
| "I love this product! It's amazing." | Positive |
| "This is the worst experience ever." | Negative |
| "The weather is nice today." | Neutral |

---

### 2️⃣ Named Entity Recognition (NER)  

📜 **Input** → 🏷 **Named Entities**  

| Input Sentence | Named Entities |
|---------------|----------------|
| "Elon Musk is the CEO of Tesla and SpaceX." | Elon Musk (PERSON), Tesla (ORG), SpaceX (ORG) |
| "Google was founded in September 1998." | Google (ORG), September 1998 (DATE) |
| "Apple launched the iPhone 15 on Sept 12, 2023." | Apple (ORG), iPhone 15 (PRODUCT), Sept 12, 2023 (DATE) |

---

### 3️⃣ Text Cleaning  

📜 **Input** → 🧹 **Cleaned Text**  

| Input Sentence | Cleaned Output |
|---------------|----------------|
| "Hello!!! How are you??? 😊" | "hello how are you" |
| "Python3.9 is great for AI!" | "python39 is great for ai" |
| "The cost of this item is $5.99." | "the cost of this item is 599" |

---

### 4️⃣ Mixed Case (All Functionalities)  

📜 **Input** → ✅ **Expected Output**  

| Input Sentence | Output |
|---------------|---------|
| "Microsoft announced Windows 11 on June 24, 2021." | **Entities:** Microsoft (ORG), Windows 11 (PRODUCT), June 24, 2021 (DATE) <br> **Sentiment:** Neutral <br> **Cleaned Text:** "microsoft announced windows 11 on june 24 2021" |
| "I hate slow internet, but Google Fiber is really fast!" | **Entities:** Google Fiber (ORG) <br> **Sentiment:** Positive <br> **Cleaned Text:** "i hate slow internet but google fiber is really fast" |

---

💡 **Enjoy analyzing text with AI!** 🚀
