# 📝 Análise de Diferenças: Código Próprio vs. Gabarito

Este documento registra as diferenças encontradas entre a minha resolução da tarefa de CSS e o gabarito oficial fornecido pelo professor. A estrutura do HTML e a maior parte dos seletores estavam corretas, com divergências pontuais em três blocos específicos de CSS.

Abaixo estão os detalhes do que está diferente em cada parte:

### 1. Seletor de Classe (`.card`)
* **Situação:** Diferença nas propriedades de alinhamento e espaçamento.
* **Código Próprio:** Foram definidas apenas as propriedades de cor de fundo, borda arredondada e largura (`background-color`, `border-radius`, `width`).
* **Gabarito:** Está desse jeito, incluindo regras de espaçamento interno, externo e comportamento de bloco:
  ```css
  .card{
            background-color: white;
            border-radius: 10px; 
            width: 200px;
        }
  ```css
  .card {
    background-color: white;   
    border-radius: 10px;      
    width: 200px;             
    padding: 15px;            
    margin: 10px;             
    display: inline-block;    
  }
