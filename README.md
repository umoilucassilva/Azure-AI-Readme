# Análise de Sentimentos com Language Studio no Azure AI

## Descrição do Projeto
Este desafio é sobre os recursos de IA da Microsoft Azure, especificamente o **Azure AI Language Studio** e o **Azure Speech Studio**. O objetivo principal foi explorar como a inteligência artificial pode interpretar a linguagem natural para analisar sentimentos em textos e converter fala em texto.

## Processos da Implementação

### 1. Análise de Sentimentos (Language Studio)
- Acessei o [Language Studio](https://language.cognitive.azure.com/).
- Selecionei a funcionalidade **"Analyze sentiment and opinions"**.
- Configurei o idioma para "Português (Brazil)".
- **Teste Realizado:** Inseri frases variadas para testar a precisão da IA.

### 2. Conversão de Texto e Fala (Speech Studio)
- Explorei o recurso de **Text-to-Speech** para converter as análises textuais em áudio sintético.
- Testei diferentes vozes neurais em português para verificar a naturalidade da entonação.

## Aprendizados

Durante o laboratório, pude perceber alguns pontos cruciais sobre as ferramentas cognitivas da Azure:

1.  **Níveis de Confiança (Confidence Scores):** A IA não diz apenas se é "Bom" ou "Ruim", ela entrega uma porcentagem de certeza (0 a 1). Isso pode criar gatilhos automáticos (ex: se a confiança de um feedback negativo for > 90%, abrir um ticket urgente no suporte).
2.  **Análise de Sentenças vs. Documento:** A ferramenta consegue analisar o sentimento geral do texto e também quebrar o sentimento por frase. Isso ajuda a entender nuances em comentários longos que começam elogiando mas terminam criticando.
3.  **Facilidade de Integração:** O Language Studio gera o JSON de resposta automaticamente, o que facilita a integração com outras aplicações.

## 🏁 Conclusão
O uso de serviços ferramentas como o Azure Language elimina a necessidade de treinar modelos de Machine Learning do zero para tarefas comuns de NLP (Processamento de Linguagem Natural). A precisão da análise de sentimentos em português foi boa e tem potêncial pra diversas aplicações.
