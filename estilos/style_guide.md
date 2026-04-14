# Guia de Estilo - SaaSModern (Light Mode)

Este documento detalha as cores e tipografias utilizadas no projeto SaaSModern, versão Light Mode, para garantir consistência visual e facilitar futuras manutenções ou expansões.

## 🎨 Paleta de Cores

A paleta de cores foi cuidadosamente selecionada para transmitir modernidade, profissionalismo e clareza, com um foco em legibilidade e uma experiência de usuário agradável em ambientes claros.

| Variável CSS | Cor Hexadecimal | Descrição | Uso Principal |
| :----------- | :-------------- | :-------- | :------------ |
| `--primary` | `#6366F1` | Indigo vibrante | Botões primários, logo, links em destaque, ícones. |
| `--primary-hover` | `#4F46E5` | Indigo mais escuro | Estado `hover` de botões primários. |
| `--secondary` | `#1E293B` | Azul Ardósia Escuro | Títulos (h1, h2, h3, h4), fundo do footer. |
| `--accent` | `#F43F5E` | Rosa/Vermelho suave | Elementos de destaque ou alerta. |
| `--background` | `#FFFFFF` | Branco puro | Fundo principal de todas as páginas. |
| `--foreground` | `#0F172A` | Azul Quase Preto | Cor principal do texto (parágrafos). |
| `--muted` | `#64748B` | Cinza Azulado | Textos secundários, descrições, placeholders. |
| `--muted-light` | `#F1F5F9` | Cinza Muito Claro | Fundo de seções secundárias (ex: "Como Funciona"), cards de depoimentos. |
| `--border` | `#E2E8F0` | Cinza Claro | Bordas de elementos, divisórias, inputs de formulário. |

## ✒️ Tipografia

A fonte **Inter** foi escolhida por sua modernidade, alta legibilidade em diferentes tamanhos e telas, e seu estilo profissional, ideal para aplicações SaaS.

| Propriedade | Valor | Descrição |
| :---------- | :---- | :-------- |
| **Família da Fonte** | `Inter`, `-apple-system`, `BlinkMacSystemFont`, `"Segoe UI"`, `Roboto`, `sans-serif` | Fonte principal do projeto, com fallbacks para sistemas operacionais. |
| **Importação** | Google Fonts CDN | `https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap` |
| **Pesos da Fonte** | `400` (Regular), `600` (Semibold), `700` (Bold), `800` (ExtraBold) | Utilizados para hierarquia visual e destaque de informações. |

### Tamanhos de Fonte (Base: `16px`)

| Elemento | Tamanho (rem) | Tamanho (px) | Peso da Fonte |
| :------- | :------------ | :----------- | :------------ |
| `h1` | `3.5rem` | `56px` | `800` (ExtraBold) |
| `h2` | `2.5rem` | `40px` | `800` (ExtraBold) |
| `h3` | `1.5rem` | `24px` | `800` (ExtraBold) |
| `p` | `1.125rem` | `18px` | `400` (Regular) |
| `body` | `1rem` | `16px` | `400` (Regular) |
| `small` (footer) | `0.875rem` | `14px` | `400` (Regular) |

## 📐 Outros Elementos Visuais

*   **Raio da Borda (`--radius`)**: `12px` para cantos suavemente arredondados em cartões e botões.
*   **Sombras (`--shadow`)**: `0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05)` para um efeito de elevação sutil.
*   **Espaçamento (`--container-width`)**: `1200px` para a largura máxima do conteúdo, com `2rem` de padding lateral.

Este guia serve como referência para manter a integridade do design do SaaSModern.
