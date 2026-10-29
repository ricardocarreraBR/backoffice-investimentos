## Olá, eu sou o Ricardo Carrera 👋

Trabalho com **investimentos em previdência complementar** e uso programação para resolver os problemas do dia a dia
da área: automatizar o backoffice, conferir o custodiante e dar à equipe análises que antes dependiam de planilhas.

### O que eu faço
- **Backoffice de investimentos:** carteira diária dos planos, cotas, contas a pagar e receber, tesouraria.
- **Conciliação:** comparação automática com os arquivos do custodiante (carteira, demonstrativo de caixa e mapa de cotas),
  com explicação e conferência das diferenças.
- **Análise:** rentabilidade contra benchmarks e meta atuarial, alocação por segmento, projeção do ano e stress.
- **Rotinas operacionais:** geração e conferência de boletas, lançamentos no sistema financeiro e leitura de PDFs.

### Em destaque: sistema de backoffice de investimentos
Sistema web interno, feito do zero para substituir um módulo terceirizado de investimentos.

- Calcula a carteira de cada plano **com dados próprios** (operações, cotas da CVM, preços da ANBIMA, índices do Banco
  Central) e usa o custodiante só para conferir.
- Valida dia a dia carteira, demonstrativo de caixa e mapa de cotas, mostrando até que data tudo bate.
- Dashboard de alocação, rentabilidade por segmento, projeção do ano com stress e manual de uso integrado.
- Regras de segurança: roda 100% na rede local, segregação de funções (quem gera não confere), trilha de auditoria e
  números exatos (`Decimal`, nada de arredondamento de ponto flutuante).
- Mais de 170 testes automatizados.

*O código é de uso interno; uma versão de demonstração, com dados fictícios, está a caminho.*

### Ferramentas
`Python` · `Django` · `SQLite` · `pandas` · `openpyxl` · `pdfplumber` · `pytest` · `git` · `HTML/CSS/JavaScript`

### Contato
- [LinkedIn](https://www.linkedin.com/in/ricardo-carrera-81073414b/)
- E-mail: ricardocarrera@id.uff.br
