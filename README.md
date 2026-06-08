
# Projeto LaTeX — Template Personalizado

Este repositório contém um template LaTeX customizado para a elaboração do Projeto Capstone do cursos de tecnologia do IDP. Siga cuidadosamente as instruções abaixo para garantir o correto funcionamento da estrutura.

## 🧭 Guia de Uso

### Estrutura de Pastas

* `main.tex`: Arquivo principal. Deve ser compilado com **XeLaTeX**.
* `partes/`: Pasta onde você deve adicionar **todos os seus arquivos `.tex` de conteúdo**.
* `configs/`: Contém arquivos de configuração do template. **Não modifique** esta pasta.
* `pacotes/pacotes.tex`: Arquivo para inclusão de pacotes adicionais. Adicione aqui qualquer pacote LaTeX extra necessário ao seu projeto.

### Campos Obrigatórios

No início do arquivo `main.tex`, preencha corretamente todos os **campos de metadados**, como:

```latex
\cienciadacomputacao %ou \engenhariadesoftware
\autor{Nome do Autor}
\titulo{Título do Trabalho}
\orientador{Nome do Orientador}
\ano{Ano}
```

### Resumo e Abstract

Os textos de **resumo** e **abstract** devem ser escritos exclusivamente nos arquivos:

* `partes/resumo.tex`
* `partes/abstract.tex`

> **⚠️ Não altere os nomes desses arquivos.**

## Dedicatória, Agradecimentos e Epígrafe

As páginas de dedicatória, agradecimentos e epígrafe são opcionais.
Pode incluir qualquer uma delas ou nenhuma. É uma livre escolha da(o) estudante.

Caso não queira incluir alguma dessas seções, basta comentar a linha correspondente 
ao seu comando no arquivo principal `main.tex`.

## ✨ Comandos Customizados

Os seguintes comandos foram definidos para facilitar a escrita do documento:

* `\secao{Título}{partes/arquivo.tex}`
  Cria uma nova **seção**, vinculando ao arquivo de conteúdo correspondente.

* `\subsecao{Título}`
  Cria uma **subseção** dentro de uma seção.

* `\subsubsecao{Título}`
  Cria uma **subsubseção**.

* `\apendice[ap:rotulo]{Título}{caminho/arquivo.tex}`
  Cria uma seção de **apêndices** (opcional).

* `\anexo{Título}{caminho/arquivo.tex}`
  Cria uma seção de **anexos** (opcional).

## 🖨️ Compilação

Este projeto deve ser **compilado com XeLaTeX** para garantir compatibilidade com a fonte e os recursos utilizados.

## Pré-requisitos

* TeX Live: XeTeX and packages

    * Nome do pacote: `texlive-xetex`

    * Esse pacote permite a compilação utilizando o comando XeLaTeX.

* Installer for Microsoft TrueType core fonts

    * Nome do pacote: `ttf-mscorefonts-installer`

    * Esse pacote contém as fontes padronizadas pelo IDP (Arial).

### Fonte utilizada: `Arial`

## 📄 Licença

Esta obra está licenciado com uma Licença [Creative Commons Atribuição-CompartilhaIgual 4.0 Internacional.](https://creativecommons.org/licenses/by-sa/4.0/deed.en)

## ⚙️ Instalação

Para compilar este projeto corretamente, você precisa de um ambiente LaTeX com suporte ao **XeLaTeX** e à fonte **Arial**.

### Execução Local:
Você pode usar qualquer distribuição compatível com XeLaTeX. Recomenda-se o [TeX Live](https://www.tug.org/texlive/)

### Execução Online
Temos um [modelo disponível no Overleaf](https://pt.overleaf.com/read/srgxtbvdbdng#effe2a)
