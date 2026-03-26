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

* **Diferença:**No meu código foram definidas apenas a cor de fundo, as bordas arredondadas e a largura. No gabarito, foram adicionadas regras de espaçamento interno (padding: 15px;) e externo (margin: 10px;). Além disso, não foi colocada no meu código a propriedade display: inline-block;, que é fundamental no gabarito para fazer com que os cards fiquem alinhados um ao lado do outro na tela, em vez de empilhados.
  
