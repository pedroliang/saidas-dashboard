# Centralux · Saídas diárias

Dashboard estático (GitHub Pages) que lê ao vivo a aba **saídas diárias** da planilha
`1fRqUo8vH4awjCwV12U0fhR2bdBSRGFUVMlU8PozUsoQ` (gid 417397612) via exportação CSV.

- A planilha precisa continuar compartilhada como "qualquer pessoa com o link".
- Para trocar de planilha/aba, edite `SHEET_ID` e `GID` no início do `<script>` em `index.html`.
- Cada bloco ("28/08 a 1/9 - feito") entra na data do primeiro dia do título.
- SKUs com grafia diferente (ex.: 5745 e 5745(P)) são mantidos separados e listados em Dados/Notas.
