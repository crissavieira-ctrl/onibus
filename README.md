# Coleta de tarifas de ônibus (cidades brasileiras)

Script em Python que coleta as tarifas de ônibus de algumas capitais por Selenium, salva/atualiza `onibusurbano_dados.xlsx` e faz commit mensal automático via GitHub Actions.

## Como usar

1. Crie um repositório no GitHub e suba estes arquivos:
   - `onibus_scraper.py`
   - `requirements.txt`
   - `.github/workflows/scrape.yml`
2. Faça o primeiro commit/push.
3. O GitHub Actions rodará **todo dia 10 às 12:00 UTC** e atualizará o Excel com uma **nova coluna** timbrada com o timestamp (UTC) da execução.
4. Você também pode rodar manualmente em **Actions → Coleta tarifas ônibus → Run workflow**.

> O arquivo `onibusurbano_dados.xlsx` fica na raiz do repositório e é versionado.
