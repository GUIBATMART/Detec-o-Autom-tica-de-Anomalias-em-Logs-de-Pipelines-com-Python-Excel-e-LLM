# 🚀 Projeto 5 - Detecção Automática de Anomalias em Logs de Pipelines

## 📌 Sobre o Projeto

Este projeto demonstra como integrar **Python + Excel + Inteligência Artificial** para criar um sistema automatizado de análise de logs de pipelines de dados.

O processo realiza:

1. Leitura de dados de execução em planilha Excel  
2. Envio das informações para um modelo de IA  
3. Análise automática de possíveis anomalias  
4. Geração de relatório em formato Word (.docx)  

Tudo de forma automatizada.

---

## 🧠 Tecnologias Utilizadas

- Python
- Pandas
- python-docx
- LangChain
- Ollama
- Llama3 (LLM local)
- Excel

---

## ⚙️ Como Funciona

1. O script carrega o arquivo `logs_pipeline.xlsx`
2. Para cada execução do pipeline:
   - Envia os dados para o modelo LLM
   - Solicita análise especializada
3. O modelo retorna feedback analítico
4. O sistema gera automaticamente:
   - Arquivo `projeto5-resultado.docx`
   - Impressão dos resultados no terminal

---

## 📂 Estrutura Esperada do Excel

A planilha deve conter colunas como:

- pipeline_id
- execution_id
- start_time
- end_time
- status
- execution_time_minutes
- operating_system
- processing_type
- attempt_number

---

## 🔧 Como Executar

### 1️⃣ Criar ambiente virtual

```bash
python -m venv venv
venv\Scripts\activate
