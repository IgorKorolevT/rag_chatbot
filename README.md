# RAG чатбот для документів

Jupyter Notebook. Без Streamlit і платних сервісів.

## Що вміє

- PDF / DOCX / TXT
- Фрагменти 500–1000 символів з overlap (файл + сторінка)
- Embeddings: paraphrase-multilingual-MiniLM-L12-v2
- Cosine similarity (numpy)
- Відповідь тільки за контекстом
- Джерела + вибір файлів чекбоксами
- Історія в SQLite, експорт у TXT

## Запуск

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook RAG_Chatbot.ipynb
```

Виконати комірки зверху вниз → завантажити файли → питати.
