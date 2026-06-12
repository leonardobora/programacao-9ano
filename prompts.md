# 🏆 Simulador da Copa do Mundo 2026 - Vibe Coding 

[![Formando Crianças para o Futuro](https://img.shields.io/badge/Programa-Formando_Crianças_para_o_Futuro-blue)](#)
[![Ano](https://img.shields.io/badge/Turma-9º_Ano-brightgreen)](#)
[![Tech](https://img.shields.io/badge/Tech-HTML_%7C_CSS_%7C_JS-orange)](#)

Este repositório contém os projetos realizados em conjunto com a turma do 9° ano do programa **Formando Crianças para o Futuro 2026**. O nosso principal objetivo foi explorar a transição do paradigma tradicional de programação (focado na memorização de sintaxe) para o **Vibe Coding** (programação assistida por IA, com foco em orquestração lógica e resolução de problemas).

## 💡 Sobre o Projeto

Para engajar os alunos, utilizamos o tema da **Copa do Mundo de 2026**. Em vez de escrevermos código do zero, os alunos atuaram como "Diretores de Lógica". Eles utilizaram ferramentas de Inteligência Artificial Generativa (Gemini) para gerar um **Simulador de Classificação do Grupo C** (grupo do Brasil), a partir de instruções (*prompts*) detalhadas.

O projeto foi dividido em duas etapas gamificadas:
1. **Geração do Esqueleto & Sistema de Missões:** A IA gera a interface base em *Glassmorphism* (intencionalmente cinzenta e incompleta) e um script de auto-validação.
2. **A Iteração (Vibe Coding):** Os alunos interagem com a IA para corrigir o design, inserir os dados corretos (bandeiras) e alterar o CSS, completando as missões que o próprio sistema valida em tempo real.

---

## 💻 Os Prompts Utilizados na Aula

### ETAPA 1 - O Esqueleto e a Gamificação
*O prompt abaixo foi utilizado para criar a aplicação base e o sistema de validação (checklist) no ecrã.*

> Atue como um Desenvolvedor Web Sênior Front-end. Crie um 'Simulador da Copa 2026 - Grupo C' num único arquivo HTML (com CSS moderno e JavaScript embutidos). Inspire-se em designs modernos com 'glassmorphism', usando variáveis no :root para as cores principais.
> 
> **A Lógica do Simulador:**
> A tela mostra os 3 jogos do Brasil: Brasil x Marrocos, Brasil x Haiti e Brasil x Escócia. Para cada jogo, dois inputs numéricos (placar) e botões 'Calcular'.
> O JS calcula: Vitória = 3 pts, Empate = 1 pt, Derrota = 0 pts. Mostre o total.
> Textos de status: >=7 pts ('Rumo ao Hexa!'), 4-6 pts ('Classificado com emoção'), <4 pts ('Eliminado').
> 
> **O Painel de Missões (Gamificação):**
> Crie um painel lateral fixo ou um card de destaque chamado 'Missões do Vibe Coder'.
> Crie uma função em JavaScript (usando setInterval a cada 2 segundos) que verifique automaticamente se as 3 missões abaixo foram cumpridas no DOM. Se sim, risque o texto da missão e adicione um emoji de ✅.
> 
> **As 3 Missões que o JS deve validar:**
> Missão 1 (Identidade): O título da página `<h1 id="group-name">` deve ser alterado de exatamente '[NOME DO GRUPO]' para qualquer outra coisa.
> Missão 2 (Bandeiras): O texto da página não pode mais conter a string '[FLAG]' e deve conter pelo menos dois emojis de bandeira (ex: 🇧🇷).
> Missão 3 (Brasil Core): A variável CSS `--accent-color` (que começa como '#cccccc' cinza) deve ser alterada para alguma variação de verde (ex: '#009b3a', '#00ff00', 'green') ou amarelo.
> 
> **Design Inicial Intencionalmente Incompleto:**
> Título principal deve ser estritamente: `<h1 id="group-name">[NOME DO GRUPO]</h1>`.
> Ao lado do nome dos países, coloque exatamente o texto `[FLAG]`.
> O design deve ser escuro (dark mode), bonito, translúcido, mas com a variável `--accent-color` definida como um cinza chato (#555555). As cores brasileiras NÃO DEVEM existir ainda.


### ETAPA 2 - O "Vibe Coding" na Prática
*Com a aplicação a rodar, os alunos identificam o que falta e dão a instrução final para a IA aplicar a sua "vibe", desbloqueando as missões no ecrã.*

> A estrutura ficou excelente! Agora eu preciso que você atualize o código para completarmos as missões do nosso checklist:
> 
> 1. Substitua o título '[NOME DO GRUPO]' para o nome da nossa equipe: 'Os Vibe Coders do Hexa'.
> 2. Substitua todos os textos '[FLAG]' pelos emojis das bandeiras corretas de cada país (Brasil, Marrocos, Haiti, Escócia).
> 3. Altere a variável CSS `--accent-color` para o verde oficial da bandeira do Brasil (#009b3a) e adicione toques de amarelo e azul nos botões e no painel para dar uma 'vibe' de Copa do Mundo.
> 
> Me devolva o arquivo HTML completo e atualizado.

---

## 🎯 Resultados de Aprendizagem
Através desta abordagem, os alunos aprenderam que programar na era da Inteligência Artificial requer **letramento lógico** e **senso crítico**. Eles compreenderam conceitos de manipulação do DOM e Variáveis CSS de forma orgânica, vendo o sistema reagir em tempo real aos seus comandos em linguagem natural.

Desenvolvido com 💚 pelos alunos do 9º Ano.
