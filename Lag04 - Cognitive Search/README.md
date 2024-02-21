# Lab03 - Language Studio

Projeto referente ao Lab. 04 do bootcamp da DIO sobre a certificação Microsoft AI-900, feito com base nos seguinte material:

https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html

Para replicar os resultados, siga os passos:

### Passo a Passo Resumido para Configuração da Pesquisa

1. **Criação de Recursos no Azure**: 
   - Crie um recurso de Azure AI Search, que gerenciará a indexação e consulta.
   - Provisione um recurso de Azure AI services, que oferecerá serviços de IA para enriquecer os dados com insights gerados por IA【13†source】.
   - Estabeleça uma conta de armazenamento no Azure para guardar os documentos.

2. **Upload de Documentos para o Azure Storage**:
   - Crie um container chamado `coffee-reviews` com acesso público no Azure Storage e faça upload dos documentos de análises de café【15†source】.

3. **Indexação dos Documentos**:
   - Utilize o Azure AI Search para extrair insights dos documentos armazenados. Use o assistente de Importação de Dados no portal Azure para criar um índice e importar seus documentos para o índice do Azure AI Search.

4. **Enriquecimento dos Dados com Habilidades Cognitivas**:
   - Adicione habilidades cognitivas para enriquecer os dados. Isso inclui extração de nomes de locais, frases-chave, detecção de sentimentos, geração de tags e legendas a partir de imagens.

### Insights e Possibilidades

- **Automatização do Processo de Insights**: A utilização de habilidades cognitivas de IA permite uma análise automatizada e aprofundada de grandes volumes de dados, como as análises de clientes.
- **Diversas Aplicações**: Esta configuração é particularmente útil para empresas que desejam compreender melhor as experiências dos clientes, mas pode ser adaptada para diversos outros cenários, como análise de sentimentos em redes sociais, análise de tendências de mercado, etc.
- **Integração com Outras Ferramentas**: Os insights gerados podem ser integrados com outras ferramentas de BI (Business Intelligence), CRM (Customer Relationship Management) ou até mesmo sistemas de marketing digital para aprimorar estratégias e tomadas de decisões baseadas em dados.

### Aprendizados Adquiridos

- **Complexidade da Configuração**: Configurar um sistema de mineração de conhecimento requer uma compreensão detalhada dos recursos do Azure e a habilidade de integrá-los de maneira eficaz.
- **Importância da Estrutura de Dados**: A qualidade dos insights depende significativamente da estrutura e qualidade dos dados de entrada.
- **Flexibilidade do Azure AI**: O Azure AI oferece flexibilidade para personalizar e escalar soluções de acordo com as necessidades específicas do negócio.