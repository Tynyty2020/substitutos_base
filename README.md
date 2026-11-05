# Substitutos Profissional — base de componentes

Pacotes públicos da base do aplicativo Substitutos Profissional, baixados
pela atualização online (aba Base → Atualização online).

- `indice.json`: versão, data, tamanho e SHA-256 de cada pacote;
- `pacotes/<id>-<versão>.csv.gz`: um pacote por família de componentes e
  um só com a situação comercial.

Os arquivos são gerados por `ferramentas/gerar_pacotes.py` no repositório
do aplicativo; não edite à mão. Cada valor técnico traz unidade, condição
de teste, fonte e página do datasheet do fabricante. Os PDFs dos datasheets
não são redistribuídos: só os links oficiais.
