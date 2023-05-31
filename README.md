# Projeto - Automate my Brain

## Objetivo

Ter um sistema baseado em Zettelkasten idependente de qualquer aplicativo proprietário e que resiste ao tempo, portanto este sistema deve ter:
- Arquivos que possam ser lidos em qualquer dispositivo. Por isso a escolha de notas em Markdown (.md)
- Notas que podem ser editadas em qualquer editor de texto simples. (Vim, Kate, gEdit, geany, notepad++, etc.)
- Estrutura de pastas simples que podem ser gerenciadas pelos gerenciadores de arquivos de qualquer sistema operacional. (Linux, Windows, Mac, Android. iOS, etc.)

## Estrutura de Pastas

├── 1. Fleeting

├── 2. Literature

├── 3. Permanent

├── Assets

│   ├── Arquivos

│   └── Templates

├── Exercícios de Copy

├── Journal

│   ├── 1. Daily

│   ├── 2. Story

│   └── 3. Frame

└── Projetos

### Explicando a estrutura de pastas

├── 1. Fleeting

├── 2. Literature

├── 3. Permanent

Nessas 3 pastas ficam as notas referentes ao sistema Zettelkasten em si.

├── Assets

│   ├── Arquivos

│   └── Templates

Em Assets/Arquivos é onde ficam os anexos (imagens, pdf, .odt, etc.) e em Assets/Templates ficam os scripts que geram os templates automáticos.

├── Journal

│   ├── 1. Daily

│   ├── 2. Story

│   └── 3. Frame

Já essas 3 pastas são a estrutura de algo que estou tentando implementar "Zettelkasten de Histórias".
 
Neste cenário, a pasta "1. Daily" será onde eu vou despejar tudo o que veio à minha mente no dia, podendo ser histórias, desabafos ou simplesmente pensamentos aleatórios. A pasta "2. Story" se comportará como a pasta de Literature Notes do Zettelkasten tradicional, nela eu vou colocar "histórias digeridas" que surgirão à partir das notas diárias. E, por fim, a pasta "3. Frame" será o equivalente a pasta de Permanent Notes do Zettelkasten, onde terão pequenos pedaços (frames) das histórias que surgiram nas pastas mencionadas anteriormente. Com isso, terei uma "teia" de histórias que poderão ser mescladas com as notas do  Zettelkasten tradicional e assim criar projetos totalmente únicos.

## To-do list

- [x] Script template fleetingnote 
- [x] Script template literaturenote
- [x] Script template permanentnote
- [ ] Script template dailynote
- [ ] Script template storynote
- [ ] Script template framenote
