# 📝 Análise de Diferenças: Código Próprio vs. Gabarito

Este documento registra as diferenças encontradas entre a minha resolução da tarefa de CSS e o gabarito oficial fornecido pelo professor.

## 1. Seletor de Classe (`.card`)

**Meu Código:**
```css
.card {
    background-color: white;
    border-radius: 10px; 
    width: 200px;
}
```
* **Diferença:** No meu código foram definidas apenas a cor de fundo, as bordas arredondadas e a largura. No gabarito, foram adicionadas regras de espaçamento interno (padding: 15px;) e externo (margin: 10px;). Além disso, não foi colocada no meu código a propriedade display: inline-block;, que é fundamental no gabarito para fazer com que os cards fiquem alinhados um ao lado do outro na tela, em vez de empilhados.

### 2. Pseudo-classe (`button:hover`)
```css
  button:hover {
    background-color: #27ae60; 
    color: white;              
    cursor: pointer;           
  }
  ```
* **Diferença:**Faltou a propriedade color: white;. No gabarito, além do fundo ficar verde no hover, a cor do texto do botão muda para branco para garantir um bom contraste e leitura.


  
