# 🤝 Como Contribuir para o PortfolioHUB

Seu interesse em contribuir para o PortfolioHUB é muito apreciado! Este documento descreve as diretrizes para garantir um processo de contribuição suave e seguro.

## 🔗 1. Requisitos e Processo

O PortfolioHUB utiliza o **GitHub Flow** para gerenciamento de código e versionamento. Para contribuir, siga estas etapas:

### 1.1. Configuração Inicial

1.  **Fork:** Crie um *fork* (cópia) deste repositório para o seu próprio perfil.
2.  **Clone:** Clone o *fork* localmente na sua máquina.
3.  **Branch:** Crie uma nova *branch* para sua funcionalidade ou correção.
    * **Convenção de Nomenclatura:** Use nomes descritivos, como `feat/nova-pagina-projeto` ou `fix/ajuste-css-mobile`.

    ```bash
    git checkout -b feature/sua-nova-funcionalidade
    ```

### 1.2. Commit e Versionamento

* **Commits Atômicos:** Faça *commits* pequenos e focados em uma única alteração.
* **Mensagens de Commit:** Utilize a convenção de mensagens (ex: `feat:`, `fix:`, `docs:`):
    * `feat: Adiciona novo cartão de projeto para ML`
    * `fix: Corrige erro de link no rodapé`

### 1.3. Submissão (Pull Request)

1.  Faça o *push* da sua nova *branch* para o seu *fork* no GitHub.
2.  Abra um **Pull Request (PR)** do seu *fork* para a *branch* `main` do repositório original.

## 🛡️ 2. Política de Controle de Acesso

**A branch `main` é protegida e representa o código em produção (o site no ar).**

* **Revisão Obrigatória:** Todo Pull Request (PR) deve ser revisado por um mantenedor antes de ser mesclado (*merge*).
* **Teste:** Seu PR deve demonstrar que as alterações foram testadas e não introduzem erros visíveis.
* **Requisitos:** O PR só poderá ser mesclado se atender às regras de **Branch Protection** definidas (aprovado por *review* e sem conflitos).
