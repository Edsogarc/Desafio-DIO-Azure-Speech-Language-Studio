# Desafio DIO: Azure Speech & Language Studio

## Introdução
Este projeto é a solução para o desafio "Dominando o Azure Speech e Language Studio" da plataforma DIO. O objetivo foi explorar e praticar o uso das ferramentas de inteligência artificial da Microsoft para análise de fala e linguagem natural.

## Tecnologias Utilizadas
* **Microsoft Azure**
* **Azure Speech Studio** (Serviço de Fala)
* **Azure Language Studio** (Serviço de Idioma)

## Processo de Execução

### 1. Azure Speech Studio
Eu utilizei o Speech Studio para **transcrever um áudio** para texto. As principais etapas foram:
1.  Criação de um recurso de Serviço de Fala no Azure.
2.  Upload de um arquivo de áudio de exemplo.
3.  Execução da funcionalidade de Speech-to-Text.

* **Análise e Insights:**
    * A precisão da transcrição foi alta, mesmo com ruído de fundo e o áudio na velocidade 1,5x.
    * Usei o reconhecimento de idioma com a opção "No início", que foi transcrito sem nenhum problema.

### 2. Azure Language Studio
A partir do texto transcrito, eu utilizei o Language Studio para realizar a análise de linguagem. As funcionalidades testadas foram:
1.  **Análise de Sentimento:** Para identificar a polaridade emocional do texto.
2.  **Extração de Frases-Chave:** Para resumir os pontos principais.
3.  **Reconhecimento de Entidades Nomeadas:** Para identificar nomes de pessoas, lugares, etc.

* **Análise e Insights:**
    * A ferramenta conseguiu identificar corretamente que o texto tinha um tom neutro e extraiu as frases principais com precisão.

## Conclusão
Este desafio me proporcionou um conhecimento prático valioso sobre como as ferramentas de IA do Azure funcionam. A combinação do Speech Studio e do Language Studio é poderosa para criar soluções que entendem e processam a comunicação humana, como a análise de chamadas de suporte ou a automatização de resumos de reuniões.

---
Feito com 💙 por Edson Garcia
