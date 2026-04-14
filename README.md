# 🚀 ExpertNet4

Sistema web simples desenvolvido com **HTML, CSS e JavaScript puro**, focado na manipulação de imagens e organização em grid, com uso prático voltado para **impressão gráfica**.

---

## 📌 Objetivo

Facilitar o processo de organização e preparação de imagens (como QR Codes e plaquinhas PIX) para impressão, garantindo:

- Padrão de tamanho  
- Alinhamento correto  
- Economia de espaço (nível gráfica)

---

## 🧠 Como funciona

A lógica do sistema é simples e direta:

1. O usuário seleciona várias imagens  
2. O JavaScript lê os arquivos usando `FileReader`  
3. As imagens são exibidas automaticamente na tela  
4. Cada imagem pode ser manipulada:
   - Clique → remove a imagem  
   - Teclas → rotacionam a imagem  
5. O CSS organiza tudo em formato de grid pronto para impressão  

---

## 📂 Estrutura do projeto

```
📁 expertnet4
 ├── index.html
 ├── style.css
 ├── script.js
```

---

## 📱 Funcionalidades

- Upload de múltiplas imagens  
- Exibição automática em grid  
- Remoção com clique  
- Rotação de imagens  
- Padronização de tamanho  
- Layout otimizado para celular  
- Layout pronto para impressão  

---

## 🖨️ Impressão (diferencial)

O sistema usa CSS específico para impressão com medidas reais:

```css
@media print {
  img {
    width: 6.5cm;
    height: 7cm;
  }
}
```

✔ Evita cortes errados  
✔ Mantém proporção  
✔ Segue padrão de gráfica  

---

## 🎯 Casos de uso

- QR Codes para pagamento  
- Plaquinhas PIX  
- Etiquetas  
- Materiais repetidos para impressão  

---

## ⚙️ Tecnologias utilizadas

- HTML5  
- CSS3  
- JavaScript (Vanilla)

---

## 💡 Filosofia do projeto

Este projeto foi desenvolvido com foco em:

- Praticidade  
- Lógica simples  
- Uso real no dia a dia  

Não tem foco em código “bonito”, e sim em **resolver o problema de forma eficiente**.

---

## 🔗 Acesse o projeto

👉 (adicione aqui o link do GitHub Pages)

---

## ✍️ Autor

**Antonio Gleison Pinto Viana**  
Fortaleza - CE  

---

## 🚧 Melhorias futuras

- Exportar direto para PDF  
- Drag and drop de imagens  
- Ajuste manual de posição  
- Versão em React  

---
