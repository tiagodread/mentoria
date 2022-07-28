# User Story

US01

**Como** um gerente<br>
**Eu quero** um campo de busca para filtrar os colaboradores que mais performaram no ultimo semestre<br>
**Para** que eu possa aplicar uma bonificacao de 10% do valor do salario de cada colaborador


## Criterios de aceite

- Um campo de busca deve ser disponibilizado na tela e trazer os dados de apenas um colaborador
- Um botao deve ser disponibilizado para gerar o relatorio completo
- A busca deve retornar colaboradores com a nota >= 3 no ciclo de performance do ultimo semestre
- Os dados devem ser consumidos do DB do RH
- O relatorio deve conter Nome, Numero de identificacao, area, anos casa, performance salario
- O relatorio deve conter o valor totalizado do bonus do colaborador
- O relatorio deve estar disponivel em PDF
- A busca deve funcionar por nome e Numero de identificacao
- O campo de busca deve ter no minimo 1 palavras
- O relatorio nao deve estar disponivel para supervisor ou colaborador


## Casos de teste

- Verificar o limite minimo de caracteres
- Verificar o campo de busca nao pode estar vazio
- Verificar se o resultado da busca tras um unico item
- Verificar se o relatorio e gerado ao clicar no botao "gerar relatorio"
- Verificar se o conteudo do relatorio contem somente colaboradores que performaram >=3
- Verificar se o relatorio possui as informacoes necessarias
- Verificar se o calculo do valor aplicado na bonificacao esta correto
- Verificar se o formato do arquivo e um PDF
- Verificar se a busca funciona usando nome ou numero de identificacao
- Verificar se apenas gerente tem acesso a busca e geracao do relatorio


Estimativa de tempo: 3 dias para testar tudo

Tempo disponivel para teste: 1 dia e meio
O que realmente deve ser testado baseado no risco:

- Verificar se apenas gerente tem acesso a busca e geracao do relatorio
- Verificar se o calculo do valor aplicado na bonificacao esta correto
- Verificar se o relatorio e gerado ao clicar no botao "gerar relatorio"
- Verificar se o conteudo do relatorio contem somente colaboradores que performaram >=3

## O que sera automatizado

- Verificar se apenas gerente tem acesso a busca e geracao do relatorio
- Verificar se o calculo do valor aplicado na bonificacao esta correto
- Verificar se o relatorio e gerado ao clicar no botao "gerar relatorio"
- Verificar se o conteudo do relatorio contem somente colaboradores que performaram >=3