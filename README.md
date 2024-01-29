<p align="center">
  <img src="https://camo.githubusercontent.com/a4e71a0942263821f4cb9213b2808af909e46967d9ed3ccee6e7e122f276efd6/68747470733a2f2f696d672e69636f6e73382e636f6d2f65787465726e616c2d74616c2d72657669766f2d726567756c61722d74616c2d72657669766f2f39362f65787465726e616c2d726561646d652d69732d612d656173792d746f2d6275696c642d612d646576656c6f7065722d6875622d746861742d6164617074732d746f2d7468652d757365722d6c6f676f2d726567756c61722d74616c2d72657669766f2e706e67" width="100" />
</p>
<p align="center">
    <h1 align="center">Exercício Material UI</h1>
</p>
<p align="center">
    <em>Exercício para a disciplina de Técnicas Avançadas de CSS do curso de Desenvolvimento Web Front-End - PUC Minas</em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/camilarozendo/exercicioMaterialUI?style=default&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/camilarozendo/exercicioMaterialUI?style=default&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/camilarozendo/exercicioMaterialUI?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/camilarozendo/exercicioMaterialUI?style=default&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
	<!-- default option, no dependency badges. -->
</p>
<hr>

## 🔗 Quick Links

> - [ Overview](#-overview)
> - [ Features](#-features)
> - [ Repository Structure](#-repository-structure)
> - [ Getting Started](#-getting-started)
>   - [ Installation](#-installation)
>   - [ Running exercicioMaterialUI](#-running-exercicioMaterialUI)
> - [ Contributing](#-contributing)
> - [ License](#-license)

---

## 📍 Overview

Esta aplicação React é um exercício que tem como objetivo a utilização da biblioteca Material-UI (MUI) para criar uma interface com componentes estilizados e um tema personalizado.

---

## 🔮 Features

#### Estrutura do Projeto:
* 'App.js': Este é o componente principal que representa a estrutura da aplicação. Ele importa estilos, componentes MUI (Button, Typography), e define um componente estilizado chamado 'MyCustomButton'.
* 'index.js': Este é o ponto de entrada da aplicação, onde é definido o tema utilizando o 'ThemeProvider' do Material-UI, e o componente 'App' é renderizado dentro desse contexto temático.

#### Material-UI (MUI):
* O código faz uso de componentes fornecidos pela biblioteca Material-UI, como 'Button' e 'Typography'.
* O tema da aplicação é personalizado usando o 'ThemeProvider' e o método 'createTheme' do Material-UI.

#### Estilização Personalizada:
* O componente 'MyCustomButton' é criado usando a função 'styled' do Material-UI, permitindo a estilização personalizada. No exemplo dado, o botão tem um preenchimento (padding) que é definido com base no espaçamento do tema.

Em resumo, a aplicação é um exemplo básico de como usar o Material-UI com temas personalizados e estilização para criar uma interface de usuário React estilizada.

## 🧩 Repository Structure

```sh

└── exercicioMaterialUI/
   ├── package-lock.json
   ├── package.json
   ├── public/
   │   ├── index.html
   │   ├── logo.png
   │   └── manifest.json
   └── src/
      ├── App.js
      ├── index.js
      ├── logo.svg
      ├── reportWebVitals.js
      └── styles.css

```

---

## 🚀 Getting Started

***Requirements***

Ensure you have the following dependencies installed on your system:

* **Node.js**

### ⚙️ Installation

1. Clone the exercicioMaterialUI repository:

```sh
git clone https://github.com/camilarozendo/exercicioMaterialUI
```

2. Change to the project directory:

```sh
cd exercicioMaterialUI
```

3. Install the dependencies:

```sh
npm install
```

### 👩‍💻 Running exercicioMaterialUI

Use the following command to run exercicioMaterialUI:

```sh
node app.js
```

---


##  🤝 Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github/camilarozendo/exercicioMaterialUI/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github/camilarozendo/exercicioMaterialUI/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github/camilarozendo/exercicioMaterialUI/issues)**: Submit bugs found or log feature requests for exercicioMaterialUI.

<details closed>
    <summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**: Clone the forked repository to your local machine using a Git client.
   ```sh
   git clone https://github.com/camilarozendo/exercicioMaterialUI
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to GitHub**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.

Once your PR is reviewed and approved, it will be merged into the main branch.

</details>

---

##  📄 License

MIT License

Copyright (c) [2023] [Camila Rozendo]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---


[**Return**](#-quick-links)

---