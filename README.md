# Sistema de Cálculo de Pagamento

Este sistema permite calcular o valor a ser recebido por um funcionário com base na quantidade de dias trabalhados.

## Requisitos

- Python 3.7 ou superior
- pip (gerenciador de pacotes Python)

## Instalação

1. Clone este repositório ou baixe os arquivos
2. Instale as dependências necessárias:
```bash
pip install -r requirements.txt
```

## Como usar

1. Execute o aplicativo:
```bash
streamlit run app.py
```

2. O navegador será aberto automaticamente com a interface do sistema
3. Preencha as informações do funcionário:
   - UF
   - Matrícula
   - Nome
   - Função
   - Código da Atividade
   - Valor de Referência
   - Percentual de Gratificação
   - Dias Trabalhados

4. Clique em "Calcular Pagamento" para ver o resultado

## Cálculos realizados

O sistema calcula:
- Valor diário (Valor de Referência / 30)
- Valor base total (Valor diário × Dias trabalhados)
- Gratificação (Valor base total × Percentual de gratificação)
- Valor total (Valor base total + Gratificação) 
