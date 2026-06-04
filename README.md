# Vitória Futebol Clube - Web Mockup

Este repositório contém o código-fonte de um **mockup (protótipo visual e funcional básico)** para um novo website do Vitória Futebol Clube. O projeto foi desenvolvido de forma independente como uma peça de portefólio, focando-se na modernização da presença online do clube, na experiência do utilizador (UX) e na centralização de informações essenciais para os adeptos e sócios.

🚀 **[CLICA AQUI PARA VISUALIZAR O MOCKUP ATIVO]**
*(Nota: Substitui este link pelo link do teu GitHub Pages após fazeres o deploy)*

## 📄 Sobre o Projeto

O objetivo principal deste projeto foi criar uma interface web que capturasse a mística e a identidade visual do Vitória FC (Verde e Branco), oferecendo ao mesmo tempo uma navegação intuitiva e fluida.

Embora seja um mockup estático (HTML/CSS/JS simples), simula uma *Single Page Application* (SPA), permitindo navegar entre as diferentes secções sem recarregar a página, proporcionando uma experiência de utilizador moderna.

## ✨ Funcionalidades do Mockup

*   **Navegação Fluida:** Menu interativo que alterna entre as secções (Início, Equipa, Sócios, Loja, História) instantaneamente.
*   **Identidade Visual Forte:** Uso consistente das cores do clube e design limpo.
*   **Centralização de Redes Sociais:** Links para Facebook, Instagram, X (Twitter), TikTok, YouTube e LinkedIn com ícones circulares no topo da página para fácil acesso.
*   **Secção Sócios:** Informação detalhada sobre vantagens, preçário de quotas e simulador de formulário de inscrição.
*   **Loja Oficial (Visual):** Exposição de produtos chave (camisolas oficiais, edições assinadas) com preços e botões de compra (simulados).
*   **História Imersiva:** Secção dedicada à história gloriosa do clube, incluindo a integração de **documentários do YouTube** que cobrem diferentes eras, como a "Década de Ouro", o Centenário e a história do Estádio do Bonfim.
*   **Destaque "Último Jogo":** Reportagem da consagração de campeão invicto, com funcionalidade "Ler mais" via JavaScript para otimização de espaço e galeria de fotos integrada.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando tecnologias web padrão, sem a necessidade de *frameworks* complexos, demonstrando solidez nos fundamentos:

*   **HTML5:** Estruturação semântica do conteúdo.
*   **CSS3:** Design responsivo, variáveis CSS, Flexbox, Grid e animações de *fade-in*.
*   **JavaScript (Vanilla):** Lógica para navegação entre páginas, funcionalidade "Ler mais" e manipulação básica do DOM.
*   **FontAwesome:** Biblioteca de ícones para redes sociais.

## 📈 Processo de Desenvolvimento e Evolução

Este projeto não nasceu pronto; ele evoluiu através de várias iterações baseadas em feedback simulado e autoavaliação, demonstrando capacidade de adaptação e melhoria contínua.

### Fases do Desenvolvimento:

1.  **Iteração Inicial (Conceito Base):** Criação da estrutura HTML base e da lógica de navegação em JavaScript. Definição das cores e tipografia iniciais.
2.  **Expansão de Conteúdo (Loja e Redes):**
    *   Integração de produtos específicos na Loja (Camisola Cardoso, Edição Assinada 25/26, etc.).
    *   Adição de links para X (Twitter), TikTok e LinkedIn.
3.  **Refinamento Estético e de UX:**
    *   Substituição dos botões de texto das redes sociais por ícones circulares e padronizados no topo da página.
    *   MUDANÇA DE COR: O site estava "demasiado branco"; foi introduzido um tom de fundo suave (verde-água/cinza) para dar mais corpo à identidade visual e reduzir a fadiga visual, mantendo o Verde e Branco como protagonistas.
    *   Transferência dos contactos da "Gestão de Sócios" e horários para serem exclusivos da página de Sócios, limpando o rodapé global.
4.  **Correção de Bugs e Padronização:**
    *   **Correção Crítica de Caminhos de Imagem:** Resolução do problema onde o logótipo e o ícone do separador (favicon) não apareciam no GitHub Pages. O erro consistia no uso de URLs absolutos do repositório (blob/main), corrigido para o uso de **caminhos relativos** (ex: `src="vfc_logo.png"`) assumindo que as imagens e o HTML estão na mesma pasta.
    *   Padronização dos nomes dos ficheiros: `vfc_logo.png` para o logo do cabeçalho e `vfc_ico.png` para o favicon.
5.  **Iteração Final (Otimização e Media):**
    *   Implementação da funcionalidade "Ler Mais" na secção "Último Jogo", permitindo reduzir o texto visível inicial sem perder a informação completa.
    *   Redesign do rodapé legal: transformação de colunas num alinhamento horizontal (linha) para um aspeto mais limpo e compacto.
    *   Integração profunda de documentários históricos do YouTube diretamente na secção de História, enriquecendo o conteúdo narrativo do clube.

---

### Como Utilizar

Sendo um projeto estático, não requer instalação. Para visualizar localmente:

1.  Clona o repositório: `git clone https://github.com/m4xw3b/VFC_Mockup.git`
2.  Navega até à pasta do projeto.
3.  Abre o ficheiro `index.html` em qualquer navegador web moderno.

*(Nota: Garante que as imagens `vfc_logo.png`, `vfc_ico.png` e qualquer outra imagem referenciada estão na mesma pasta que o ficheiro `index.html` para que carreguem corretamente.)*

---
**Autor:** Projeto desenvolvido por `[INSERIR O TEU NOME AQUI]`.
*Este é um projeto independente e não tem afiliação oficial com o Vitória Futebol Clube.*
