# 📝 Text Summarizer

A web-based NLP tool to **summarize text**, **extract keywords**, **analyze sentiment**, and **classify topics** using advanced machine learning and NLP models.

## 🚀 Features

- Text Summarization using `facebook/bart-large-cnn`
- Keyword Extraction with TF-IDF
- Sentiment Analysis using VADER
- Topic Classification (Health, Finance, Sports, Education, General)
- Summary Compression Score
- Interactive Gradio UI

## 🧰 Technologies Used

- Python
- Transformers (Hugging Face)
- spaCy
- VADER Sentiment
- scikit-learn
- Gradio

## 📦 Installation

```bash
pip install transformers spacy vaderSentiment scikit-learn gradio
python -m spacy download en_core_web_sm

▶️ Usage
Run in Jupyter/Colab.

📂 Files
Text_Summarizer.ipynb – Main application
README.md – Project overview

🧪 Example
Input:

Climate change is one of the most pressing challenges facing humanity today. It refers to long-term alterations in temperature, precipitation, wind patterns, and other elements of the Earth's climate system. While climate variability occurs naturally, scientific evidence overwhelmingly indicates that recent climate change is largely driven by human activities, particularly the emission of greenhouse gases such as carbon dioxide, methane, and nitrous oxide. These gases trap heat in the atmosphere, leading to the greenhouse effect and resulting in global warming. The consequences of climate change are profound and far-reaching, affecting natural ecosystems, biodiversity, food security, water resources, and human health. Sea levels are rising due to the melting of polar ice caps and glaciers, threatening coastal communities around the world. More frequent and intense weather events, including hurricanes, droughts, and heatwaves, are becoming increasingly common. These events not only cause significant economic damage but also disproportionately impact vulnerable populations. Addressing climate change requires urgent and coordinated global action. This includes transitioning to renewable energy sources, improving energy efficiency, protecting forests, and investing in sustainable agriculture and transportation. International agreements such as the Paris Agreement aim to limit global warming to well below 2 degrees Celsius above pre-industrial levels, with efforts to limit it to 1.5 degrees. Achieving these targets will require substantial policy shifts, technological innovation, and societal changes. Public awareness and education are also essential to drive behavioral changes and support for climate action. While the challenge is immense, the opportunity to build a more sustainable, equitable, and resilient world lies within our grasp—if we act swiftly and decisively.

Output:

Summary: Climate change is one of the most pressing challenges facing humanity today. Addressing climate change requires urgent and coordinated global action. International agreements aim to limit global warming to well below 2 degrees Celsius.
Keywords: ['climate', 'change', 'global', 'action', 'changes']
Sentiment: Compound
Topic: Health
Compression Score: 0.12

📄 License
MIT License

🙋‍♀️ Author
Anagha Ankolekar
