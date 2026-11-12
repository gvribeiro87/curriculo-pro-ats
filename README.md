# curriculo-pro-ats
Desafio DIO - Otimizador inteligente de currículos compatível com sistemas ATS.

# 🚀 CurrículoProATS | Otimizador Inteligente de Currículos (ATS)

> Aplicação web desenvolvida para ajudar profissionais a superarem os filtros automáticos de sistemas de recrutamento (ATS), otimizando palavras-chave e a narrativa do currículo com total transparência e ética.

---

## 🎯 1. Qual problema a sua aplicação resolve?
Muitos profissionais qualificados são eliminados de processos seletivos antes mesmo de seus currículos chegarem às mãos de um recrutador humano. Isso acontece porque os sistemas **ATS (Application Tracking System)** utilizam robôs que barram currículos desalinhados com a descrição da vaga ou que possuem formatações complexas e incompatíveis com a leitura automatizada.

O **CurrículoProATS** resolve essa dor permitindo que o candidato cruze sua trajetória real com a descrição da vaga, identificando lacunas de termos técnicos e gerando uma versão otimizada, limpa e legível para os robôs — mantendo a fidelidade à experiência real do usuário sem inventar competências.

---

## 💻 2. Endereço da Aplicação Publicada
Você pode testar a aplicação rodando ao vivo no link abaixo:
🔗 **[Acessar CurrículoProATS](https://frame-to-form-guide.lovable.app)**

---

## 📝 3. O Mega Prompt Utilizado e sua Evolução
A aplicação foi gerada no **Lovable.dev** a partir de um mega prompt estruturado em Markdown, especificando um design limpo em tons corporativos, painel de match score, gap analysis de palavras-chave e modo escuro/claro.

### Mega Prompt Base:
```markdown
# Projeto: CurrículoProATS - Otimizador Inteligente de Currículos

## 1. Visão Geral
Construa uma aplicação web moderna, limpa, responsiva e altamente profissional chamada CurrículoProATS. O objetivo da aplicação é analisar a compatibilidade entre o currículo de um candidato e a descrição de uma vaga de emprego (Job Description), fornecendo um score de match detalhado, palavras-chave encontradas e ausentes, e gerando uma versão otimizada e limpa do currículo (ATS-friendly). 

A aplicação deve seguir estritamente uma diretriz ética fundamental exibida na interface: "Otimizamos a sua narrativa e palavras-chave para robôs de ATS, mantendo 100% de fidelidade à sua trajetória real (sem inventar experiências ou competências fictícias)".

## 2. Design System & Identidade Visual
- Framework: React com Tailwind CSS e componentes inspirados no shadcn/ui.
- Paleta de Cores: Azul corporativo e cinza claro, com suporte a Dark/Light Mode.

## 3. Estrutura e Funcionalidades
- Entradas: Textareas para colar a Descrição da Vaga e o Currículo Atual.
- Saídas: Match Score percentual, análise de palavras-chave encontradas vs. ausentes, painel ético e o novo currículo ATS-friendly com botões de cópia.

O que mudou do prompt inicial até a versão final:
 Ajustes de espaçamento e UI: Refinamos os cards de palavras-chave ausentes e encontradas para garantir melhor legibilidade e organização visual em telas menores (mobile).
 Feedback de Ação: Aprimoramos o comportamento dos botões de cópia de texto para oferecer uma resposta visual imediata ao usuário.

⚙️ 4. Como a Análise Funciona (Da Vaga ao Currículo Ajustado)
1. Entrada de Dados: O usuário cola a Descrição da Vaga no primeiro bloco e o seu Currículo Atual no segundo bloco.
2. Processamento e Score: Ao clicar em "Analisar Compatibilidade & Gerar ATS", o sistema compara o conteúdo textualmente e gera um Match Score percentual (ex: 20% ou compatibilidade alta/baixa).
3. Diagnóstico de Gaps (Palavras-Chave): A interface separa visualmente as palavras-chave já encontradas (com check verde) daquelas ausentes na vaga (com alertas laranjas/marrons).
4. Orientações e Geração Ética: O sistema fornece diretrizes de como fechar as lacunas honestamente e entrega instantaneamente um Novo Currículo ATS-Friendly limpo, estruturado e pronto para cópia ou exportação.

🛠️ 5. Tecnologias Utilizadas
 Plataforma de Desenvolvimento: Lovable.dev
 Framework: React / TypeScript
 Estilização: Tailwind CSS & Componentes customizados

