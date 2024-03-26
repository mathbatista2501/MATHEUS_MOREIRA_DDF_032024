# MATHEUS_MOREIRA_DDF_032024

**Fonte de Dados**

Banco de dados Adventure Works, contendo 71 tabela.

**ETL**
Todo o processo foi criado utilizando ferramentas da Azure.

O processo está concentrado no Data Factory. Nele fiz a criação do pipeline para criação das minhas tabelas

![image](https://github.com/mathbatista2501/MATHEUS_MOREIRA_DDF_032024/assets/63022738/d83f0be2-6033-4225-a9b1-11fdf98bc08d)

Dentro do meu data flow é o momento que eu faço a criação das minhas dimensões. 
Utilizo as tabelas originais como origem, faço algumas transformações necessarias e ai faço a criação de novas tabelas que são utilizadas como dimensão

![image](https://github.com/mathbatista2501/MATHEUS_MOREIRA_DDF_032024/assets/63022738/83cefe19-c52a-4568-a41f-69bce02433ec)

No banco de dados salvo elas utilizando o prefixo de "Dim"

![image](https://github.com/mathbatista2501/MATHEUS_MOREIRA_DDF_032024/assets/63022738/697091cd-e04a-4e60-8bef-458890640168)

No proximo passo do pipeline, eu faço a criação da minha tabela Fato. Para criação dela, eu utilizo uma query SQL

![image](https://github.com/mathbatista2501/MATHEUS_MOREIRA_DDF_032024/assets/63022738/4fe884f8-7ab9-47aa-88b4-e6e11806fa7f)

O proximo passo é fazer a modelagem das tabelas. Fiz a criação do modelo no formato estrela, centralizando minha tabela Fato. 
Modelagem feita no PowerBI.

![image](https://github.com/mathbatista2501/MATHEUS_MOREIRA_DDF_032024/assets/63022738/97385524-5b09-48af-a391-02bd02b52f0a)

Com a modelagem dos dados feitas, já é possivel eu fazer a analise dos dados. Foram criadas medidas em DAX para o auxilio das informações

![image](https://github.com/mathbatista2501/MATHEUS_MOREIRA_DDF_032024/assets/63022738/a0f353bb-ec5f-4891-a41d-00252d26f89b)

Segue algumas analises:

*Produtos*

  -Produtos mais vendido
  
  ![image](https://github.com/mathbatista2501/MATHEUS_MOREIRA_DDF_032024/assets/63022738/57a2f5e3-0645-4a53-aac2-15971d979e2a)
  
  -Top 5 produtos que geraram mais renda ($)
  
  ![image](https://github.com/mathbatista2501/MATHEUS_MOREIRA_DDF_032024/assets/63022738/2be0b51d-fdf0-4312-9903-daceadb8e900)
