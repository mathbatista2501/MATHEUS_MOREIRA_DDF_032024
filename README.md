# MATHEUS_MOREIRA_DDF_032024


**Item 2**

Foi criado diversos teste de pipeline para fazer a extração do dados via api, porem todos deram erro de execução. Por não ter a permissão de editar, foram criados novos pipelines.
![image](https://github.com/mathbatista2501/MATHEUS_MOREIRA_DDF_032024/assets/63022738/d33de555-d4a3-4f80-b072-5812088b87e2)
*https://app.dadosfera.ai/pt-BR/collect/pipelines/545bcd9a-4576-43ce-964e-4b1154f46ad0*

Para a injestão de dados, foi feito por um arquivo parquet para exemplicação dos dados
![image](https://github.com/mathbatista2501/MATHEUS_MOREIRA_DDF_032024/assets/63022738/3d63cf67-90ac-45de-b7ba-ef5ddd451bf3)
*https://app.dadosfera.ai/pt-BR/collect/import-files/3e2ab327-7543-49fa-9d81-2970f416a991*

![image](https://github.com/mathbatista2501/MATHEUS_MOREIRA_DDF_032024/assets/63022738/f1bf6500-9f76-40ed-b3cb-f7f86ec74696)
*https://app.dadosfera.ai/pt-BR/catalog/data-assets/ee578ba6-867c-49f3-957a-afea86a22623*

**Item 3**
Para esse item, não obtive uma resposta. 
No enunciado, está descrito:
"Para entender como usar um LLM como o GPT, acesse este notebook de exemplo ou então pesquise no Playground da Open AI (referenciado abaixo)"
Não estava disponivel o link para verificar o notebook de exemplo e a utilização do Playground da Open AI é pago.

**Item 4**

Como não foi possivel fazer o item anterior, utilizei a tabela TB__1DM8DH__PRODUCT_SEARCH_CORPUS_FINAL para fazer as consultas desse item.

select CATEGORY,
count(distinct DOCID)
from TB__1DM8DH__PRODUCT_SEARCH_CORPUS_FINAL,
group by CATEGORY
![image](https://github.com/mathbatista2501/MATHEUS_MOREIRA_DDF_032024/assets/63022738/58081863-f828-4fcb-8ab7-6921b35db9a9)

**Item 5**
Fiz a criação da conexão com Streamlit, e crei o app como foi informado na documentação
![image](https://github.com/mathbatista2501/MATHEUS_MOREIRA_DDF_032024/assets/63022738/024b2fbc-d44f-4b15-b526-16f561459ee4)

Tentei criar o .ipynb referente a "Visualizing Word Vectors with t-SNE"
![image](https://github.com/mathbatista2501/MATHEUS_MOREIRA_DDF_032024/assets/63022738/c59d3611-9004-48d4-90c4-779de3792b61)

*https://app-intelligence-treinamentos.dadosfera.ai/pipeline?project_uuid=50802daa-9754-401a-94ac-4efc6de9464a&pipeline_uuid=d55add85-dabb-441f-8a86-b874b8b04f2b*
