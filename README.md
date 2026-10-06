# Atividade 02/10 - Técnicas de Inspeção de Acessibilidade no Navegador

Repositório dedicado à auditoria manual de requisitos não-funcionais visuais e de acessibilidade, com base nas diretrizes **WCAG 2.1 (Nível AA)** e na norma **ISO/IEC 25010**.

## 📁 Estrutura do Projeto

- `painel-campanha.html` — Componente web local contendo intencionalmente barreiras e falhas de acessibilidade para fins de diagnóstico e inspeção.

---

## 🔍 Etapas da Auditoria Visual (DevTools)

As evidências (prints) solicitadas na atividade cobrem os seguintes pontos:

1. **Emulação de Deficiências Visuais:**
   - Utilização do painel *Rendering* (`More tools > Rendering > Emulate vision deficiencies`) para simular condições como *Protanopia* e *Blurred vision*.
2. **Inspeção e Cálculo da Taxa de Contraste:**
   - Validação através do *Color Picker* do DevTools para verificar se os elementos de texto cumprem o rácio mínimo de `4.5 : 1` exigido pelo Critério 1.4.3 (Nível AA).
3. **Ordem e Fluxo de Tabulação:**
   - Teste de navegação por teclado (`Tab`) para analisar desvios de foco provocados pelo uso incorreto de atributos `tabindex` positivos e a ausência do indicador visual de foco (`:focus-visible`).

---
*Disciplina: Qualidade e Teste de Software (QTS)*
