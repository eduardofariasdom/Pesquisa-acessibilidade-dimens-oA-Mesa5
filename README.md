# 📘 README — Acessibilidade Web no Processo de Desenvolvimento

---

## 🧭 Visão Geral

Este documento organiza **conceitos, ferramentas e práticas essenciais** para o desenvolvimento de aplicações web acessíveis.

A acessibilidade deve ser tratada como parte estrutural do projeto — **desde o planejamento até a manutenção contínua** — e não como um ajuste final.

> 💡 Resultado esperado: interfaces inclusivas, funcionais e compatíveis com diferentes usuários e tecnologias assistivas.

---

## 🎯 Objetivo

Garantir que aplicações web:

* sejam utilizáveis por pessoas com diferentes tipos de deficiência
* sigam diretrizes como WCAG
* mantenham qualidade, usabilidade e consistência
* atendam requisitos legais e sociais

---

## 🛠️ Ferramentas de Avaliação de Acessibilidade

### 🔎 1. WebAIM WAVE

* Disponível para: Chrome, Firefox e Edge
* Analisa páginas em tempo real
* Exibe erros diretamente na interface com ícones visuais
* Detecta:

  * baixo contraste
  * ausência de texto alternativo
  * problemas estruturais

---

### 🧪 2. Siteimprove Accessibility Checker

* Extensão gratuita de navegador
* Analisa páginas individuais (inclusive protegidas por senha)
* Fornece:

  * explicações detalhadas
  * sugestões práticas
  * simulação de contraste

---

### ⚙️ 3. Deque Axe DevTools

* Extensão (principalmente Chrome)
* Uso via modo **"Inspecionar" (DevTools)**
* Funciona como um *linter de acessibilidade*
* Analisa:

  * HTML, CSS e JavaScript
* Detecta:

  * problemas de contraste
  * ausência de ALT
  * falhas de foco de teclado

---

### 🚀 4. Accessibility Insights for Web

* Extensão da Microsoft
* Possui dois modos principais:

  * **FastPass** → análise rápida (≈5 min)
  * **Assessment** → avaliação completa
* Inclui:

  * visualização da navegação por TAB
  * guia de testes manuais
  * exportação de relatórios

---

### 🧩 5. ANDI (Accessible Name & Description Inspector)

* Tipo: **bookmarklet (não extensão)**
* Detecta problemas automaticamente
* Mostra o que leitores de tela interpretam
* Ajuda a:

  * validar elementos interativos
  * melhorar descrições acessíveis
  * aplicar boas práticas da Seção 508

---

## 🔄 Processo de um Desenvolvedor que Leva Acessibilidade a Sério

### 🧠 1. Planejamento

* Define requisitos acessíveis desde o início
* Considera diferentes perfis de usuários
* Integra acessibilidade ao design e UX

---

### 🧱 2. Estrutura Semântica

* Uso correto de:

  * `<header>`, `<main>`, `<nav>`, `<footer>`
  * hierarquia de títulos (`<h1> → <h6>`)
* Garante melhor interpretação por leitores de tela

---

### 🖼️ 3. Conteúdo Acessível

* Imagens com `alt` adequado
* Elementos não textuais com descrição
* Evitar dependência apenas visual

---

### ⌨️ 4. Navegação por Teclado

* Todos os elementos devem ser acessíveis via teclado
* Testes com:

  * `Tab`
  * `Enter`
  * `Space`
* Sem "armadilhas de foco"

---

### 🎨 5. Contraste e Legibilidade

* Garantir contraste adequado
* Evitar textos ilegíveis
* Testar zoom e responsividade

---

### 🤖 6. Testes Automatizados

Utilizar ferramentas como:

* WAVE
* Siteimprove
* Axe DevTools
* Accessibility Insights
* ANDI

✔ Detectam rapidamente problemas comuns

❗ Não substituem testes manuais

---

### 🧪 7. Testes Manuais

* Navegação real sem mouse
* Uso de leitores de tela
* Validação de fluxos completos

---

### 👥 8. Testes com Usuários

* Sempre que possível, incluir pessoas com deficiência
* Identifica problemas reais que ferramentas não detectam

---

### 🔁 9. Iteração Contínua

* Corrigir erros encontrados
* Documentar melhorias
* Integrar acessibilidade no ciclo de desenvolvimento

---

## 🧾 Boas Práticas Resumidas

```txt

✔ Planejar acessibilidade desde o início

✔ Usar HTML semântico

✔ Garantir navegação por teclado

✔ Validar contraste e legibilidade

✔ Combinar testes automáticos + manuais

✔ Melhorar continuamente

```

---

## ⚠️ Observação Importante

Acessibilidade não é:

* um “extra”
* uma etapa final
* apenas visual

👉 Ela é **parte da qualidade do software**

---

## 📌 Conclusão

Um desenvolvedor que leva acessibilidade a sério:

> pensa antes, constrói corretamente e testa continuamente.

Isso resulta em sistemas mais inclusivos, profissionais e preparados para todos os usuários.
