# MyCalculator

Uma calculadora simples desenvolvida com **React Native** utilizando componentes reutilizáveis, gerenciamento de estado com `useState` e estilização personalizada.

---

# 🚀 Tecnologias utilizadas

- React Native
- TypeScript
- Expo
- useState Hook
- StyleSheet API

---

# ✨ Funcionalidades

✅ Operações matemáticas básicas  
✅ Interface moderna  
✅ Botões reutilizáveis  
✅ Sistema de display dinâmico  
✅ Operadores matemáticos  
✅ Limpar display  
✅ Deletar caracteres  

---

# 📸 Screenshots

## Tela Inicial

![Tela Inicial](./Captura de tela 2026-05-13 120802.png)
<img src=
---

## Inserindo números

![Inserindo números](./assets/screenshots/input.png)

---

## Operação matemática

![Operação matemática](./assets/screenshots/operation.png)

---

## Resultado

![Resultado](./assets/screenshots/result.png)

---

# 📂 Estrutura do Projeto

```bash
📦 app
 ┣ 📂 Components
 ┃ ┗ 📂 utils
 ┃    ┣ 📜 Button.tsx
 ┃    ┗ 📜 Colors.ts
 ┣ 📂 screens
 ┃ ┗ 📜 Calculator.tsx
 ┗ 📜 index.tsx
```

---

# 🎨 Interface

A interface foi construída utilizando:

- `flexbox`
- `flexWrap`
- componentes reutilizáveis
- estilização dinâmica baseada no tipo do botão

---

# 🔥 Exemplo do componente Button

```tsx
<Button
  title="7"
  type="number"
  onPress={() => handleNumberInput('7')}
/>
```

---

# ⚙️ Instalação

Clone o projeto:

```bash
git clone https://github.com/seu-usuario/calculator-app.git
```

Entre na pasta:

```bash
cd calculator-app
```

Instale as dependências:

```bash
npm install
```

Execute o projeto:

```bash
npx expo start
```

---

# 🧠 Aprendizados

Durante o desenvolvimento foram praticados:

- Componentização
- Props
- Hooks
- Organização de código
- Manipulação de estado
- Estilização no React Native

---

# 👨‍💻 Autor

Luciz 🚀
