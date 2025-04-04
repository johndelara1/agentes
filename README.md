## Agentes raspadores de websites

Diferente de uma raspagem tradicional, em que temos que separar as divs do site e definir exatamente onde estão os botões, esse agente entende sozinho os padrões do website e se adapta a estrutura das páginas para raspagem mais precisa, evitando erros de raspagens.

### Agente número 1:
- Agente de verificação: responsabilidade de verificar a credibilidade, utiliza fontes de dados antes de publicar um artigo. Suas respostas são:
    - correto
    - incorreto
    - verificado

### Agente número 2:
- Agente de resumos: responsabilidade de extrair pontos-chave e gerar resumos curtos e claros. Suas respostas são:
    - Texto com resumo

## Exemplo de Aplicação:
Imagine que você queira gerar um relatório sobre as últimas tendências em pesquisa de IA. Se você usar um LLM padrão, você pode:

1. Peça um resumo de artigos de pesquisa recentes sobre IA.
2. Revise a resposta e perceba que você precisa de fontes.
3. Obtenha uma lista de artigos junto com citações.
4. Perceba que algumas fontes estão desatualizadas, então refine sua consulta.
5. Finalmente, após várias iterações, você obtém uma saída útil.

### Com é um bloco de construção de agentes de IA:
Existem seis blocos de contrução essenciais que tornam os agentes de IA mais confiáveis, inteligentes e úteis em aplicações do mundo real:

1. Interpretação de papéis
    - Definir claramente a função dos agentes.
        - Quando um agente recebe uma identidade, especialização e objetivo bem definidos, suas respostas se tornam mais estruturadas, relevantes e alinhadas com as expectativas.
        - Exemplos: Desenvolvedor Sênior, Escritor de conteúdo, analista de pesquisa.
2. Foco
    - Reduzir alucinações, melhorar a precisão e garantir consistência
        - Sobrecarregar um agente com muitas tarefas, muitas informações ou objetivos conflitantes pode fazer com que ele perca o foco e prejudique o desempenho.
        - Reduzir responsabilidades extras para não diminuir a eficácia.
        - Exemplo: agente de IA for responsável por escrever textos de marketing, ele deve se concentrar apenas em tarefas como mensagens da marca, tom e engajamento do público.
3. Ferramentas
    - Ferramentas certas e não sobrecarregar com muitas opções.
        - Exemplo: Por exemplo, um agente de pesquisa de IA poderia se beneficiar de:
            - Uma ferramenta de busca na web para recuperar publicações recentes.
            - Um modelo de resumo para condensar longos artigos de pesquisa.
            - Um gerenciador de citações para formatar corretamente as referências.

4. Cooperação
    - uma rede de agentes especializados pode trabalhar em conjunto
        - Exemplo: Análise financeira alimentado por IA:
            - Um agente de coleta de dados coleta dados do mercado de ações em tempo real.
            - Um agente de avaliação de risco avalia os riscos de investimento com base em tendências históricas.
            - Um agente de estratégia de portfólio recomenda estratégias de investimento ideais.
            - Um agente de geração de relatórios compila as descobertas em um resumo de fácil utilização.
5. guardrails(regras orientadoras)
    - Evitar alucinações e entrar em loops infinitos ou evitar tomar decisões não confiáveis.
        - As proteções garantem que os agentes permaneçam no caminho certo e mantenham os padrões de qualidade.
            - Limitar o uso de ferramentas: evite que um agente use APIs em excesso ou gere consultas irrelevantes.
            - Definir pontos de verificação de validação: garantir que as saídas atendam aos critérios predefinidos antes de passar para a próxima etapa.
            - Estabelecer mecanismos de fallback: se um agente não conseguir concluir uma tarefa, outro agente ou revisor humano pode intervir.
        - Exemplo: 
            - Assistente jurídico com tecnologia de IA, as proteções podem impedir que o sistema:
                - Gerando aconselhamento jurídico não baseado em fatos.
                - Interpretação errônea de leis que diferem entre jurisdições
                - Citação de precedentes legais desatualizados ou incorretos.

6. Memória
    - Sem memória, um agente começaria do zero toda vez, perdendo todo o contexto de interações anteriores. Com memória, os agentes podem melhorar ao longo do tempo, lembrar de ações passadas e criar respostas mais coesas.
        - Diferentes tipos de memória em agentes de IA incluem:
            - **Memória de curto prazo** – Existe apenas durante a execução (por exemplo, relembrando o histórico de conversas recentes).
            - **Memória de longo prazo** – Persiste após a execução (por exemplo, lembrando as preferências do usuário em múltiplas interações).
            - **Memória de entidade** – Armazena informações sobre os principais assuntos discutidos (por exemplo, rastrear detalhes do cliente em um agente de CRM).
        Exemplo: Sistema de tutoria com tecnologia de IA, a memória permite que o agente:
            - Lembre-se das lições anteriores e do progresso de um aluno.
            - Adapte recomendações futuras com base no histórico de aprendizagem anterior.
            - Evite repetir as mesmas explicações desnecessariamente.



```Ao projetar sistemas agênticos, pense em si mesmo como um gerente que contrata uma equipe.

• Defina a meta – Qual é o resultado específico que você deseja que o agente alcance?
• Estabeleça o processo – Quais etapas o agente deve seguir para atingir essa meta?
• Contrate os especialistas certos – Se esse fosse um trabalho do mundo real, que tipo de especialistas você traria?
• Dê a eles as ferramentas certas – Depois de contratar os especialistas, a quais ferramentas eles precisariam ter acesso para concluir seu trabalho com eficiência?

Por exemplo, em vez de um agente genérico "pesquisador", crie um "analista de pesquisa de mercado especializado em tendências de IA". Em vez de um agente "escritor", crie um "estrategista sênior de conteúdo técnico".

Ao dar aos agentes funções, experiência, propósito e ferramentas claras, você os torna mais eficazes, estruturados e capazes de fornecer resultados de alta qualidade. A especificidade importa.```