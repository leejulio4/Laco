# ◉ laço — Comparador de seguidores do Instagram

> **Análise avançada, privada e 100% local de conexões do Instagram diretamente no seu navegador.**

O **laço** é uma ferramenta web independente, ultraleve e sem servidores (serverless), projetada para comparar arquivos exportados do Instagram (formatos `.json` e `.html`) e identificar perfis que não te seguem de volta ou que saíram da sua lista de seguidores.

---

## 🔒 Privacidade e Segurança em Primeiro Lugar

- **Zero Acesso a Senhas/APIs:** Não solicita login, token, senha nem acesso à API do Instagram.
- **Processamento 100% Local:** Todo o parsing, comparação e processamento ocorrem exclusivamente na memória do seu navegador.
- **Sem Telemetria:** Nenhum dado, nome de usuário ou arquivo é enviado para servidores externos.
- **Respeito aos Limites da Meta:** Abertura de perfis organizada em lotes pequenos configuráveis para evitar bloqueios temporários no navegador.

---

## ⚡ Principais Recursos

- **Modos de Comparação:**
  - *Quem não segue de volta:* Compara a lista de perfis que você segue com seus seguidores atuais.
  - *Quem saiu da lista:* Compara duas exportações de seguidores em momentos diferentes para verificar perdas.
- **Filtro de Histórico Opcional:** Permite importar resultados ou históricos anteriores (`.csv` ou `.json`) para ocultar perfis que você já analisou.
- **Visualização por Lotes:** Botões de abertura em blocos de 5, 10 ou 20 perfis por vez para facilitar a verificação manual no Instagram.
- **Exportação Flexível:** Baixe o resultado limpo em formato `.csv`, `.json` ou grave um snapshot completo da sua lista de seguidores.
- **PWA Instalável:** Funciona como um aplicativo nativo no desktop ou celular e opera totalmente offline.
- **Suporte a Temas:** Alternância nativa entre modo claro (*Light*) e escuro (*Dark*) com persistência automática via `localStorage`.

---

## 📁 Como Baixar os Dados no Instagram

1. No aplicativo ou site do Instagram, vá em **Sua atividade** > **Baixar suas informações**.
2. Solicite a opção de **Baixar alguns dados** ou selecione **Seguidores e Seguindo**.
3. Escolha o formato **JSON** (recomendado) ou **HTML**.
4. Faça o download do arquivo compactado enviado pelo Instagram e extraia a pasta no seu computador.

---

## 🚀 Como Usar

1. Abra a aplicação no navegador (ou execute o arquivo `index.html` localmente).
2. No **Passo 01**, selecione o arquivo `following.json` (ou `.html`).
3. No **Passo 02**, selecione o arquivo `followers_1.json` (ou `.html`).
4. *(Opcional)* No **Passo 03**, carregue um arquivo de histórico para filtrar perfis já vistos.
5. Clique no botão **Comparar listas**.
6. Use a barra de busca, ordenação (A-Z / Z-A) ou abertura em lotes para visualizar os perfis.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3:** Variáveis CSS nativas, CSS Grid e Flexbox com design responsivo de alto contraste.
- **JavaScript Vanilla (ES6+):** Código limpo sem dependências de frameworks pesados ou bibliotecas externas.
- **Service Worker / Web App Manifest:** PWA integrado para suporte completo a uso offline.

---

## 📄 Licença

Este projeto é disponibilizado sob a licença [MIT](LICENSE).

---

*Isenção de Responsabilidade: Esta ferramenta é um projeto independente e não possui qualquer vínculo, patrocínio ou associação com o Instagram ou a Meta Platforms, Inc.*
