# <h1 align="center"> MouraBateria Smart Contract (Solidity) </h1>
![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=%20DESENVOLVIDO&color=GREEN&style=for-the-badge)

## Resumo do projeto
Este projeto consiste no desenvolvimento e implantação de um **Smart Contract (Contrato Inteligente)** escrito em **Solidity**. A aplicação, chamada `MouraBateria`, funciona como um registro descentralizado de baterias defeituosas em uma Blockchain compatível com Ethereum (como a Rede de Teste Sepolia).

O objetivo principal é demonstrar o ciclo completo de desenvolvimento Web3, desde a codificação do contrato em Solidity (incluindo lógica de manipulação de arrays como o "Swap and Pop") até a interface de usuário em HTML/JavaScript que interage com a Blockchain através do Ethers.js e MetaMask.

## 🔨 Funcionalidades do projeto

- **Registro** descentralizado de baterias defeituosas com campos como tipo, uso, número de série e lote.
- **Listagem** completa de todos os registros de baterias armazenados no contrato.
- **Remoção** de registros utilizando o padrão "Swap and Pop" para otimização de gás.
- **Atualização** de todos os dados de um registro existente.
- **Interação** com o contrato via frontend (HTML/JS) e a carteira MetaMask.
- **Transparência** e imutabilidade dos dados garantidas pela Blockchain.

## 📁 Acesso ao projeto

Você pode interagir com a aplicação diretamente pelo **deploy online** ou acessar o código-fonte:

- **🔗 Aplicação Online (Vercel):** [Moura Bateria - Controle de Defeito](https://moura-desafio.vercel.app/#)
- **💻 Código Fonte (GitHub):** [Acessar o código-fonte do Contrato e Frontend](URL_DO_SEU_REPOSITORIO)
- **⬇️ Baixar o Código:** [Baixar repositório completo](URL_DE_DOWNLOAD_DO_SEU_REPOSITORIO)
- 
## 🛠️ Abrir e rodar o projeto

1. **Clone ou baixe** o repositório.
2. **Implante o Contrato:** Utilize o **Remix IDE** para compilar e implantar o arquivo `MouraBateria.sol` em uma rede de testes (ex: Sepolia).
3. **Obtenha o Endereço:** Copie o **endereço do novo contrato** após a implantação.
4. **Configure o Frontend:** No arquivo `index.html` (ou no arquivo JS), substitua a variável `CONTRACT_ADDRESS` pelo novo endereço copiado.
5. **Execute a Aplicação:** Abra o arquivo `index.html` em seu navegador.
6. **Conecte o MetaMask:** Certifique-se de que o MetaMask está na rede de teste correta e conectado à sua aplicação.

## ✔️ Técnicas e tecnologias utilizadas

- **Solidity** (Linguagem do Smart Contract)
- **Ethereum** / EVM (Máquina Virtual Ethereum)
- **Rede de Teste** (Sepolia)
- **Remix IDE** (Para desenvolvimento e deploy)
- **HTML/CSS/JavaScript** (Para o Frontend)
- **Ethers.js** (Para a comunicação JavaScript/Blockchain)
- **MetaMask** (Para gerenciamento de carteira e transações)
- Padrão **"Swap and Pop"** para otimização de remoção de arrays.

![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

## Desenvolvido por [Abner Barreto e João Henrique].

| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/166763846?v=4" width=115><br><sub>Abner Barreto</sub>](https://github.com/AbnerBarretto) | [<img loading="lazy" src="https://github.com/lordpipoca.png" width=115><br><sub>João Henrique</sub>](https://github.com/lordpipoca) |
| :---: | :---: |
