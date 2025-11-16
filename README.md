# afg-challenge-agente-estudos
Challenge do programa Azure Frontier Girls

# Descrição do projeto e Objetivo do Agente
O projeto foi criado com o objetivo de auxiliar o usuário nos estudos relacionados à sua graduação em Tecnologia da Informação.

# Instruções
A instrução passada para o agente foi:
Você é um agente de auxílio aos estudos. Você cria resumos, monta exercícios e provas com base nos materiais que serão indexados e responde perguntas a respeito das matérias, com base nos materiais de estudo que serão indexados e pesquisas na internet. Você precisa informar em suas respostas se a informação veio do material indexado ou de busca na internet, dando preferência sempre às informações dos materiais.

# Knowledge
Foram incluídas no knowledge os materiais de estudo em PDF disponibilizados pela Instituição de Ensino, afim de delimitar bem as matérias abordadas na graduação.

# Passo a passo da criação

1. Após a criação do resource group e do projeto foi feito o deploy do model gpt-4o-mini e a inclusão do agente AgentEstudos.
2. Foi incluída então a instrução:
> Você é um agente de auxílio aos estudos. Você cria resumos, monta exercícios e provas com base nos materiais que serão indexados e responde perguntas a respeito das matérias, com base nos materiais de estudo que serão indexados e     pesquisas na internet. Você precisa informar em suas respostas se a informação veio do material indexado ou de busca na internet, dando preferência sempre às informações dos materiais.

![Image](https://github.com/user-attachments/assets/69a6afc3-8569-4893-a677-43d3526bfe0e)

3. Depois foram incluídos os materiais no Knowledge.

![Image](https://github.com/user-attachments/assets/bc514f01-0a00-4e26-8525-ee02794d7daf)

![Image](https://github.com/user-attachments/assets/33888c1d-25d4-48be-82a3-452acfac2f28)

4. Cliquei então em "Try in Playground" e iniciei os testes para verificar se ele estava atendendo as solicitações conforme o esperado.

![Image](https://github.com/user-attachments/assets/500247c3-78ab-4f05-a969-d448899efae2)

5. Pedi inicialmente que ele fizesse um resumo do primeiro capítulo da matéria Implementação de Banco de Dados". Ele então localizou no material disponibilizado a matéria solicitada e o capítulo específico e montou um resumo padrão.

![Image](https://github.com/user-attachments/assets/ec36c8f8-6103-4e1e-9530-12b8eded270c)

![Image](https://github.com/user-attachments/assets/2e539a9e-4dff-4a17-b884-a27b2148cfe0)

6. Eu pedi então que ele criasse uma prova de multipla escolha, com 4 opções de escolha em cada questão, e 5 questões sobre o segundo capítulo da matéria Modelagem de Dados. Ele então localizou a matéria e o capítulo e montou as questões.

![Image](https://github.com/user-attachments/assets/bbddbc48-d194-41ec-9267-89f15356f3a8)

7. Após montar as questões ele me perguntou se eu gostaria que ele me fornecesse o gabarito.

![Image](https://github.com/user-attachments/assets/b7b7bee1-e422-4b5e-99c8-98bcdd89e616)

8. Pedi então que ele me fornecesse o gabarito comentado, o que ele me entregou em seguida.

![Image](https://github.com/user-attachments/assets/0ce52dad-6268-4ea3-935f-55e222c52ee3)

![Image](https://github.com/user-attachments/assets/c47a3b33-bbfe-409b-bd74-3895d595280f)

9. Pedi então que ele criasse pra mim um resumo no estilo flashcards do capítulo 4 da matéria Modelagem de dados e ele me forneceu conforme matéria, capítulo e modelo solicitado.

![Image](https://github.com/user-attachments/assets/2e24e9c3-d637-40b5-850c-d081a9b5d060)

![Image](https://github.com/user-attachments/assets/4dfa719d-98c0-4091-ad89-730a8317ac9e)

10. Por último pedi que ele criase um resumo do capitulo 2 da matéria Implementação de Banco de Dados utilizando o método Cornell, o que ele prontamente me entregou conforme especificações solicitadas.

![Image](https://github.com/user-attachments/assets/1c0b735a-3de8-4a9b-a4f2-03be879ebf49)

![Image](https://github.com/user-attachments/assets/bbc6b7e8-8d3c-4efe-b9eb-57b6e8f37a1b)

![Image](https://github.com/user-attachments/assets/37e99230-9f26-4082-8b8b-0057217cb331)

# Referências

- [Azure AI Foundry](https://ai.azure.com)
- [Portal Azure](https://portal.azure.com)
