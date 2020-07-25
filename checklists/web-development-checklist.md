# Esteira de Produção - Website

### Fase 1: Coleta de Recursos
- [ ] Levantamento das especificações do projeto
  - Ex.: `cores, tipografia, imagens etc..`
  - [ ] Criar um arquivo de texto com todas as cores do projeto já com os nomes de referência que servirão como base 
 para a criação das variáveis css - As cores deverão preferencialmente ser códigos hexadecimais
    - Ex: `light-blue: #code-hex`
  - [ ] Criar uma pasta na nuvem contendo **TODAS** as imagens que serão
 necessárias no projeto preferencialmente no formato **SVG** para ícones e ilustrações e no formato **JPG** para fotos 
 sem transparência
- [ ] Levantamento do conteúdo textual
  - [ ] Criar um arquivo de texto cotendo o conteúdo textual do website
- [ ] Levantamento das ferramentas que serão utilizadas no projeto. 
  - Ex: `Bootstrap 4, TheSaas, vueJS, etc.`

### Fase 2: Planejamento da codificação HTML/CSS
**Princípios:** O planejamento deverá ser dividido por página e, em cada página, deverá ser dividido por seção
- **Projeto:**
  - [ ] Definição da estrutura do projeto - **Padrão a ser estabelecido**
  - [ ] Adição dos recursos e ferramentas 
- **Página:**
  - [ ] Definição da estrutura HTML semântica a partir do layout para cada seção
  - [ ] Definição da nomenclatura dos seletores que receberão as regras de estilo
  - [ ] Adição de conteúdo (textos e imagens)
  - [ ] Definição da estrutura HTML para o layout responsivo (mobile first)
  - [ ] Definição das regras de estilo para o layout responsivo (mobile first)

### Fase 3: Codificação HTML/CSS

- [ ] Codifição da estrutura HTML semântica: A codificação deverá seguir o guia HTML5 da [W3School](https://www.w3schools.com/html/html5_syntax.asp)
- [ ] Nomenclatura dos seletores  (**classes**): A nomenclatura deverá seguir a metodologia [BEM](http://getbem.com/introduction/)
- [ ] Adição do conteúdo (textos e imagens)
- [ ] Codificação da estrutura HTML responsiva
- [ ] Estilização dos elementos
---
## Checklist de Qualidade
- [ ] A código HTML está seguindo a estrutura semântica correta?
- [ ] Existem declarações ***!important*** desnecessárias nas folhas de estilo? Isto é , que podem ser substituidas
adicionando especificidade a regra de estilo?
- [ ] Existem quaisquer blocos de comentários desnecessários?
- [ ] As regras de estilos estão todos em arquivos `.css` importados aos arquivos HTML? - Com exceção de *tags*  `<img>`