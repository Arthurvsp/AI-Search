# AI-Search

## Azure Cognitive Search Tutorial

Este projeto contém um tutorial passo a passo para configurar e utilizar o Azure Cognitive Search para indexação e consulta de dados com capacidades de Inteligência Artificial (AI).

## Pré-requisitos

1. **Conta no Azure**: Se você ainda não possui, [crie uma conta gratuita](https://azure.microsoft.com/free/).
2. **Azure Cognitive Search**: Acesse o portal do Azure e crie um serviço de Pesquisa Cognitiva.

## Passo a Passo para Configuração

### 1. Criar um Serviço de Pesquisa Cognitiva
- Acesse o portal do Azure.
- No painel de pesquisa, procure por "Cognitive Search" e clique em "Criar".
- Preencha as informações de nome, grupo de recursos e localização.
- Escolha o nível de preço adequado (Free, Basic, Standard, etc.).
- Após a criação, vá para a página do serviço.

### 2. Configurar um Indexador de Dados
- No painel do Azure Cognitive Search, clique em "Importar dados".
- Selecione a origem dos dados (pode ser um banco de dados SQL, Blob Storage, etc.).
- Configure o indexador, mapeando os campos que serão indexados.

### 3. Criar um Índice de Pesquisa
- Crie um índice configurando os campos que deseja indexar, como `ID`, `Nome`, `Descrição`, etc.
- Defina os tipos de dados (texto, número, etc.) e marque quais campos são pesquisáveis e filtráveis.

### 4. Habilitar Capacidades de IA
- Utilize habilidades cognitivas (Cognitive Skills) como detecção de idioma, reconhecimento de entidades ou análise de sentimentos para enriquecer os dados durante a indexação.

### 5. Consultar Dados
- Utilize a interface de consulta ou faça consultas via API REST.
- Exemplos de queries incluem pesquisa simples por palavras-chave ou consultas avançadas usando operadores booleanos.

## Ferramentas e Casos de Uso

- **E-commerce**: Filtragem de produtos, busca por similaridade, ou recomendação de itens baseados em características de clientes.
- **Setor Jurídico**: Pesquisa em grandes volumes de documentos legais com capacidades de linguagem natural para extrair entidades importantes.
- **Mídia e Entretenimento**: Busca avançada em arquivos de vídeo e áudio com transcrição automática e análise de sentimentos.

## Possibilidades e Insights

- **Análise de Sentimentos**: Pode ser útil para análise de avaliações de clientes.
- **Detecção de Entidades**: Automação de extração de informações importantes em documentos textuais.
- **Processamento de Linguagem Natural**: Refinamento de consultas de pesquisa com suporte para sinônimos e variações de termos.

## Aprendizados

Durante este processo, os principais aprendizados foram:
1. Como configurar um serviço de pesquisa utilizando o Azure.
2. Como enriquecer dados de forma automática com habilidades cognitivas.
3. Como realizar consultas complexas em grandes volumes de dados.
4. A importância de personalizar a indexação de acordo com o contexto dos dados.

## Recursos Úteis

- [Documentação Oficial do Azure Cognitive Search](https://learn.microsoft.com/pt-br/azure/search/search-what-is-azure-search)
- [Exemplo de API REST](https://learn.microsoft.com/en-us/rest/api/searchservice/)

## Como Contribuir

Sinta-se à vontade para clonar este repositório, sugerir melhorias e abrir issues!

