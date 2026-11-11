# Projeto Integrador Final — Criação de um Portfólio Pessoal Web

## 1. Objetivo do projeto

O projeto consiste no desenvolvimento de um portfólio pessoal utilizando HTML e CSS.

O portfólio funcionará como uma apresentação profissional, permitindo que visitantes conheçam o estudante, suas habilidades, seus projetos, seus objetivos e seus interesses pessoais.

O objetivo principal é demonstrar os conhecimentos adquiridos na unidade curricular de CSS, desenvolvendo uma interface moderna, organizada, responsiva e funcional.

**Carga horária sugerida:** 24 horas.

## 2. Seções obrigatórias do portfólio

O site deverá apresentar os seguintes conteúdos:

1. **Apresentação inicial (Hero):** nome ou identificação profissional, breve apresentação e destaque visual.
2. **Sobre mim:** trajetória, interesses, objetivos e área de atuação.
3. **Projetos:** apresentação dos trabalhos desenvolvidos, incluindo título, imagem, descrição, tecnologias utilizadas e links para demonstração ou GitHub.
4. **Habilidades:** tecnologias, ferramentas e competências técnicas.
5. **Conexões e redes:** links funcionais para LinkedIn, GitHub e outras redes sociais.
6. **Interesses pessoais:** filmes, séries, livros, músicas, esportes e hobbies.
7. **Contato:** e-mail ou perfil profissional para contato.
8. **Rodapé:** identificação do autor, ano de criação ou créditos.

A organização das seções é flexível, permitindo alterações na ordem e inclusão de novos conteúdos.

## 3. Requisitos técnicos obrigatórios de CSS

O professor exige a utilização de 11 recursos técnicos de CSS. Todos deverão ser aplicados no portfólio e o estudante deverá saber explicar onde foram utilizados.

### 3.1. Seletores CSS

Utilizar diferentes tipos de seletores:

- Seletores de elementos.
- Classes.
- IDs.
- Seletores agrupados.
- Seletores avançados.

### 3.2. Cores

Utilizar diferentes formatos de cores:

- HEX.
- RGB.
- RGBA.
- currentColor.

### 3.3. Gradientes

Utilizar `linear-gradient()` em pelo menos três aplicações diferentes, como:

- Banner inicial (Hero).
- Botões.
- Rodapé.

### 3.4. CSS Columns

Utilizar `column-count` e `column-gap` em uma seção textual, como biografia, trajetória ou interesses pessoais.

### 3.5. Transformações 2D

Aplicar as seguintes transformações em elementos decorativos ou interativos:

- `scale()`: aumenta ou diminui um elemento.
- `rotate()`: gira um elemento.
- `translate()`: movimenta um elemento.

### 3.6. Transition

Criar transições suaves em elementos como:

- Botões.
- Menu de navegação.
- Cards de projetos.
- Cards de interesses.

### 3.7. Animation

Utilizar `@keyframes` e `animation` para criar pelo menos uma animação funcional no portfólio.

### 3.8. Border Image

Aplicar `border-image` em pelo menos um botão ou card especial.

### 3.9. Múltiplos Backgrounds

Utilizar múltiplos backgrounds na seção Hero, criando uma composição visual com mais de um fundo.

### 3.10. Fontes personalizadas

Utilizar `@font-face` ou fontes locais configuradas no CSS para personalizar a tipografia do site.

### 3.11. Estilo para impressão

O portfólio deverá possuir uma opção de impressão ou salvamento em PDF pelo navegador.

Requisitos:

- Utilizar `@media print`.
- Utilizar `@page` para configurar formato e margens.
- Ocultar elementos desnecessários, como menus, botões e animações.
- Ajustar cores, textos e imagens para facilitar a leitura.
- Disponibilizar um botão de impressão utilizando JavaScript com `window.print()`.

## 4. Requisitos visuais e de qualidade

### Requisitos visuais

- Identidade visual coerente.
- Hierarquia tipográfica.
- Espaçamento e alinhamento adequados.
- Contraste entre texto e fundo.
- Navegação intuitiva.
- Layout responsivo.
- Imagens relacionadas ao conteúdo.

### Qualidade do código

- CSS organizado, identado e comentado quando necessário.
- Estrutura limpa e reutilizável.
- Evitar duplicação desnecessária de regras CSS.
- Separar a estrutura HTML da apresentação CSS.
- Garantir que todos os links e botões funcionem corretamente.

## 5. Estrutura mínima de arquivos

```text
portfolio-pessoal/
│
├── index.html
│
├── css/
│   └── style.css
│
├── images/
│
└── fonts/
```

## 6. Entregáveis

### 6.1. Arquivos do projeto

- `index.html`
- `style.css`
- Pasta `images/` com imagens e recursos utilizados.
- Pasta `fonts/` quando houver fontes locais.
- Demais arquivos necessários para executar o portfólio.

### 6.2. Documento técnico

O estudante deverá entregar um relatório breve contendo:

- Identificação do projeto e nome do estudante.
- Objetivo do portfólio e público-alvo.
- Tecnologias utilizadas: HTML e CSS.
- Recursos aplicados e onde foram utilizados.
- Links dos perfis e projetos apresentados.
- Justificativa das principais escolhas visuais.

## 7. Etapas de desenvolvimento

### Etapa 1 — Planejamento

- Definir o objetivo do portfólio e o público-alvo.
- Selecionar projetos e conteúdos.
- Definir paleta de cores e tipografia.
- Escolher referências visuais.
- Criar um wireframe simples.

**Entrega:** wireframe e planejamento do conteúdo.

### Etapa 2 — Estruturação

- Construir a estrutura semântica utilizando `header`, `nav`, `main`, `section` e `footer`.
- Organizar as seções.
- Inserir os conteúdos.
- Criar links para GitHub, LinkedIn e projetos.

**Entrega:** estrutura HTML inicial.

### Etapa 3 — Estilização

- Desenvolver a identidade visual com CSS.
- Aplicar todos os requisitos técnicos obrigatórios.
- Estilizar projetos, botões, textos e demais elementos.

**Entrega:** interface estilizada.

### Etapa 4 — Testes e ajustes

- Validar a navegação e os links.
- Verificar responsividade.
- Conferir contraste e legibilidade.
- Testar efeitos e animações.
- Testar a versão de impressão.
- Corrigir problemas encontrados.

**Entrega:** portfólio revisado e funcional.

### Etapa 5 — Apresentação

- Demonstrar o funcionamento do portfólio.
- Apresentar os projetos.
- Explicar a organização das seções.
- Demonstrar os recursos CSS obrigatórios.
- Justificar as escolhas técnicas e visuais.

**Entrega:** demonstração e defesa técnica.

## 8. Critérios de avaliação

| Critério | Peso |
|---|---:|
| Estrutura HTML | 15% |
| Aplicação CSS | 35% |
| Recursos avançados | 20% |
| Organização do projeto | 10% |
| Apresentação técnica | 10% |
| Documentação | 10% |
| **Total** | **100%** |

**Ponto importante:** a aplicação CSS e os recursos avançados representam juntos 55% da nota. Portanto, é fundamental implementar corretamente os recursos solicitados.

## 9. Rubrica de avaliação

- **Excelente (4 pontos):** todos os requisitos implementados, código organizado, interface profissional e responsiva e domínio das decisões técnicas.
- **Bom (3 pontos):** maioria dos requisitos implementados, com pequenos ajustes necessários.
- **Satisfatório (2 pontos):** requisitos parcialmente atendidos, com algumas inconsistências visuais ou técnicas.
- **Insuficiente (1 ponto):** projeto incompleto ou com falhas técnicas significativas.

## 10. Apresentação final

Durante a apresentação individual, o estudante deverá demonstrar:

- Navegação entre as seções.
- Projetos e links externos.
- Layout em diferentes tamanhos de tela.
- Recursos CSS utilizados.
- Animações e transições.
- Versão preparada para impressão.

### Defesa técnica

O estudante deverá explicar as decisões visuais, a estrutura adotada, os recursos avançados implementados e os desafios encontrados durante o desenvolvimento.

### Perguntas de reflexão

1. Qual recurso CSS foi mais útil no desenvolvimento do portfólio?
2. Qual foi a maior dificuldade encontrada e como ela foi resolvida?
3. Como o CSS contribuiu para a identidade visual e a experiência de navegação?
4. De que forma o portfólio pode ajudar a apresentar seus projetos e habilidades?

## 11. Recomendações para o desenvolvimento

Uma proposta interessante é desenvolver o portfólio com uma identidade visual profissional, utilizando um estilo Dark Tech.

### Identidade visual sugerida

- Fundo azul-escuro ou preto.
- Detalhes em azul e ciano.
- Tipografia moderna.
- Cards com efeitos de interação.
- Gradientes em elementos estratégicos.
- Animações suaves.

### Projetos que podem ser apresentados

- API de Controle de Chamados.
- API de Catálogo de Games.
- CRM de Clientes em PHP.
- SupplyChain SENAI.
- Projetos desenvolvidos com PHP, PostgreSQL e Laravel.

## 12. Checklist de desenvolvimento

- [ ] Planejar identidade visual e público-alvo.
- [ ] Criar wireframe do site.
- [ ] Desenvolver estrutura HTML semântica.
- [ ] Criar todas as seções do portfólio.
- [ ] Aplicar os diferentes seletores CSS.
- [ ] Utilizar HEX, RGB, RGBA e currentColor.
- [ ] Implementar pelo menos três gradientes.
- [ ] Aplicar CSS Columns.
- [ ] Utilizar scale(), rotate() e translate().
- [ ] Implementar transitions.
- [ ] Criar animação com @keyframes.
- [ ] Aplicar border-image.
- [ ] Utilizar múltiplos backgrounds no Hero.
- [ ] Configurar fonte personalizada.
- [ ] Criar versão de impressão com @media print e @page.
- [ ] Testar botão window.print().
- [ ] Verificar responsividade e links.
- [ ] Organizar arquivos e pastas.
- [ ] Produzir relatório técnico.
- [ ] Preparar apresentação e defesa técnica.

---

## Conclusão

O objetivo final é desenvolver um portfólio pessoal completo, funcional, responsivo e visualmente consistente, demonstrando os conhecimentos adquiridos durante a unidade curricular de CSS.

Além de atender aos requisitos do SENAI, o projeto poderá ser utilizado como parte do portfólio profissional do estudante, apresentando seus projetos, conhecimentos técnicos e evolução na área de Desenvolvimento de Sistemas.