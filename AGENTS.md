# AGENTS.md

Este arquivo contém instruções, diretrizes de design e padrões de projeto da **EO Consultoria Acadêmica** para orientar agentes de IA (como Antigravity, Cursor, Devin, etc.) que venham a dar manutenção ou implementar novas funcionalidades neste repositório.

## Tecnologias e Setup

O projeto é estático e super leve:
- **Tecnologias principais**: HTML5 puro e CSS3 moderno (sem Tailwind CSS ou pré-processadores).
- **Sem Bundlers/Dependências**: Não há gerenciadores de pacotes (`npm`, `pnpm`, `yarn`), scripts de compilação ou processos de build.
- **Como Executar**: Basta abrir o arquivo `index.html` diretamente no navegador. Para recarregamento automático no VS Code, utilize a extensão **Live Server**.

---

## Estrutura do Projeto

```text
consultoria-academica/
|-- assets/
|   |-- css/
|   |   `-- styles.css       # Estilo principal e sistema de design
|   `-- images/
|       |-- branding/        # Logotipos e identidade visual da marca
|       |-- generated/       # Imagens geradas e referências visuais
|       |-- profile/         # Fotos profissionais da fundadora
|       |-- testimonials/    # Prints de avaliações/depoimentos dos clientes
|       `-- whatsapp/        # Elementos flutuantes/ícones do WhatsApp
|-- AGENTS.md                # Diretrizes para agentes de IA (este arquivo)
|-- index.html               # Página única (Landing Page)
`-- README.md                # Visão geral do projeto para humanos
```

---

## Diretrizes de Desenvolvimento e Código

### 1. Estilização (CSS)
- Todo o estilo reside em [assets/css/styles.css](file:///c:/Users/elayn/OneDrive/Documentos/GitHub/consultoria-academica/assets/css/styles.css).
- **Sistema de Cores e Tipografia**: Definidos por variáveis CSS declaradas no bloco `:root` de `styles.css`. Sempre utilize essas variáveis (`var(--bg)`, `var(--brand)`, etc.) em vez de cores hardcoded.
- **Responsividade**: Utilize CSS Grid, Flexbox e Media Queries no final do arquivo `styles.css` para manter o layout impecável em celulares, tablets e desktops.
- **Componentes**: Mantenha classes semânticas e organizadas para componentes reutilizáveis como `.card`, `.button`, `.service-card`, `.testimonial-card`.

### 2. Estrutura e Semântica (HTML)
- O arquivo principal é o [index.html](file:///c:/Users/elayn/OneDrive/Documentos/GitHub/consultoria-academica/index.html).
- Escreva HTML5 semântico (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- Certifique-se de que os elementos interativos tenham IDs descritivos e atributos acessíveis (como `aria-label`, `alt` para imagens e `tabindex` adequado).
- Utilize entidades HTML no texto caso necessário para caracteres especiais (`&html;`) de forma consistente com o código atual.

### 3. Imagens e Mídia
- Salve novas imagens na subpasta correspondente sob `assets/images/`.
- Evite placeholders externos. Se precisar de novas imagens de demonstração ou ilustrativas, use a ferramenta de geração de imagem.
- Use sempre caminhos relativos para os arquivos do projeto (`assets/images/branding/Logo marca.png`). Nunca use caminhos absolutos do sistema local.

---

## Diretrizes Estéticas e de Design

O projeto adota uma estética premium e minimalista voltada ao público acadêmico (estudantes, professores e pesquisadores). 
- **Cores**: Tons sofisticados de azul, bege claro e dourado/acabamentos elegantes.
- **Tipografia**: Títulos acadêmicos com fontes serifadas (`Cormorant Garamond`) e blocos de leitura com fontes sem serifa (`Manrope`/`Inter`/`Poppins`).
- **Micro-animações e Interações**: Efeitos sutis de transição (`transition: all 0.3s ease`) ao passar o mouse (hover) em botões, links de navegação e cartões de serviços.

---

## Contatos Configurados no Projeto

Se precisar alterar links de conversão ou dados de contato, os valores atuais configurados no HTML são:
- **WhatsApp**: `https://wa.me/5598985052987` (com texto de inicialização personalizado).
- **E-mail**: `eoconsultoria.academica@gmail.com`
- **Instagram**: `https://instagram.com/_elayne_oliveira` e `https://www.instagram.com/eoconsultoriaacademica/`
