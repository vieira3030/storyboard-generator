
# StoryFrame — Gerador de Storyboards com IA

> Aplicação web que gera storyboards cinematográficos automaticamente a partir de uma narrativa em texto, utilizando Inteligência Artificial.

🔗 **[Ver Aplicação](https://storyboard-generator-three.vercel.app)** &nbsp;|&nbsp; 📁 **[Repositório](https://github.com/vieira3030/storyboard-generator)**

---

## Sobre o Projeto

O **StoryFrame** resolve um problema real de criadores de conteúdo e estudantes de multimédia: a criação de guiões visuais é um processo demorado e manual. Com esta ferramenta, o utilizador descreve a sua narrativa e a IA estrutura automaticamente as cenas, definindo enquadramentos, movimentos de câmara, transições e ambiente.

Desenvolvido no âmbito da unidade curricular de **Engenharia de Software** — IPVC · ESTG · ECGM.

---

## Funcionalidades

- ✅ Geração de storyboard com IA a partir de narrativa em texto
- ✅ 9 géneros cinematográficos (Cinematográfico, Documental, Publicidade, Videoclip, Animação, Videojogo, Série TV, Curta-Metragem, Institucional)
- ✅ 4 a 10 cenas configuráveis
- ✅ Tipos de plano, movimentos de câmara, transições e ambiente por cena
- ✅ Botão de regeneração individual por cena
- ✅ Edição inline de descrições
- ✅ Exportação para PDF
- ✅ Timer de geração
- ✅ Contador de caracteres e botão limpar

---

## Tecnologias

| Tecnologia | Utilização |
|---|---|
| HTML5 + CSS3 + JavaScript | Frontend da aplicação |
| [Groq API](https://groq.com) + LLaMA 3.3 | Motor de IA para geração de storyboards |
| [Vercel](https://vercel.com) | Deploy automático e CI/CD |
| GitHub | Versionamento e colaboração |
| GitHub Projects | Gestão Agile/Scrum |

---

## Como Usar

1. Acede a [storyboard-generator-three.vercel.app](https://storyboard-generator-three.vercel.app)
2. Seleciona o género e o número de cenas
3. Escreve a tua narrativa
4. Clica em **GERAR STORYBOARD**
5. Explora as cenas geradas — podes regenerar ou editar cada uma
6. Exporta para PDF com o botão **EXPORTAR / IMPRIMIR**

---

## Desenvolvimento

O projeto foi desenvolvido com recurso a **Vibe Coding** — toda a aplicação foi gerada através de prompting iterativo com Claude (Anthropic).

### Estrutura do Projeto

```
storyboard-generator/
└── index.html    # Aplicação completa (SPA)
```

### CI/CD

Qualquer push para a branch `main` desencadeia automaticamente um novo deploy na Vercel.

---

## Equipa

| Nome | GitHub |
|---|---|
| Rodrigo Vieira | [@vieira3030](https://github.com/vieira3030) |
| André Flores | [@andre-flores](https://github.com/andre-flores) |

---

## Contexto Académico

**Unidade Curricular:** Engenharia de Software  
**Curso:** Engenharia da Computação Gráfica e Multimédia  
**Instituição:** IPVC · ESTG  
**Ano Letivo:** 2025/2026

---

*Desenvolvido com ❤️ e muito prompting*
