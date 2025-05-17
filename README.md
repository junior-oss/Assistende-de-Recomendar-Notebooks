# Assistente de Recomendação de Notebooks

## Descrição do Projeto

Este projeto consiste em um sistema de recomendação de notebooks desenvolvido utilizando agentes conversacionais e
a API do Gemini. O objetivo principal é auxiliar usuários na escolha do notebook ideal com base em suas necessidades
e no uso pretendido. O sistema interage com o usuário para entender seus requisitos, busca as melhores opções disponíveis
no mercado brasileiro, analisa reviews e, finalmente, apresenta uma recomendação de custo-benefício. Além disso, o
sistema oferece funcionalidades para tirar dúvidas sobre o notebook recomendado e comparar diferentes modelos.

## Funcionalidades Principais

* **Entendimento das Necessidades do Usuário:** Através de uma conversa inicial, o sistema coleta informações sobre como o usuário pretende utilizar o notebook.
* **Validação da Descrição:** Um agente verifica se a descrição fornecida pelo usuário faz sentido, oferecendo sugestões caso contrário.
* **Sugestão de Componentes:** Com base na descrição do trabalho, o sistema sugere configurações de hardware ideais.
* **Busca de Notebooks no Brasil:** O sistema busca notebooks disponíveis para compra no Brasil que correspondam às configurações recomendadas.
* **Análise de Reviews:** Opiniões de usuários sobre os notebooks encontrados são analisadas para entender os pontos positivos e negativos.
* **Escolha por Custo-Benefício:** O sistema identifica a melhor opção de notebook que equilibra desempenho e preço.
* **Geração de Relatório Final:** Um relatório detalhado com a recomendação do melhor notebook é apresentado ao usuário.
* **Interação Pós-Recomendação:** O usuário pode expressar sua satisfação, pedir novas recomendações com base em novas preferências, tirar dúvidas sobre o notebook recomendado e comparar diferentes opções.
* **Comparação de Notebooks:** Permite ao usuário comparar o notebook recomendado com outros modelos considerados durante a busca.
* **Sistema de Tirar Dúvidas:** Um agente especializado responde a perguntas específicas sobre o notebook recomendado.

## Como Utilizar

1.  Execute o código Python principal.
2.  O sistema iniciará com uma mensagem de boas-vindas e solicitará que você descreva como pretende usar o notebook.
3.  Siga as instruções na tela, respondendo às perguntas do sistema.
4.  Após a recomendação inicial, você poderá interagir com o sistema para fornecer feedback, tirar dúvidas ou solicitar comparações.

## Tecnologias Utilizadas

* Python
* API do Gemini (através de algum framework ou biblioteca específica que você utilizou)
* (Mencione outras bibliotecas relevantes, como `langchain` ou outras para interação com agentes, `re` para expressões regulares, `IPython.display` para formatação Markdown no Colab, etc.)

## Estrutura do Código (Breve Descrição dos Agentes)

* **Agente Validador de Descrição (`agente_validador_descricao`):** Verifica se a descrição do trabalho do usuário é válida.
* **Agente de Sugestão de Componentes (`agente_sugestao_componentes`):** Sugere configurações de hardware.
* **Agente Buscador de Notebooks (`agente_buscador_notebooks`):** Busca notebooks no mercado brasileiro.
* **Agente Analisador de Reviews (`agente_analisador_reviews`):** Analisa opiniões de usuários.
* **Agente de Escolha por Custo-Benefício (`agente_escolha_custo_beneficio`):** Seleciona a melhor opção.
* **Agente de Relatório Final (`agente_relatorio_final`):** Gera o relatório para o usuário.
* **Agente de Comparação de Notebooks (`agente_comparador_notebooks`):** Compara especificações de notebooks.
* **Agente de Resposta a Dúvidas (`agente_responde_duvida`):** Responde a perguntas sobre o notebook recomendado.

## Autor

Joseval Eliziário de Melo junior
