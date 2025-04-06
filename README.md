# 💳 Cartão Nubank Interativo

<img src="https://github.com/souzaseven/Cart-o-Nubank/blob/Desafios/Cart%C3%A3o%20Nubank/cardexemple.png?raw=true" width="20%" alt="Preview">


Simulação realista de cartão Nubank com efeito 3D interativo.

## ✨ Funcionalidades

### 🖱️ Interatividade 3D
- **Movimento Parallax**: Responde ao movimento do mouse
- **Efeito de Rotação**: Perspectiva 3D realista
- **Transição Suave**: Animação ao sair da área

### 🎨 Design Fiel
- Cores oficiais do Nubank (roxo #820ad1)
- Elementos gráficos:
  - Logo Mastercard
  - Chip do cartão
  - Identificação do titular

## 🛠 Tecnologias
Frontend:
- HTML5 Semântico
- CSS3 (Flexbox + Transformações 3D)
- JavaScript (Interações)



🎨 Estilos CSS
.container {
  background-color: #820ad1;
  border-radius: 10px;
  box-shadow: 5px 8px 8px #000;
  transform: perspective(500px) rotateX(0) rotateY(0);
  transition: transform 400ms;
}
