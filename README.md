## Chat mit PDF im MD-Format

Dieses Repo implementiert einen Chat mit deinem PDF über eine GUI. Dieser Code nutzt OpenAI's LLM und Embedding-Modelle für die Informationsabfrage aus deinen Dokumenten.

![ChatApp UI](https://github.com/PromtEngineer/PDF_Chat-GUI/assets/134474669/bba57a81-909f-4fe3-91cd-96ae14c17438)

## Das Repo klonen:
Klone das Repository.
```shell
git clone https://github.com/PromtEngineer/PDF_Chat-GUI.git
```

## Umgebung einrichten
Um deine Umgebung für den Code hier einzurichten, installiere zunächst alle Anforderungen:

```shell
pip install -r requirements.txt
```

## OpenAI API-Schlüssel

Du benötigst den OpenAI API-Schlüssel, um dies auszuführen, hole dir deinen OpenAI-Schlüssel [hier](https://platform.openai.com/account/api-keys).
Trage im `.env` deinen API-Schlüssel ein.

```shell
OPENAI_API_KEY=
```

## Die WebApp starten:

```shell
streamlit run ChatPDF.py
```
