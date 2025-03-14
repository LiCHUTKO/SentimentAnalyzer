# 🎭 Analizator Sentymentu Komentarzy (Sentiment Analyzer)

## 📝 Opis projektu
Projekt służy do analizy sentymentu komentarzy w języku polskim wykorzystując model BERT. Narzędzie automatycznie klasyfikuje teksty jako pozytywne, neutralne lub negatywne.

## ✨ Główne funkcje
- 🔍 Analiza sentymentu tekstu w języku polskim
- 📊 Wizualizacja wyników w formie wykresów
- 📋 Eksport wyników do DataFrame
- 🎯 Kategoryzacja na 3 grupy sentymentu

## 🛠️ Wymagania techniczne
- Python
- Biblioteki:
  - transformers
  - pandas
  - matplotlib

## 📦 Instalacja
```bash
pip install transformers pandas matplotlib
```

## 🚀 Jak uruchomić
1. Sklonuj repozytorium:
```bash
git clone https://github.com/LiCHUTKO/SentimentAnalyzer.git
cd SentimentAnalyzer
```

2. Uruchom Jupyter Notebook:
```bash
jupyter notebook
```

3. Otwórz plik `notebook.ipynb`

## 💡 Przykład użycia
```python
from transformers import pipeline

# Inicjalizacja analizatora
sentiment_pipeline = pipeline("sentiment-analysis", 
                            model="nlptown/bert-base-multilingual-uncased-sentiment")

# Przykładowa analiza
tekst = "Ten produkt jest niesamowity!"
wynik = sentiment_pipeline(tekst)
```

## 📊 Przykładowe wyniki
- 😊 Pozytywne: 4-5 gwiazdek
- 😐 Neutralne: 3 gwiazdki
- ☹️ Negatywne: 1-2 gwiazdki

## 🌟 Funkcjonalności
- Analiza wielu komentarzy jednocześnie
- Wizualizacja rozkładu sentymentów
- Eksport wyników do różnych formatów
- Wsparcie dla języka polskiego

## 📈 Wydajność
Model osiąga wysoką skuteczność w analizie tekstów w języku polskim, szczególnie w kontekście opinii o produktach.

## 🤝 Wkład w projekt
Zachęcamy do kontrybucji! Aby zgłosić błąd lub zaproponować nową funkcjonalność:
1. Utwórz fork repozytorium
2. Stwórz nową gałąź
3. Wyślij pull request

## 👥 Autorzy
- LiCHUTKO

---
⭐ Jeśli projekt ci się podoba, zostaw gwiazdkę na GitHubie!
