# Gerador de PDF para Orçamento
Este programa em Python gera um arquivo PDF contendo um orçamento baseado em informações fornecidas pelo usuário. Ele utiliza a biblioteca fpdf para criar e formatar o documento.
## Ferramentas

![Logo do Python](https://static.wixstatic.com/media/4bef97_3fca4225935f490783ac9ecb3f27a8b1~mv2.png/v1/fill/w_256,h_256,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/python_logo.png)

- Linguagem de programação: Python

## Funcionalidades
- Solicita ao usuário detalhes do projeto:
  - Descrição do projeto
  - Quantidade de horas previstas
  - Valor da hora trabalhada
  - Prazo estimado
- Calcula o valor total do orçamento
- Gera um documento PDF formatado com as informações inseridas
## Bibliotecas Utilizadas
- fpdf: Utilizada para a criação e manipulação de arquivos PDF.
## Como Executar
1. Clone o repositório:
   
    ```
    git clone <repo-url>
    cd nome-do-projeto
    ```

3. Certifique-se de ter a biblioteca fpdf instalada:
   
    `pip install fpdf`
   
4. Execute o programa:
   
    `python nome_do_arquivo.py`
   
5. Insira as informações solicitadas quando o programa pedir.
6. O PDF será gerado no diretório do programa.
## Exemplo
```
Informe a descrição do projeto: Site institucional
Informe a quantidade de horas previstas: 40
Informe o valor da hora trabalhada: 50
Digite o prazo estimado: 2 semanas
```
Isso gerará um PDF contendo essas informações formatadas corretamente a partir do template utilizado.
