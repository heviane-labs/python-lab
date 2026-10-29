# 🧪 Catálogo de Exemplos Práticos

Esta pasta reúne scripts práticos, pequenos projetos e automações desenvolvidos para consolidar os conhecimentos descritos no [Roadmap de Estudos](../roadmap.md).

Cada exemplo é auto-contido e possui seu próprio guia `.md` detalhando pré-requisitos, instruções de execução e resultados esperados.

---

## 📋 Índice de Exemplos

| Exemplo | Guia | Descrição | Principais Bibliotecas | Fase do Roadmap | Nível |
| :--- | :--- | :--- | :--- | :---: | :---: |
| [`generate-excel.py`](generate-excel.py) | [Guia](generate-excel.md) | Geração de planilha de checklist de devolução veicular corporativo com estilos, bordas e validação de dados (dropdowns). | `openpyxl` | Fase 3 | Intermediário |

---

## 🚀 Como Executar um Exemplo

1. Certifique-se de que o ambiente virtual está ativo a partir da raiz do repositório:

   ```bash
   # Windows (PowerShell)
   .venv\Scripts\Activate.ps1

   # Linux/Mac
   source .venv/bin/activate
   ```

2. Instale as dependências requeridas pelo exemplo específico (consulte o `.md` do exemplo).
3. Execute o script a partir da raiz:

   ```bash
   python examples/<nome-do-script>.py
   ```

---

## 📐 Padrão para Novos Exemplos

Para manter o laboratório organizado ao criar novos estudos, siga a convenção abaixo:

1. **Código (`<nome-do-exemplo>.py`):**
   * Código limpo, seguindo as convenções da **PEP 8**.
   * Uso de type hints e docstrings explicativas.
   * Definição de ponto de entrada padrão:

     ```python
     if __name__ == "__main__":
         ...
     ```

2. **Documentação (`<nome-do-exemplo>.md`):**
   * Explicação do objetivo do script.
   * Dependências necessárias (`pip install ...`).
   * Comando de execução e saída esperada (ex: console, arquivo gerado, etc.).
3. **Atualização do Catálogo:**
   * Adicione o novo script à tabela de índice acima.
