# 📘 Resumo das Tags Mais Importantes do HTML

## 🧱 1. Estrutura Básica da Página

| Tag        | Função                         | Tipo       | Bloco/Inline | Atributos Comuns                          |
|------------|--------------------------------|------------|---------------|-------------------------------------------|
| `<html>`   | Raiz do documento HTML         | Estrutural | Bloco         | `lang="pt-BR"`                            |
| `<head>`   | Metadados e configurações      | Estrutural | Bloco         | —                                         |
| `<body>`   | Conteúdo visível da página     | Estrutural | Bloco         | —                                         |
| `<title>`  | Título da aba do navegador     | Metadado   | Inline        | —                                         |

---

## 📄 2. Títulos e Textos

| Tag        | Função                      | Tipo       | Bloco/Inline | Atributos Comuns                          |
|------------|-----------------------------|------------|---------------|-------------------------------------------|
| `<h1>`-`<h6>` | Títulos do conteúdo       | Semântica  | Bloco         | —                                         |
| `<p>`      | Parágrafo de texto          | Semântica  | Bloco         | —                                         |
| `<br>`     | Quebra de linha             | Apresentação | Inline      | — (auto-fechável)                         |
| `<hr>`     | Linha horizontal            | Apresentação | Bloco       | — (auto-fechável)                         |

---

## ✍️ 3. Marcação de Texto

| Tag          | Função                         | Tipo       | Bloco/Inline | Atributos Comuns                          |
|--------------|--------------------------------|------------|---------------|-------------------------------------------|
| `<strong>`   | Negrito com significado        | Semântica  | Inline        | —                                         |
| `<em>`       | Itálico com significado        | Semântica  | Inline        | —                                         |
| `<b>`        | Negrito visual                 | Visual     | Inline        | —                                         |
| `<i>`        | Itálico visual                 | Visual     | Inline        | —                                         |
| `<mark>`     | Destaque (fundo amarelo)       | Semântica  | Inline        | —                                         |
| `<small>`    | Texto pequeno (legal, avisos)  | Semântica  | Inline        | —                                         |
| `<blockquote>` | Citação longa                | Semântica  | Bloco         | `cite="url"`                             |
| `<code>`     | Texto monoespaçado (código)    | Semântica  | Inline        | —                                         |

---

## 🔗 4. Links e Navegação

| Tag      | Função                    | Tipo       | Bloco/Inline | Atributos Comuns                          |
|----------|---------------------------|------------|---------------|-------------------------------------------|
| `<a>`    | Link (âncora)             | Semântica  | Inline        | `href=""`, `target="_blank"`, `rel=""`   |
| `<nav>`  | Agrupa links de navegação | Estrutural | Bloco         | —                                         |

---

## 🖼️ 5. Mídia

| Tag        | Função                    | Tipo     | Bloco/Inline | Atributos Comuns                                   |
|------------|---------------------------|----------|---------------|----------------------------------------------------|
| `<img>`    | Inserir imagem            | Mídia    | Inline        | `src=""`, `alt=""`, `width=""`, `height=""`       |
| `<video>`  | Inserir vídeo             | Mídia    | Bloco         | `src=""`, `controls`, `autoplay`, `muted`, `loop` |
| `<audio>`  | Inserir áudio             | Mídia    | Bloco         | `src=""`, `controls`, `autoplay`, `loop`          |
| `<source>` | Fonte alternativa         | Mídia    | Inline        | `src=""`, `type="audio/mp3"` ou `video/mp4`       |

---

## 📋 6. Listas

| Tag     | Função                          | Tipo       | Bloco/Inline | Atributos Comuns          |
|---------|---------------------------------|------------|---------------|---------------------------|
| `<ul>`  | Lista não ordenada              | Semântica  | Bloco         | —                         |
| `<ol>`  | Lista ordenada                  | Semântica  | Bloco         | `type="1"`, `"a"`, `"i"`  |
| `<li>`  | Item da lista                   | Semântica  | Bloco         | —                         |
| `<dl>`  | Lista de definição              | Semântica  | Bloco         | —                         |
| `<dt>`  | Termo da definição              | Semântica  | Bloco         | —                         |
| `<dd>`  | Definição do termo              | Semântica  | Bloco         | —                         |

---

## 📦 7. Containers Genéricos

| Tag      | Função                         | Tipo       | Bloco/Inline | Atributos Comuns                          |
|----------|--------------------------------|------------|---------------|-------------------------------------------|
| `<div>`  | Agrupamento genérico de blocos | Estrutural | Bloco         | `class=""`, `id=""`                       |
| `<span>` | Agrupamento inline             | Estrutural | Inline        | `class=""`, `id=""`                       |

---

## 📝 8. Formulários

| Tag        | Função                     | Tipo       | Bloco/Inline | Atributos Comuns                                       |
|------------|----------------------------|------------|---------------|--------------------------------------------------------|
| `<form>`   | Formulário                 | Semântica  | Bloco         | `action=""`, `method="get|post"`                      |
| `<input>`  | Campo de entrada           | Formulário | Inline        | `type=""`, `name=""`, `placeholder=""`, `value=""`    |
| `<label>`  | Rótulo do campo            | Semântica  | Inline        | `for=""`                                               |
| `<textarea>` | Campo de texto longo     | Semântica  | Bloco         | `rows=""`, `cols=""`, `placeholder=""`, `name=""`     |
| `<select>` | Lista suspensa             | Semântica  | Bloco         | `name=""`, `multiple`                                 |
| `<option>` | Opção do select            | Semântica  | Inline        | `value=""`, `selected`                                |
| `<button>` | Botão                      | Semântica  | Inline        | `type="submit|reset|button"`                          |

---

## ⚙️ 9. Tags Semânticas Modernas (HTML5)

| Tag        | Função                         | Tipo       | Bloco/Inline | Atributos Comuns |
|------------|--------------------------------|------------|---------------|------------------|
| `<header>` | Cabeçalho do site/seção        | Semântica  | Bloco         | —                |
| `<main>`   | Conteúdo principal             | Semântica  | Bloco         | —                |
| `<footer>` | Rodapé da página               | Semântica  | Bloco         | —                |
| `<section>`| Seção temática do conteúdo     | Semântica  | Bloco         | —                |
| `<article>`| Conteúdo independente          | Semântica  | Bloco         | —                |
| `<aside>`  | Conteúdo lateral, secundário   | Semântica  | Bloco         | —                |

---

> **💡 Dica:** Use sempre `class=""` e `id=""` para estilizar ou manipular elementos via CSS e JavaScript!

