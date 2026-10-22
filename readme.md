# 🏢 Gestão Horizonte

Protótipo de um **Sistema de Gestão Empresarial** para a **Horizonte Soluções**, empresa fictícia que vende produtos e presta serviços. Projeto acadêmico da disciplina de **Git e GitHub**, desenvolvido de forma individual.

> ⚠️ Este é um protótipo demonstrativo. Os dados são fictícios e os formulários são apenas ilustrativos: **nada é salvo**.

---

## 📌 O problema da empresa

A Horizonte Soluções cresceu rápido e hoje controla clientes, produtos, pedidos e relatórios com anotações e planilhas separadas. O resultado são cadastros duplicados, informações desencontradas e dificuldade para acompanhar a operação.

## 🎯 Objetivo do protótipo

Apresentar páginas simples e navegáveis, com identidade visual coerente, que mostrem como um sistema de gestão unificado poderia organizar a operação da empresa. Nesta etapa, o foco é **mostrar o caminho percorrido no desenvolvimento**: versionamento com Git, revisão por Pull Requests, tags e releases.

## ✨ Funcionalidades previstas

| Módulo | Descrição | Arquivo |
| --- | --- | --- |
| Painel inicial | Apresentação do sistema, menu e resumo dos módulos | `index.html` |
| Clientes | Cadastro ilustrativo e lista de clientes de exemplo | `clientes.html` |
| Produtos | Formulário e catálogo fictício | `produtos.html` |
| Pedidos | Dados de pedidos ilustrativos e seus status | `pedidos.html` |
| Relatórios | Indicadores e tabela com dados simulados | `relatorios.html` |

## 🛠️ Tecnologias utilizadas

- **HTML5** e **CSS3** (uma única folha de estilos compartilhada)
- **Git** e **GitHub** para versionamento e colaboração
- **VS Code** como editor

Não há backend, banco de dados nem bibliotecas externas.

### Requisitos para visualizar

Apenas um navegador web atual (Chrome, Firefox, Edge ou similar).

## 🚀 Como obter e abrir o projeto

```bash
# 1. Clonar o repositório
git clone https://github.com/JulianaRoSilva/gestao_horizonte.git

# 2. Entrar na pasta
cd gestao_horizonte
```

Depois, abra o arquivo `index.html` no navegador (clique duas vezes nele ou use a extensão *Live Server* do VS Code) e navegue pelo menu.

## 🗂️ Estrutura de pastas

```text
gestao_horizonte/
├── index.html        # Painel inicial
├── clientes.html     # Módulo de clientes
├── produtos.html     # Módulo de produtos
├── pedidos.html      # Módulo de pedidos
├── relatorios.html   # Módulo de relatórios
├── css/
│   └── estilo.css    # Identidade visual compartilhada
├── README.md         # Este documento
└── .gitignore        # Itens ignorados pelo Git
```

## 🌿 Fluxo de branches

O projeto usa dois níveis de branches fixas e branches de trabalho curtas:

- **`main`**: branch estável. Só recebe a versão final, via Pull Request vindo da `develop`.
- **`develop`**: branch de integração. Recebe todas as tarefas por Pull Request.

**Branches de trabalho** (sempre criadas a partir da `develop` e integradas a ela por Pull Request):

| Tipo | Branch | Responsabilidade |
| --- | --- | --- |
| Funcionalidade | `feature/clientes` | Página do módulo de clientes |
| Funcionalidade | `feature/produtos` | Página do módulo de produtos |
| Funcionalidade | `feature/pedidos` | Página do módulo de pedidos |
| Funcionalidade | `feature/relatorios` | Página do módulo de relatórios |
| Correção | `fix/menu` | Correção de um link incorreto no menu |
| Correção | `fix/visual` | Correção de uma inconsistência visual no CSS |


## 📍 Situação atual do desenvolvimento

- [x] Estrutura inicial do projeto e folha de estilos
- [x] Painel inicial (`index.html`)
- [ ] Módulo de clientes
- [ ] Módulo de produtos
- [ ] Módulo de pedidos
- [ ] Módulo de relatórios
- [ ] Correção do menu
- [ ] Correção visual
- [ ] Conflito local resolvido
- [ ] Conflito em Pull Request resolvido
- [ ] Entrega final (`develop` → `main`)

### 🔜 Próximas entregas

Integração dos módulos de cadastros, depois pedidos e relatórios, seguidos das correções, da resolução dos conflitos e da revisão final da documentação.

> Esta seção será atualizada a cada release importante.

## 🏷️ Histórico de versões

| Versão | Marco | Conteúdo | Status |
| --- | --- | --- | --- |
| `v0.1.0` | Protótipo inicial | Página inicial, README inicial e estrutura do projeto | Planejada |
| `v0.2.0` | Cadastros | Módulos de clientes e produtos | Planejada |
| `v0.3.0` | Operação | Módulos de pedidos e relatórios | Planejada |
| `v1.0.0` | Entrega final | Correções, conflitos resolvidos e documentação revisada | Planejada |

👉 Todas as versões publicadas estão em: [Releases do projeto](https://github.com/JulianaRoSilva/gestao_horizonte/releases)


## 👩‍💻 Autoria

- **Aluna responsável:** Juliana Rodrigues
- **Curso:** Técnico em Desenvolvimento de Sistemas Bilíngue, Senac São Leopoldo
- **Disciplina:** Git e GitHub
- **Turma:** 26-1N
- **Data:** 22/10/2026
- **GitHub:** [JulianaRoSilva](https://github.com/JulianaRoSilva)

---

© 2026 Horizonte Soluções. Protótipo educacional com dados fictícios.