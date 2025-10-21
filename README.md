# Info_log
3. Edite o README.md:
Exemplo de estrutura para o README:

markdown
# Análise de Dados de Restaurantes

Este projeto contém uma planilha Excel com análise de dados de estabelecimentos alimentícios.

## Fórmulas Utilizadas

### 1. Contagem de Municípios Únicos
```excel
=CONT.VALORES(REMOVER.DUPLICADAS(A:A))
Extrai municípios únicos da coluna A e conta quantos existem.

2. Contagem de Especialidades Únicas
excel
=CONT.VALORES(REMOVER.DUPLICADAS(B:B))
Remove duplicatas da coluna B (especialidades) e conta os valores restantes.

3. Contagem de Naturezas Jurídicas Únicas
excel
=CONT.VALORES(REMOVER.DUPLICADAS(C:C))
Mesma lógica para a coluna C (natureza jurídica).

4. Restaurantes em São José dos Campos
excel
=CONT.SES(D:D; "São José dos Campos"; E:E; "Restaurante")
Conta registros onde a cidade é "São José dos Campos" e o tipo é "Restaurante".

5. Busca por CNPJ
excel
=SEERRO(PROCV(CNPJ; A:G; Nº_COLUNA; FALSO); "")
Busca um CNPJ na coluna A e retorna informações das colunas B a G.

Como Usar
Baixe o arquivo analise_restaurantes.xlsx.

Digite um CNPJ na célula destacada para ver suas informações.

Use as abas com análises pré-configuradas.

Autor
Augusto - GitHub
