# Processando e Transformando Dados com Power BI

Projeto baseado no modulo Visualização e Analise de dados com power BI ministrado pela Juliana Mascarenhas 
https://github.com/julianazanelatto

O objetivo deste desafio é transformar e analisar dados de um banco de dados com o Power BI.
Para a preparação do ambiente, criei uma instancia de banco de dados Mysql no Azure, realizei a conexão do servidor com o Workbench e populei a base de dados com o script disponibilizado na aula.
Após isso conectei o mysql no Power BI e selecionei todas as tabelas da base de dados para começar as transformações.


### Transformações:

Foram realizadas as seguintes transformações nos dados originalmente extraídos do banco de dados:

- Alteração dos tipos dos dados de texto para inteiro ou decimal se necessário
- Tratamento de valores nulos
- Mesclagem de colunas (nome e sobrenome)
- Mesclagem de tabelas (employee e departament, colaboradores e gerentes, departamento e localização)
- Separação de colunas complexas (endereço) 
- Eliminação de colunas não utilizadas no Relatório

(No caso da mesclagem das tabelas de departamento e localização, não utilizamos o atribuir pois O Atribuír acrescenta as colunas de uma tabela na outra, não relacionando os campos de relacionamento das duas, nesse caso não queremos acrescentar os dados de uma tabela na outra, mas sim vincular o dnumber e verificar quais localizações e departamentos tem o mesmo Dnumber)

### Visuais

Os visuais criados então com essas transformações foram:
- Totel de funcionários por gerentes
- Total de horas por Projeto
- Funcionarios por departamento 
- Departamento por localização






![imagem](https://media.discordapp.net/attachments/1024076211137290270/1162605131439820810/image.png?ex=653c8b67&is=652a1667&hm=0f4c0cf4ecdff41baa444374ba830a02041485ef7bb5030268a8483756279b15&=)

