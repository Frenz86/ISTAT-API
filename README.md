# ISTAT-API by Daniele Grotti
ISTAT SDMX API - download open data, clicca il link a fianco per aprire l'instanza Google Colab [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frenz86/ISTAT-API/blob/main/ISTAT_SDMX.ipynb)

API permette di ecuperare dati dall' ISTAT (Istituto Nazionale di Statistica Italiano). La libreria è progettata per esplorare i metadati ISTAT e per recuperare dati in diversi formati. istatapi è basato sull'API RESTful ISTAT SDMX.

Che tu sia un'organizzazione esistente, un individuo curioso o un ricercatore accademico, istatapi mira a consentirti di accedere facilmente ai database ISTAT con solo poche righe di codice. La libreria implementa funzioni per:
- Esplorare tutti i set di dati ISTAT disponibili (flussi di dati nella terminologia SDMX)
- Ricercare i set di dati disponibili per parole chiave
- Recuperare le informazioni su un dataset specifico come: l'ID del flusso di dati, i nomi e i valori disponibili delle dimensioni del dataset, i filtri disponibili.
- Ottieni i dati di un set di dati disponibile in formato Pandas DataFrame, CSV o JSON.

Un ringraziamento particolare a Jacopo Attolini per la creazione della libreria Python. Per ulteriori dettagli consultare la documentazione dell'API su https://attol8.github.io/istatapi/
