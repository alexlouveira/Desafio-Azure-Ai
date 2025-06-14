# Notas sobre a Experiência com Azure Speech Studio e Language Studio

## Azure Speech Studio
- **Objetivo**: Testar a conversão de fala em texto e texto em fala.
- **Resultado**: Utilizei o serviço para transcrever áudio em texto e gerar áudio a partir de um texto. Consegui ajustar a voz e o idioma para obter um resultado adequado.
  
  **Passos seguidos**:
  1. Criei uma chave de API no portal do Azure.
  2. Testei a conversão de áudio para texto utilizando uma gravação simples.
  3. Criei um projeto de texto para fala, usando diferentes opções de voz.

  **Desafios**:
  - Compreender as nuances de como o serviço lida com diferentes idiomas.

## Azure Language Studio
- **Objetivo**: Analisar um texto em português para identificar sentimentos e frases-chave.
- **Resultado**: O serviço foi capaz de determinar com precisão o sentimento do texto (positivo/negativo) e extrair frases-chave relevantes.

  **Passos seguidos**:
  1. Subi um texto não estruturado.
  2. Testei as funcionalidades de **Análise de Sentimentos** e **Extração de Frases-Chave**.

  **Desafios**:
  - A interpretação do sentimento de textos complexos, com uso de jargões e termos técnicos.

## Capturas de Tela
Adicionei capturas de tela relevantes na pasta `images/` para ilustrar o uso das ferramentas. As imagens incluem:
- Tela do Speech Studio após a conversão de fala em texto.
- Resultado da extração de frases-chave em um texto de exemplo.
