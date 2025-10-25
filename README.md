# Sistema de Rastreabilidade Moura: Arquitetura de Próxima Geração (Next-Gen)

![Badge em Desenvolvimento](https://img.shields.io/static/v1?label=STATUS&message=EM+DESENVOLVIMENTO&color=FFD700&style=for-the-badge)

## 🎯 Visão Estratégica & Diferencial Competitivo

Este projeto é um **Produto Mínimo Viável (MVP)** de alta qualidade, focado em **UX Vencedora, Segurança Imediata** e um **Plano de Evolução Arquitetural** claro.

Nossa abordagem reconhece as limitações da manipulação de arrays na Blockchain e propõe a rota mais eficiente para a V2, garantindo que o investimento seja feito em uma solução escalável.

### Estratégia de Desenvolvimento (MVP + Roadmap)

| Característica | Solução Atual (MVP) | **Visão de Arquitetura V2** | Vantagem Competitiva |
| :--- | :--- | :--- | :--- |
| **Integridade do ID** | Array mutável (Swap-and-Pop) | **`Mapping` com ID Permanente** (ID imutável para 100% de Auditabilidade). | Essencial para rastreabilidade de longo prazo. |
| **Segurança Crítica** | **Controle de Acesso `onlyOwner`** | Gestão de Acesso Modular (`RBAC`) e Transferência de Propriedade. | **Maior segurança imediata** que a concorrência sem `onlyOwner`. |
| **UX de Auditoria** | Filtros em tempo real. | **Filtro Discreto/Minimalista** (Interface mais limpa do que a concorrência). | |

---

## 🎨 Design & Experiência do Usuário (UX/UI)

Priorizamos uma interface limpa e intuitiva, alinhada à identidade visual da Moura.

- **Filtro Minimalista (Destaque UX):** O filtro de busca é acionado por um **ícone discreto** e se expande suavemente, mantendo a interface despoluída (superando designs que usam filtros sempre visíveis).
- **Feedback Rico:** Uso de **Toast Notifications** para sucesso/erro e **Modal de Confirmação** para remoção.

---

## 🎨 Demonstração de Uso

<p align="center">
  <img src="https://raw.githubusercontent.com/AbnerBarretto/MouraDesafio/main/assets/VideoDemonstracaoMoura.gif" alt="Demonstração do Fluxo de Uso" width="850">
</p>

<p align="center"><em>Vídeo demonstrando o fluxo de Cadastro, Listagem e interação com o Smart Contract.</em></p>

---


## 🔨 Funcionalidades do Projeto

- **Registro** descentralizado de baterias defeituosas (tipo, uso, número de série e lote).
- **Listagem** completa de todos os registros armazenados no contrato.
- **Busca Avançada (UX):** Filtro por Número de Série e Tipo de Bateria.
- **Remoção** otimizada de registros usando o padrão *Swap and Pop* para reduzir custo de gás.
- **Controle de Acesso:** Funções de escrita restritas ao `onlyOwner`.

---

## ⚙️ Detalhes do Projeto e Tecnologias

- **Smart Contract:** `MouraBateria` em **Solidity**.
- **Segurança:** Implementação de **`onlyOwner`**.
- **Framework Web3:** **Ethers.js** (biblioteca moderna).
- **Rede de Deploy:** Arbitrum Sepolia.

### Configuração da Rede (Arbitrum Sepolia)

| Parâmetro | Valor |
| :--- | :--- |
| **Network Name** | Arbitrum Sepolia |
| **New RPC URL** | `https://sepolia-rollup.arbitrum.io/rpc` |
| **Chain ID** | `421614` |
| **Currency Symbol** | ETH |
| **Block Explorer URL** | [https://sepolia.arbiscan.io/](https://sepolia.arbiscan.io/) |

---

## 📁 Acesso e Execução

- **🔗 Aplicação Online (Vercel):** [Moura Bateria - Controle de Defeito](https://moura-desafio-3w3j.vercel.app/)
- **💻 Código Fonte (GitHub):** [Repositório MouraBateria](https://github.com/AbnerBarretto/MouraDesafio)

---

## 🚀 Próximos Passos e Otimizações Futuras (Roadmap)

Os seguintes recursos estão planejados para a próxima fase:

### Smart Contract (Segurança e Eficiência)

- [ ] **Otimizar Integridade (V2):** Migrar o array (`Bateria[]`) para um `mapping` com IDs permanentes.
- [ ] **Auditoria:** Adicionar `Events` em todas as funções de alteração de estado para melhorar a rastreabilidade.

### Front-end e Usabilidade (UX)

- [x] **Filtro Discreto/Minimalista:** Implementar filtro avançado por Número de Série e Tipo de Bateria. (Feito)
- [ ] **Reforçar Validação:** Adicionar validações de formato (RegEx) para campos críticos, além de impedir o cadastro de datas futuras.

---

## 👨‍💻 Desenvolvedores

Projeto desenvolvido por **Abner Barreto** e **João Henrique**.

| [<img loading="lazy" src="https://github.com/AbnerBarretto.png" width=115><br><sub>Abner Barreto</sub>](https://github.com/AbnerBarretto) | [<img loading="lazy" src="https://github.com/lordpipoca.png" width=115><br><sub>João Henrique</sub>](https://github.com/lordpipoca) |
| :---: | :---: |
