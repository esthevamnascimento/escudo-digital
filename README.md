# 🛡️ Projeto Escudo Digital

> Uma plataforma de educação e defesa para construir resiliência digital na população contra golpes online, transformando potenciais vítimas em uma primeira linha de defesa ativa.

Este repositório contém o código-fonte do painel de impacto do **Projeto Escudo Digital**, uma página única (single-page) interativa desenvolvida para apresentar a missão, as funcionalidades, as metas e o modelo de sustentabilidade da iniciativa.

**[Acesse a Demonstração Online](URL_DA_SUA_PAGINA_AQUI)**

---

## 📖 Tabela de Conteúdos

* [Sobre o Projeto](#-sobre-o-projeto)
* [Principais Funcionalidades](#-principais-funcionalidades)
* [Tecnologias Utilizadas](#-tecnologias-utilizadas)
* [Como Executar o Projeto](#-como-executar-o-projeto)
  * [Pré-requisitos](#pré-requisitos)
  * [Instalação e Configuração](#instalação-e-configuração)
* [Como Contribuir](#-como-contribuir)
* [Licença](#-licença)
* [Contato](#-contato)

---

## 🎯 Sobre o Projeto

O **Escudo Digital** nasceu para combater a epidemia silenciosa de fraudes online, que causa danos financeiros e emocionais devastadores, especialmente a públicos vulneráveis como idosos e pessoas com baixa letramento digital.

Nossa abordagem é a de um **"Vacinador Digital"**: uma plataforma gratuita e acessível que capacita os cidadãos através de quatro pilares principais, combinando educação preventiva com ferramentas de defesa em tempo real.

---

## ✨ Principais Funcionalidades

O painel demonstra as quatro funcionalidades centrais da plataforma:

1.  **🎓 Simulador de Golpes:** Um ambiente seguro onde os usuários podem interagir com simulações realistas de golpes comuns (SMS, e-mail, etc.) para aprender a identificar os "sinais vermelhos" na prática, sem correr riscos.

2.  **🔍 Verificador Rápido com IA:** Uma ferramenta que utiliza a **API do Gemini** para analisar textos e links suspeitos. O usuário cola a mensagem duvidosa e recebe uma análise de risco instantânea (Baixo, Médio ou Alto), com uma explicação dos pontos de atenção.

3.  **🔔 Alertas em Tempo Real:** Um sistema de notificações que mantém os usuários informados sobre novos tipos de golpes que estão circulando, garantindo que estejam sempre um passo à frente dos criminosos.

4.  **📚 Biblioteca de Defesa:** Uma central de conhecimento com guias simples e visuais sobre temas essenciais de segurança digital, como a criação de senhas fortes e a identificação de sites falsos.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído com tecnologias web modernas, focando em simplicidade e performance:

* **HTML5**
* **Tailwind CSS:** Para uma estilização rápida e responsiva.
* **JavaScript (Vanilla):** Para toda a interatividade, incluindo a navegação por abas e a lógica dos gráficos.
* **Chart.js:** Para a visualização de dados e KPIs de impacto social.
* **Google Gemini API:** Para a funcionalidade de análise de mensagens suspeitas.

---

## 🚀 Como Executar o Projeto

Siga os passos abaixo para ter uma cópia do projeto rodando localmente.

### Pré-requisitos

* Um navegador de internet moderno (Chrome, Firefox, etc.).
* Um editor de código (como o VS Code).
* Uma chave de API do [Google AI Studio](https://aistudio.google.com/) para usar o modelo Gemini.

### Instalação e Configuração

1.  **Clone o repositório:**
    ```sh
    git clone [https://github.com/seu-usuario/escudo-digital.git](https://github.com/seu-usuario/escudo-digital.git)
    ```

2.  **Navegue até o diretório:**
    ```sh
    cd escudo-digital
    ```

3.  **Abra o arquivo `index.html`** no seu navegador para ver a página.

4.  **🚨 Configurar a Chave de API do Gemini (MUITO IMPORTANTE):**

    Para que o "Verificador Rápido" funcione, você precisa configurar sua chave de API. **NUNCA** deixe sua chave diretamente no código que vai para o GitHub.

    * No arquivo `index.html`, encontre a linha dentro da tag `<script>`:
        ```javascript
        const apiKey = "AIzaSyC9EPl0lfa_qWDAdeQDu3_LIVRVpdc_d38"; // <-- NUNCA FAÇA COMMIT COM A CHAVE AQUI
        ```
    * **Para desenvolvimento local**, você pode substituir o valor da `apiKey` pela sua chave real. **Apenas lembre-se de NUNCA fazer commit desta alteração.**
    * **Para produção**, a melhor prática é usar variáveis de ambiente e um backend que atue como proxy para a API do Gemini, protegendo sua chave.

---

## 🤝 Como Contribuir

Contribuições são o que tornam a comunidade de código aberto incrível. Qualquer ajuda é **muito bem-vinda**.

1.  Faça um **Fork** do projeto.
2.  Crie uma nova **Branch** (`git checkout -b feature/NovaFuncionalidade`).
3.  Faça o **Commit** das suas alterações (`git commit -m 'Adiciona NovaFuncionalidade'`).
4.  Faça o **Push** para a Branch (`git push origin feature/NovaFuncionalidade`).
5.  Abra um **Pull Request**.

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

## 📧 Contato

Seu Nome - [@seu_twitter](https://twitter.com/seu_twitter) - seu_email@exemplo.com

Link do Projeto: [https://github.com/seu-usuario/escudo-digital](https://github.com/seu-usuario/escudo-digital)
