# Unorganized Nations Organization (UNO)

**Tema:** Países e cooperação internacional  
**Estudante:** Guilherme Gon Wiemes  
**Turma:** DSM03 - 2025 - 2ª Série  
**Unidade curricular:** Programação de Aplicativos  
**Ano:** 2026

## Sobre o projeto

A UNO (*Unorganized Nations Organization*, ou Organização Desorganizada das Nações) é uma organização fictícia criada para este trabalho, com uma abordagem bem-humorada sobre países e cooperação internacional. O site apresenta a organização, reúne informações comparativas sobre seis países e inclui formulários demonstrativos de cadastro e contato. A UNO não é uma instituição real e não possui vínculo com a Organização das Nações Unidas (ONU).

## Como abrir o site

1. Baixe ou clone o repositório para o computador.
2. Mantenha os cinco arquivos HTML na mesma pasta e a pasta `img` junto deles.
3. Abra o arquivo `index.html` em um navegador.
4. Use o menu principal para navegar entre as páginas.

O projeto utiliza HTML, sem CSS, conforme as regras da atividade. Os formulários são demonstrativos: usam `action="#"` e não estão conectados a um servidor, portanto não realizam cadastro nem enviam mensagens de verdade.

## Páginas do site

- **`index.html` — Início:** apresenta a UNO e orienta o visitante para as outras áreas do site.
- **`sobre.html` — Sobre:** explica a proposta e os objetivos fictícios da organização e apresenta um glossário de termos.
- **`dados.html` — Dados:** exibe uma tabela comparativa com seis países, suas capitais, continentes e datas de admissão na ONU.
- **`cadastro.html` — Cadastro:** contém um formulário fictício para demonstrar como seria a manifestação de interesse de um país em participar da UNO.
- **`contato.html` — Contato:** apresenta informações de contato fictícias e um formulário demonstrativo para mensagens.

## Semântica e acessibilidade

Foram adotados os seguintes recursos no HTML:

- Documento declarado em HTML5, idioma `pt-BR`, codificação UTF-8 e configuração de `viewport`.
- Título e descrição (`meta description`) próprios para cada página.
- Regiões semânticas `header`, `nav`, `main` e `footer`, com um único `main` e um único título principal (`h1`) em cada página.
- Menu principal consistente entre as páginas, com `aria-current="page"` no link correspondente à página atual.
- Link para pular diretamente ao conteúdo principal, facilitando a navegação por teclado.
- Imagens informativas com texto alternativo descritivo, dimensões e legendas; a imagem decorativa utiliza `alt=""` para ser ignorada por leitores de tela.
- Formulários com rótulos associados aos campos por meio de `label`, `for` e `id`, além de tipos de entrada e atributos de validação nativa adequados.
- Tabela de dados com legenda, cabeçalhos identificados por `scope`, datas marcadas com `time` e linha de totalização.
- Uso de `section` para agrupar conteúdo por assunto; `article` para blocos que podem ser compreendidos separadamente; e `aside` para informação complementar. O elemento `address` é usado para agrupar informações de contato.
- Não foram utilizados CSS, atributos `style`, elementos obsoletos nem tabelas para organizar o layout.

## Testes e validação

### Teste de teclado

**Resultado: concluído com sucesso.** As cinco páginas foram testadas com `Tab` e `Shift + Tab`. Links, campos e botões podem ser percorridos em uma ordem lógica e utilizados sem depender do mouse.

### Validação do HTML

Os cinco arquivos (`index.html`, `sobre.html`, `dados.html`, `cadastro.html` e `contato.html`) foram submetidos ao [Nu HTML Checker](https://validator.w3.org/nu/#textarea).

**Resultado: concluído com sucesso.** As cinco páginas foram validadas sem erros remanescentes.

### Lighthouse

Todos os testes do lighthouse foram bem sucedidos. Vale dizer que, em todos eles, as páginas html ficaram 1 ponto de distância da pontuação máxima por conta de espaçamento, já que o trabalho proíbe utilizar <br>, era impossível tirar nota máxima.


### Evidências da atividade

As capturas de tela dos testes realizados acompanham o documento de evidências solicitado pelo professor. O documento foi anexado no AVA.

## Fontes consultadas

- **United Nations — Member States:** https://www.un.org/en/about-us/member-states — referência para informações sobre Estados-membros e datas de admissão na ONU.
- **Encyclopaedia Britannica — Places:** https://www.britannica.com/topic/list-of-countries-1993160 — consulta de informações geográficas.
- **OpenStreetMap:** https://www.openstreetmap.org/ — referência geográfica relacionada às informações de contato fictícias apresentadas no site.

## Imagens

As imagens abaixo são arquivos SVG originais criados para este projeto e armazenados na pasta `img`:

- `img/globo-terrestre.svg` — ilustração de um globo terrestre.
- `img/bandeiras-mundo.svg` — ilustração de bandeiras que representam a diversidade de países.

**Autoria:** produzidas para o projeto UNO.  
**Licença:** conteúdo original deste projeto; não foi utilizado arquivo de imagem externo nesses dois SVGs.
