# Avaliação visual — site da barbearia

## Premissa da avaliação

As imagens, textos de contato, endereço, WhatsApp, Instagram e demais informações presentes no projeto são consideradas **meramente ilustrativas**. Portanto, esses elementos não foram penalizados na avaliação visual.

## 1. Nota geral

# **6,5/10**

O site possui uma direção visual consistente e uma boa intenção de posicionamento premium. O hero é forte, a paleta é adequada ao segmento e o fluxo principal de agendamento está bem identificado.

Apesar disso, a execução ainda pode evoluir bastante para transmitir uma sensação verdadeiramente sofisticada. Os principais limitadores são a responsividade, a repetição de padrões decorativos, a dependência excessiva da mesma tipografia e alguns detalhes de interação que ainda parecem mais próximos de um protótipo do que de um produto digital refinado.

### Notas por área

| Área | Nota |
|---|---:|
| Direção visual do hero | 7,5 |
| Paleta de cores | 7,0 |
| Tipografia | 6,0 |
| Identidade visual | 6,0 |
| Hierarquia visual | 6,5 |
| Organização das informações | 6,5 |
| Botões e chamadas para ação | 6,5 |
| Agendamento | 6,0 |
| Responsividade | 3,5 |
| Consistência geral | 6,5 |

## 2. Principais pontos positivos

- O hero tem impacto visual, com vídeo, contraste escuro, vinheta e headline bem destacada.
- A frase “Estilo não se improvisa” é forte, direta e adequada ao posicionamento desejado.
- A combinação de preto, grafite e dourado cria uma associação imediata com sofisticação.
- O CTA de agendamento aparece com destaque na navegação e no hero.
- A página possui uma ordem lógica: apresentação, serviços, agendamento, galeria e contato.
- Os cards de serviço organizam bem nome, descrição, duração e preço.
- O resumo lateral do agendamento é uma boa solução para manter o usuário orientado no desktop.
- Os números dos passos ajudam a estruturar o processo de escolha.
- As animações são relativamente discretas e não comprometem a leitura.
- Existe uma tentativa clara de criar uma linguagem editorial com linhas, divisores, espaçamento e títulos de impacto.

## 3. Problemas e inconsistências encontrados

### Identidade visual

A marca “NAVALHA” funciona como nome e ponto de partida, mas ainda não possui uma assinatura visual realmente proprietária. O elemento listrado ao lado do nome é simples demais para funcionar como símbolo de marca forte.

A combinação de preto, dourado, Bebas Neue, vídeo de barbeiro e textos em caixa alta é comum no segmento. Para parecer mais exclusiva, a marca precisa de algum elemento visual que seja reconhecível mesmo sem o nome.

### Paleta de cores

A paleta é adequada, mas existem várias versões do dourado:

- `#B8922A`;
- `#C9A030`;
- `#D4AF37`;
- diversos tons transparentes.

Essa variação reduz a sensação de sistema visual rigoroso. O ideal seria definir um dourado principal, um dourado claro para destaque e uma escala bem controlada de neutros.

O dourado também aparece em muitos elementos ao mesmo tempo: CTA, preços, linhas, números, etiquetas, seleção e detalhes decorativos. Quando tudo é destaque, nada se torna realmente especial.

### Tipografia

A Bebas Neue funciona bem para impacto e remete ao universo masculino, mas é usada em praticamente todos os elementos de maior destaque: logo, títulos, preços, números e confirmações.

Isso deixa a interface visualmente repetitiva e aproxima o resultado de uma estética urbana ou temática. Para uma experiência mais premium, seria interessante combinar:

- uma fonte display mais exclusiva para títulos;
- uma sans-serif refinada para textos e controles;
- eventualmente uma serif discreta para detalhes institucionais ou editoriais.

### Hierarquia visual

O hero possui uma hierarquia clara, mas as seções internas repetem praticamente a mesma fórmula: linha dourada, pequeno texto em caixa alta, título grande e descrição lateral.

Essa repetição cria consistência, mas também deixa a página previsível e com aparência de template. As seções poderiam ter ritmos diferentes, com variações de composição, largura, alinhamento e densidade de informação.

### Espaçamentos, alinhamentos e proporções

Os espaçamentos são generosos e passam uma sensação de calma, mas o uso repetido de grandes blocos verticais pode tornar a navegação cansativa.

Também existe uma diferença de linguagem entre os elementos:

- CTAs com bordas muito arredondadas;
- cards e blocos predominantemente quadrados;
- galeria com composição modular;
- divisores e linhas decorativas em praticamente todas as seções.

O resultado poderia ser mais elegante com menos estilos competindo entre si.

### Botões e chamadas para ação

Os CTAs estão bem posicionados e possuem boa visibilidade. Porém:

- o botão de agendamento aparece com tratamentos diferentes na navegação e no hero;
- o uso de pills em excesso deixa a interface mais genérica;
- não há estados de foco visíveis para links e botões;
- os estados de seleção poderiam ter maior contraste e feedback;
- o botão de confirmação visualmente desativado não utiliza o atributo `disabled`.

Uma linguagem de botões mais editorial, com bordas discretamente arredondadas e menos efeitos translúcidos, poderia transmitir mais sofisticação.

### Navegação e experiência do usuário

A navegação é simples e fácil de entender no desktop. Ainda assim, faltam alguns refinamentos:

- não há indicação clara da seção atualmente ativa;
- não há navegação mobile dedicada;
- o CTA principal poderia permanecer acessível durante a navegação em telas pequenas;
- não há link de retorno ou ação persistente depois da confirmação do agendamento;
- os links de navegação são funcionais, mas visualmente pouco distintivos.

### Responsividade

Este é o principal problema técnico-visual do projeto.

Não há regras `@media` no arquivo, e alguns layouts estão definidos permanentemente em múltiplas colunas:

- navegação fixa sem adaptação mobile ([linhas 65–75](C:/Users/augus/OneDrive/Documentos/projetos/Sistema-de-agendamento-WEB-2.0/Barbearia%20Landing%20v2.dc.html:65));
- cards com largura mínima de 310px ([linha 155](C:/Users/augus/OneDrive/Documentos/projetos/Sistema-de-agendamento-WEB-2.0/Barbearia%20Landing%20v2.dc.html:155));
- agendamento em duas colunas ([linha 188](C:/Users/augus/OneDrive/Documentos/projetos/Sistema-de-agendamento-WEB-2.0/Barbearia%20Landing%20v2.dc.html:188));
- galeria em quatro colunas ([linha 291](C:/Users/augus/OneDrive/Documentos/projetos/Sistema-de-agendamento-WEB-2.0/Barbearia%20Landing%20v2.dc.html:291));
- contato em duas colunas ([linha 311](C:/Users/augus/OneDrive/Documentos/projetos/Sistema-de-agendamento-WEB-2.0/Barbearia%20Landing%20v2.dc.html:311)).

Em celulares, isso pode gerar compressão excessiva, overflow horizontal, textos apertados e perda de hierarquia.

### Formulário e agendamento

A estrutura em três passos é boa, mas a experiência ainda pode ficar mais clara e profissional:

- os campos usam apenas placeholder, sem labels persistentes;
- os horários aparecem mesmo antes da escolha do dia;
- horários indisponíveis parecem desativados, mas continuam sendo botões;
- não há mensagens de validação próximas aos campos;
- o usuário não recebe uma indicação visual de progresso;
- o resumo lateral precisa ser reorganizado para telas pequenas;
- a confirmação poderia apresentar mais detalhes e ações úteis.

## 4. Elementos que mais impedem o site de parecer premium

1. Responsividade insuficiente em celulares e tablets.
2. Uso excessivo de uma única fonte de impacto.
3. Repetição da mesma estrutura visual em todas as seções.
4. Dourado aplicado em elementos demais, reduzindo sua força como destaque.
5. Excesso de efeitos translúcidos, sombras e bordas arredondadas.
6. Identidade visual ainda pouco proprietária.
7. Estados de interação e acessibilidade pouco refinados.
8. Processo de agendamento com aparência de demonstração em vez de experiência finalizada.

## 5. Melhorias recomendadas por prioridade

### Prioridade máxima

- Criar breakpoints reais para celular, tablet e desktop.
- Transformar a navegação em um menu mobile adequado.
- Reorganizar o agendamento em uma coluna no celular.
- Adaptar a galeria para duas colunas ou uma coluna em telas pequenas.
- Corrigir possíveis larguras mínimas e overflow horizontal.
- Adicionar `box-sizing: border-box` e uma escala consistente de espaçamentos.
- Implementar estados de foco, seleção, erro, carregamento e confirmação.

### Alta prioridade

- Definir um sistema de design com tokens para cores, tipografia, bordas e espaçamentos.
- Reduzir as variações do dourado.
- Refinar o logotipo e criar um símbolo proprietário.
- Reduzir o uso de bordas totalmente arredondadas.
- Diversificar a hierarquia entre as seções.
- Criar labels reais para os campos do formulário.
- Bloquear semanticamente os horários indisponíveis com `disabled` ou `aria-disabled`.

### Média prioridade

- Substituir o ticker por uma mensagem de posicionamento mais exclusiva.
- Adicionar navegação ativa durante o scroll.
- Criar uma composição tipográfica com mais contraste entre títulos e textos.
- Adicionar microinterações de seleção e confirmação.
- Implementar suporte a `prefers-reduced-motion`.
- Organizar os estilos em classes ou variáveis, reduzindo a dependência de estilos inline.

## 6. Sugestões práticas para tornar o visual mais elegante

- Usar o dourado apenas em CTAs principais, preços selecionados e pequenos detalhes de marca.
- Trocar parte dos efeitos de blur por superfícies sólidas e contrastes mais controlados.
- Utilizar bordas de 2px a 6px em vez de transformar todos os botões em pills.
- Criar uma escala tipográfica com três níveis claros: display, título de seção e texto.
- Alternar alinhamentos centralizados e alinhamentos à esquerda para criar ritmo.
- Dar mais destaque visual ao serviço recomendado por meio de composição, não apenas por etiqueta.
- Transformar o fluxo de agendamento em uma sequência progressiva, mostrando apenas o próximo passo relevante.
- Usar um resumo compacto e fixo na parte inferior do celular.
- Criar uma seção de diferenciais com ícones simples e textos objetivos.
- Manter transições curtas, mas adicionar feedback visual claro para seleção e confirmação.

## 7. Direção visual recomendada

A direção mais adequada seria uma **barbearia contemporânea de autor**: menos decoração genérica e mais precisão, personalidade e controle visual.

Essa direção poderia combinar:

- fundo carvão e grafite;
- marfim para textos de maior destaque;
- dourado quente usado com moderação;
- logotipo tipográfico próprio;
- títulos fortes, mas não baseados exclusivamente em Bebas Neue;
- composição editorial com mais respiro;
- elementos de interface mais discretos e funcionais;
- uma experiência de agendamento mais clara, progressiva e acessível.

## Conclusão

O projeto já possui uma base visual acima da média para uma primeira versão. O hero é convincente, a intenção de posicionamento é clara e a jornada principal está bem estruturada.

O próximo salto de qualidade não depende de adicionar mais efeitos. Depende de controlar melhor o sistema visual, aprimorar a responsividade, reduzir a repetição de padrões e tornar o agendamento mais refinado.

Com esses ajustes, o site pode evoluir de uma boa landing page temática para uma experiência realmente elegante, moderna e profissional.
