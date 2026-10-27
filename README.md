# Currículo – Gabriel do Prado Machry

Site estático (GitHub Pages). Abra `index.html`.

- `index.html` – capa; `cv-pt.html` / `cv-en.html` – currículo online.
- `Gabriel_Machry_Curriculo.pdf` / `Gabriel_Machry_Resume.pdf` – PDFs com texto real (leitura por ATS), 2 páginas A4.
- `style.css` – visual do site e layout de impressão (`@media print`).

## Atualizar o currículo
1. Edite o texto em `cv-pt.html` e `cv-en.html`.
2. Gere os PDFs: `python scripts/gerar_pdf.py` (precisa de `pip install playwright` e `playwright install chromium`).
   Alternativa: abrir a página no Chrome > Imprimir > Salvar como PDF > desmarcar "Cabeçalhos e rodapés".
3. Faça commit de HTML + PDFs.
