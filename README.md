# 📦 Image Editor (Node.js)

Projeto simples em Node.js para redimensionar imagens usando `sharp` e comprimir usando `compress-images`.

---

## ⚙️ Requisitos

- Node.js instalado
- Instalar dependências com:

```bash
npm install
npm install gifsicle@5.2.1 --save
```

---

## ▶️ Como usar

```bash
node app.js <caminho-da-imagem> <nova-largura>
```

**Exemplo:**

```bash
node app.js image.jpg 500
```

- A imagem redimensionada será salva em `./temp/output_resize.jpg`
- A imagem comprimida será salva em `./compressed/`

---

## 📁 Estrutura

```
.
├── app.js
├── temp/
│   └── output_resize.jpg
├── compressed/
└── package.json
```
---

## 🛠️ Tecnologias usadas

- [sharp](https://www.npmjs.com/package/sharp)
- [compress-images](https://www.npmjs.com/package/compress-images)
- [gifsicle](https://www.npmjs.com/package/gifsicle)
