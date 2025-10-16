# Página de Produto Apple - Pulseira Loop Esportiva

Uma réplica moderna e interativa da página de produto da Apple, focada na venda de pulseiras para Apple Watch. Este projeto demonstra habilidades em HTML, CSS e JavaScript para criar uma experiência de usuário fluida e responsiva.

## Funcionalidades

### Seleção de Cores
- 5 opções de cores disponíveis:
  - Verde-cipreste
  - Azul-inverno (padrão)
  - Meia-noite
  - Estelar
  - Rosa-claro
- Atualização dinâmica das imagens do produto
- Visualização em tempo real das mudanças

### Seleção de Tamanho
- Opções de 41mm e 45mm
- Ajuste automático da escala da imagem do produto
- Atualização do título do produto

### Galeria de Imagens
- 3 ângulos diferentes do produto
- Navegação intuitiva entre as imagens
- Atualização automática baseada na cor selecionada

### Informações de Preço
- Preço principal: R$ 499,90
- Opção de parcelamento: até 12x de R$ 41,58
- Desconto à vista: R$ 449,10 (10% de desconto)

## Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização moderna com:
  - Flexbox e Grid Layout
  - Fontes personalizadas (San Francisco)
  - Animações e transições suaves
  - Design responsivo
- **JavaScript** - Interatividade:
  - Manipulação do DOM
  - Event listeners
  - Atualização dinâmica de conteúdo

## Estrutura do Projeto

```
apple/
├── index.html          # Página principal
├── style.css           # Estilos CSS
├── script.js           # Lógica JavaScript
├── imagens/
│   ├── opcoes-cores/   # Imagens das cores
│   │   ├── azul-inverno.jpeg
│   │   ├── estelar.jpeg
│   │   ├── meia-noite.jpeg
│   │   ├── rosa-claro.jpeg
│   │   ├── verde-cipreste.jpeg
│   │   └── imagens-[cor]/  # Galeria por cor
│   └── outros-recursos/ # Selos e ícones
└── README.md           # Documentação
```

## Como Executar

1. Clone ou baixe o projeto
2. Abra o arquivo `index.html` em um navegador web
3. Explore as funcionalidades interativas

## Funcionalidades JavaScript

### `atualizarCorSelecionada()`
- Atualiza o título do produto
- Muda as imagens da galeria
- Atualiza o nome da cor selecionada

### `atualizarTamanho()`
- Modifica o título do produto
- Ajusta a escala da imagem principal
- Aplica classe CSS para tamanho menor (41mm)

### `atualizarImagemSelecionada()`
- Troca a imagem principal
- Mantém a cor selecionada
- Atualiza apenas o ângulo da foto

## Design Features

- **Tipografia**: Fonte San Francisco (oficial da Apple)
- **Cores**: Paleta minimalista com azul corporativo
- **Layout**: Grid responsivo com foco na experiência do usuário
- **Interações**: Feedback visual imediato
- **Acessibilidade**: Labels e alt texts apropriados

## Responsividade

O projeto foi desenvolvido com foco em dispositivos desktop, mas mantém boa usabilidade em tablets e dispositivos móveis.

## Personalização

Para adicionar novas cores:
1. Adicione a imagem da cor em `imagens/opcoes-cores/`
2. Crie a pasta `imagens-[nome-cor]/` com as 3 imagens
3. Atualize o array `opcoesCores` no JavaScript

## Licença

Este é um projeto educacional para demonstração de habilidades em desenvolvimento web front-end.

---

**Desenvolvido para o Intensivão JS**
