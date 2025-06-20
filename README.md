# genai-product-marketing-analyzer
A hands-on GenAI project using LangChain and OpenAI GPT-4o-mini to generate creative and structured marketing product descriptions from technical product fact sheets. Includes multiple prompt engineering strategies like generic social media tone, structured tabular output, and concise targeted messaging.

```markdown
# 📱 GenAI Product Marketing Analyst

This project leverages the power of **LangChain** and **OpenAI GPT-4o-mini** to generate dynamic and structured marketing content for smartphones using advanced **prompt engineering techniques**. The aim is to convert raw technical data into clear, engaging marketing descriptions suitable for multiple contexts.

---

## 🎯 Objective

Transform a product fact sheet (PDF or raw text) into:
- A catchy social media product description
- A structured and informative marketing copy with specifications
- A concise targeted message focused on camera and display quality

---

## 🔧 Technologies Used
- 🧠 OpenAI GPT-4o-mini
- 🔗 LangChain + LangChain Community
- 🧪 LangChain OpenAI integration
- 🐍 Python (Jupyter/Colab)
- 📦 PromptTemplate orchestration

---

## 💡 Features

✅ Converts detailed technical specs into:
- ✨ General product marketing text  
- 🧾 Structured descriptions with a feature-spec table  
- 📣 Custom 60-word ads focused on display/camera  

✅ Supports reusable prompt templates  
✅ Demonstrates real-world prompt engineering styles  

---

## 📑 Prompt Types Implemented

| Type                     | Description                                                 |
|--------------------------|-------------------------------------------------------------|
| Social Media Marketing   | Friendly, general audience tone for product promotions      |
| Structured Output        | Formatted as product name, description, and table of specs  |
| Focused Messaging        | Short pitch highlighting display and camera features        |

---

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/GovindaTak/genai-product-marketing-analyzer.git
   cd genai-product-marketing-analyzer
````

2. Install dependencies:

3. Add your OpenAI API key:

   ```python
   import os
   os.environ["OPENAI_API_KEY"] = "your-key"
   ```

4. Run the notebook `prompt_marketing_analyst.ipynb` in Google Colab or Jupyter.

---

## 🧠 Skills Learned

* Prompt Engineering with LangChain
* Designing reusable prompt templates
* Output control using formatting logic
* LangChain integration with OpenAI GPT-4o
* Comparative analysis of marketing output types
* Structured tabular data generation using LLMs

---

## 📣 Sample Output

### ✅ General Description:

> Unfold a new era of tech with **Samsung Galaxy Z Fold4 5G**! With its immersive 7.6” display, PC-like multitasking, and rugged design, it’s built for explorers and achievers.

### 📊 Structured Format:

```
Product Name: Samsung Galaxy Z Fold4  
Description: Unleash your creativity and multitasking with foldable display, powerful Snapdragon 8+ Gen 1, and 12 GB RAM.

| Feature                | Specification                  |
|------------------------|--------------------------------|
| Foldable Display       | 7.6" Main Screen               |
| Processing Power       | Snapdragon 8+ Gen 1            |
| RAM                    | 12 GB                          |
| Camera                 | Rear and Front                 |
| Battery Life           | 4400 mAh                       |
```

## 📬 Contact

👤 Govinda Tak
🔗 [GitHub](https://github.com/GovindaTak)
📧 [govindatak19@gmail.com](mailto:govindatak19@gmail.com)

