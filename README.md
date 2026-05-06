# EO Consultoria Academica

Site institucional da **EO Consultoria Academica**, desenvolvido em HTML e CSS puros para apresentar a consultoria, os servi&ccedil;os oferecidos, a trajet&oacute;ria profissional da fundadora e os canais de contato.

## Estrutura de pastas

```text
consultoria-academica/
|-- assets/
|   |-- css/
|   |   `-- styles.css
|   `-- images/
|       |-- branding/
|       |-- generated/
|       |-- profile/
|       |-- testimonials/
|       `-- whatsapp/
|-- index.html
`-- README.md
```

## Visao geral

O projeto foi organizado como uma landing page de apresentacao, com foco em:

- transmitir mais profissionalismo e autoridade
- facilitar a leitura do conteudo
- destacar os servicos da consultoria
- gerar contato rapido pelo WhatsApp, e-mail e Instagram
- funcionar bem em desktop e mobile

## Estrutura da pagina

O site esta dividido nas seguintes secoes:

- `Hero`: apresentacao principal da marca, proposta de valor e chamada para contato
- `Sobre a consultoria`: resumo institucional
- `Sobre`: apresentacao da fundadora, formacao e experiencia
- `Servi&ccedil;os`: lista dos principais atendimentos oferecidos
- `Como funciona`: explicacao resumida do processo de atendimento
- `Diferenciais`: pontos que fortalecem a confianca no servico
- `Depoimentos`: prova social em formato textual
- `Duvidas frequentes`: respostas para perguntas comuns
- `Contato`: chamada final para conversao

## Tecnologias utilizadas

- `HTML5`
- `CSS3`
- Google Fonts

Nao ha dependencias de framework, biblioteca JavaScript ou processo de build.

## Arquivos principais

- [index.html](/c:/Users/elayn/OneDrive/Documentos/GitHub/consultoria-academica/index.html): pagina principal do site
- [README.md](/c:/Users/elayn/OneDrive/Documentos/GitHub/consultoria-academica/README.md): documentacao do projeto
- [assets/css/styles.css](/c:/Users/elayn/OneDrive/Documentos/GitHub/consultoria-academica/assets/css/styles.css): arquivo de estilos principal
- `assets/images/branding/Logo marca.png`: logo usada no cabecalho
- `assets/images/profile/elayne.jpg`: imagem principal da secao sobre
- `assets/images/testimonials/`: imagens de depoimentos
- `assets/images/generated/`: imagens geradas e referencias visuais
- `assets/images/whatsapp/`: imagens exportadas do WhatsApp e materiais de apoio

## Como executar

Como o projeto e estatico, basta abrir o arquivo `index.html` no navegador.

Opcao 1:

1. Abra a pasta do projeto.
2. Clique duas vezes em `index.html`.

Opcao 2:

1. Abra o projeto no VS Code.
2. Use uma extensao como Live Server, se quiser visualizar com recarregamento automatico.

## Personalizacao

Os ajustes principais podem ser feitos em dois arquivos:

- [index.html](/c:/Users/elayn/OneDrive/Documentos/GitHub/consultoria-academica/index.html): estrutura e textos
- [assets/css/styles.css](/c:/Users/elayn/OneDrive/Documentos/GitHub/consultoria-academica/assets/css/styles.css): visual e responsividade

### Alterar textos

Edite os conteudos das secoes diretamente no HTML:

- titulo principal da pagina
- descricao da consultoria
- lista de servi&ccedil;os
- FAQ
- links e chamadas para contato

### Alterar imagens

Substitua os arquivos locais e mantenha o mesmo nome, ou altere o caminho no HTML:

- logo: `assets/images/branding/Logo marca.png`
- foto principal: `assets/images/profile/elayne.jpg`

### Alterar cores e estilo

As principais cores do site estao concentradas no bloco `:root` em `assets/css/styles.css`.

Variaveis importantes:

- `--bg`: fundo geral
- `--brand`: cor principal da marca
- `--brand-dark`: variacao mais escura da marca
- `--accent`: cor de apoio
- `--text`: cor principal dos textos
- `--muted`: cor dos textos secundarios

## Responsividade

O layout foi preparado para se adaptar a telas menores com `media queries`, reorganizando:

- menu superior
- blocos em grade
- cards de servicos
- secao de FAQ
- botao flutuante de WhatsApp

## Contatos configurados no site

Atualmente o site utiliza os seguintes links:

- WhatsApp: `https://wa.me/5598985052987`
- E-mail: `eoconsultoria.academica@gmail.com`
- Instagram: `https://instagram.com/_elayne_oliveira`

Se algum desses contatos mudar, atualize os links diretamente no HTML.

## Melhorias futuras sugeridas

- inserir depoimentos reais com imagem ou nome abreviado
- adicionar secao com valores ou pacotes de atendimento
- incluir galeria ou portfolio academico
- adicionar favicon
- melhorar SEO com metadados adicionais
- publicar o projeto em hospedagem como GitHub Pages, Netlify ou Vercel

## Observacoes

- O projeto esta em formato estatico e simples de manter.
- A estrutura agora esta separada em pastas de estilos e imagens.
- Para futuras expansoes, voce pode adicionar novas paginas em uma pasta como `pages/` e componentes reutilizaveis em uma convencao propria.
