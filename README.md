# Statistické rozpoznávání – Semestrální práce

Tento repozitář obsahuje zdrojový kód a data k semestrální práci.

## Obsah repozitáře

* **`smiles.ipynb`**: Hlavní notebook pro experimenty s notací SMILES. Obsahuje kompletní pipeline od načtení dat, přes tokenizaci a výpočet k-spektrálních vzdáleností, až po trénování modelů (k-NN, Random Forest, SVM) a vyhodnocení výsledků.
* **`blincs.ipynb`**: Notebook obsahující experimenty s notací BLINCS. Zahrnuje specifické předzpracování dat a pro tuto reprezentaci.
* **`environment.yml`**: Soubor pro vytvoření Conda prostředí se všemi potřebnými závislostmi pro reprodukci výsledků.
* **`*.csv`**: Soubory obsahující naměřené výsledky a metriky všech experimentálních běhů.

## Instalace a reprodukce

Pro reprodukci výsledků doporučuji vytvořit nové prostředí pomocí přiloženého konfiguračního souboru:

```bash
conda env create -f environment.yml
