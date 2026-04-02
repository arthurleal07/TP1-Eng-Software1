<div align="center">

# 📋 PLANO DE TRABALHO

<sub>Modelo de documento para projetos de desenvolvimento de software</sub>

---

| Campo | Descrição |
|-------|-----------|
| **Nome do Projeto** | Foca & Revisa |
| **Codinome** | Não Possui |
| **Versão** | Alpha 1.0 |
| **Status** | Em desenvolvimento |
| **Número de Controle SRBR-M** | Código de rastreamento interno para identificação do projeto |
| **Executor Principal** | Renan Schultz |
| **Coordenador do Projeto** | Andrey Rodrigues |

</div>

---

## 🕓 Histórico de Versões

| Versão | Descrição | Autor | Data |
|--------|-----------|-------|------|
| `1.0` | Elaboração do Plano de Trabalho | XXXXXX | XXXXXXX |

---

## 📑 Índice

1. [Introdução](#1-introdução)
   - 1.1 [Objeto](#11-objeto)
   - 1.2 [Motivação, Justificativa e Oportunidade](#12-motivação-justificativa-e-oportunidade)
   - 1.3 [Caracterização do Projeto](#13-caracterização-do-projeto)
     - 1.3.1 [Classe](#131-classe)
     - 1.3.2 [Enquadrabilidade](#132-enquadrabilidade)
2. [Informações Gerais](#2-informações-gerais)
   - 2.1 [Escopo Geral](#21-escopo-geral)
     - 2.1.1 [Escopo Específico](#211-escopo-específico)
     - 2.1.2 [Escopo Negativo](#212-escopo-negativo)
   - 2.2 [Ambiente de Desenvolvimento](#22-ambiente-de-desenvolvimento)
   - 2.3 [Características Inovadoras do Projeto](#23-características-inovadoras-do-projeto)
   - 2.4 [Resultados Esperados](#24-resultados-esperados)
3. [Metodologia de Projeto](#3-metodologia-de-projeto)
   - 3.1 [Estrutura do Projeto](#31-estrutura-do-projeto)
   - 3.2 [Equipe de Projeto](#32-equipe-de-projeto-papéis-e-responsabilidades)
4. [Despesas](#4-despesas)
   - 4.1 [Dispêndios](#41-dispêndios)
   - 4.2 [Resumo Financeiro e Valor Total](#42-resumo-financeiro-e-valor-total)

---

## 1. Introdução

> O sistema Foca & Revisa consiste em um aplicativo digital voltado ao apoio de estudantes no processo de organização, concentração e revisão de conteúdos acadêmicos. A solução foi concebida com foco em melhorar a produtividade e a retenção de conhecimento por meio de técnicas estruturadas de estudo.

### 1.1 Objetivo

> O principal objetivo do sistema é auxiliar usuários no gerenciamento do tempo de estudo, promovendo sessões focadas e revisões periódicas, contribuindo para um aprendizado mais eficiente e contínuo.

---

### 1.2 Motivação, Justificativa e Oportunidade

Explica o **motivo pelo qual o projeto é relevante**, destacando problemas que ele resolve e as oportunidades de aplicação.

**Exemplo:**
> A fase do pré-vestibular é a etapa mais importante da vida do estudante, nesta etapa o estudante visa como estudar de forma coerente, inteligente, entender a matéria para aprender-la, para um estudo efetivo o estudante visa procurar técnicas que molhoram o seu aprendizado e uma delas é o pomodoro e a revisão de conteúdo. Este aplicativo visa ajudar no foco do estudante nos seus estudos utilizando a técnica do pomodoro junto com a revisão com flashcards, para que o usuário tenha um aumento na performance e produtivo dos seus estudos. 

---

### 1.3 Caracterização do Projeto

Aqui são definidos atributos que classificam o projeto em diferentes categorias.

#### 1.3.1 Classe

Indica a **categoria geral do projeto**, especificando suas características principais.

| Classe | Detalhamento |
|--------|-------------|
| **Aplicativo Móvel** | Um app de revisão com flashcard e integração da técnica pomodoro |

#### 1.3.2 Enquadrabilidade

Define em que **contexto ou regulamento** o projeto se encaixa (finalidade, licenciamento, conformidade com normas).

| Enquadrabilidade | Detalhamento |
|-----------------|-------------|
| **Software Educacional** | O sistema será utilizado por universidades para gestão de eventos acadêmicos |


---

## 2. Informações Gerais

> O que o projeto pretende desenvolver

Pretendemos entregar uma plataforma que vá além de um simples cronômetro ou um app de cartões. O sistema inclui:

Timer Pomodoro personalizável (tempo de foco, pausas curtas e longas)
Sistema de flashcards com algoritmo de repetição espaçada
Dashboard de desempenho (tempo estudado, taxa de acerto, evolução)
Organização por disciplinas e temas
Notificações inteligentes para manter consistência de estudo
Sincronização em nuvem para acesso multiplataforma

A ideia central é transformar estudo em um processo contínuo, mensurável e adaptativo.

Inovação do Projeto

O diferencial não está apenas nas funcionalidades isoladas, mas na integração entre elas.

Hoje, aplicativos de Pomodoro (como Focus To-Do) e plataformas de flashcards (como Anki) funcionam de forma separada.

Nosso projeto une esses dois fluxos em uma única experiência contínua:

O momento de pausa deixa de ser passivo e passa a ser produtivo
O conteúdo revisado é automaticamente baseado no desempenho do usuário
O ciclo de estudo se torna mais eficiente sem aumentar a carga cognitiva

Além disso, pretendemos incorporar no futuro:

IA para geração automática de flashcards a partir de textos
Análise preditiva de desempenho
Sugestões de estudo personalizadas

Tecnologias Utilizadas

O desenvolvimento será estruturado com tecnologias modernas e escaláveis:

Frontend Mobile: Flutter (multiplataforma – Android e iOS)
Backend: Node.js com API REST
Banco de Dados: Firebase (tempo real e autenticação)
Armazenamento e sincronização: Cloud integrada
Futuro (IA): APIs de processamento de linguagem natural

Essa stack permite rápida prototipação, escalabilidade e baixo custo inicial de infraestrutura.

Limitações do Projeto

Como qualquer solução em fase inicial, temos algumas limitações:

Dependência de engajamento do usuário (disciplina ainda é um fator externo)
Algoritmos de repetição espaçada podem exigir ajustes com base no uso real
Competição com apps já consolidados no mercado
Necessidade de validação contínua da experiência do usuário (UX)

Além disso, a integração entre foco e revisão precisa ser cuidadosamente balanceada para não gerar sobrecarga cognitiva.

### 2.1 Escopo Geral

O escopo geral descreve, de forma ampla, as **funcionalidades e objetivos principais** do sistema.

> O projeto visa desenvolver uma plataforma mobile multiplataforma (Android e iOS) que integra um sistema de Timer Pomodoro personalizável com um mecanismo de flashcards baseado em repetição espaçada, permitindo que o usuário gerencie seus ciclos de foco e revisão de conteúdo em um único ambiente. A solução conta com organização por disciplinas e temas, dashboard de desempenho com métricas de evolução, notificações inteligentes para consistência de estudos e sincronização em nuvem para acesso multiplataforma — transformando o estudo em um processo contínuo, mensurável e adaptativo.

#### 2.1.1 Escopo Específico

Detalha as **funcionalidades e requisitos** que serão implementados.

- Timer pomodoro configurável
- Contador de sessões
- Estatísticas de progresso do usuário
- Limite de 20 flashcards (versão gratuita)

#### 2.1.2 Escopo Negativo

Define **o que NÃO será desenvolvido**, evitando expectativas erradas.

**Exemplo:**
- Não haverá integração com redes sociais para login
- O sistema não incluirá uma versão web
- Não será implementada uma IA para a versão gratuita

---

### 2.2 Ambiente de Desenvolvimento

Tecnologias e ferramentas que serão utilizadas no desenvolvimento do projeto.

| Componente | Tecnologia / Ferramenta |
|------------|------------------------|
| **Metodologia** | Scrum com sprints |
| **Gerenciamento de Backlog** | GitHub |
| **Repositório de Código** | GitHub |
| **Modelagem de Software** | Draw.io (diagrama de classes, fluxo de telas) |
| **Desenvolvimento do MVP** | `xxxxx` |

---

### 2.3 Características Inovadoras do Projeto

O que torna o projeto **diferente de soluções já existentes**.

**Exemplo:**
- 🔗 **Integração nativa:** O aplicativo vem com a junção de duas funções como uso do timer pomodoro e flashcards no mesmo app.
- 📚 **Organização simplificada para estudante:** Foco em algo que aluno realmente precisa: Matéria → Tópico → Flashcards
- 📊 **Métricas simples:** Mostrar dados para o aluno como: Quantos Pomodoros por matéria
Quantos flashcards revisados
Taxa de acerto básica (%)

---

### 2.4 Resultados Esperados

Principais resultados esperados após a conclusão do projeto.

**Exemplo:**
- ✅ Um app que ajude na performance nos estudos 
- ✅ x
- ✅ Interface intuitiva para o usuário
- ✅ Estatísticas positivas sobre o progresso do usuário

---

## 3. Metodologia de Projeto

> Esta seção descreve como o projeto será conduzido, desde a concepção até a entrega do MVP (Produto Mínimo Viável).

### 3.1 Estrutura do Projeto

O desenvolvimento será dividido em **cinco fases principais**, seguindo a abordagem ágil com Scrum.

```
📦 Projeto
 ┣ 📌 Fase 1 — Ideação
 ┣ 📌 Fase 2 — Levantamento de Requisitos
 ┣ 📌 Fase 3 — Projeto e Arquitetura
 ┣ 📌 Fase 4 — Projeto dos Casos de Teste
 ┗ 📌 Fase 5 — Desenvolvimento do MVP
```

---

### 3.2 Equipe de Projeto: Papéis e Responsabilidades

A equipe será composta por **até 5 alunos**, com papéis definidos para otimizar o desenvolvimento.

| Integrante | Papel / Responsabilidades |
|-----------|--------------------------|
| Ian Gabriel | Ideação do projeto |
| Caio Gonzaga | Levantamento de requisitos |
| Renan Schultz | Pojeto e Arquitetura |
| Francisco José | Projeto dos Casos de Teste |
| Arthur | Desenvolvimento do MVP |

---

## 4. Despesas

### 4.1 Dispêndios

#### 4.1.1 Equipamentos e Programa de Computador

| Item                          | Descrição                                                                 | Tipo            | Custo Estimado (R$) | Observação                                      |
|-------------------------------|---------------------------------------------------------------------------|-----------------|---------------------|-------------------------------------------------|
| Notebook/Computador           | Equipamento para desenvolvimento do aplicativo                           | Equipamento     | 3.000 – 5.000       | Pode ser já possuído pelo desenvolvedor         |
| Smartphone para testes        | Dispositivo Android para testes do app                                   | Equipamento     | 800 – 2.000         | Pode ser o próprio celular do desenvolvedor     |
| Flutter                       | SDK para desenvolvimento mobile multiplataforma                          | Software        | Gratuito            | Open source                                     |
| Visual Studio Code            | Editor de código                                                         | Software        | Gratuito            | Leve e amplamente utilizado                     |
| Android Studio                | IDE oficial para desenvolvimento Android (emulador incluso)              | Software        | Gratuito            | Necessário para testes e build                  |
| Firebase                      | Backend (autenticação, banco de dados, hospedagem)                       | Serviço         | Gratuito (plano inicial) | Pode gerar custos conforme uso               |
| GitHub                        | Controle de versão e repositório                                         | Serviço         | Gratuito            | Essencial para organização do projeto           |
| Conta Google Play Developer   | Publicação do app na Play Store                                          | Serviço         | ~125 (taxa única)   | Pago apenas uma vez                             |
| Internet                      | Conexão para desenvolvimento e testes                                    | Serviço         | 120 – 200/mês        | Considerar custo mensal                         |

---

#### 4.1.2 Materiais de Consumo

| # | Descrição | Qtd. | Valor Unit. (R$) | Valor Total (R$) |
|---|-----------|:----:|:----------------:|:----------------:|
| 1 | Roteador | 1 | 250,00 | 250,00 |
| 2 | Materiais de escritório | 1 | 200,00 | 200,00 |
| 3 | Materiais elétricos (fontes) | 10 | 30,00 | 300,00 |
| 4 | Chip ESP-12 – ESP8266 | 10 | 30,00 | 600,00 |
| 5 | Bateria lítio | 10 | 70,00 | 700,00 |
| 6 | Led infravermelho | 100 | 1,00 | 100,00 |
| 7 | Placas fenolite dupla face | 10 | 20,00 | 200,00 |
| 8 | Solda | 1 | 50,00 | 50,00 |
| 9 | Filamento ABS / Esp8266 Chip ESP-12 | 3 | 140,00 | 420,00 |
| 10 | Resistores 2 ohms e 3 ohms | 40 | 1,00 | 40,00 |
| 11 | Redutor de tensão | 50 | 2,00 | 100,00 |
| | | | **Total** | **R$ 2.660,00** |

---

#### 4.1.3 Treinamento

> Treinamentos não serão necessários ao projeto, pois já estão inclusos nas licenças dos softwares descritos no item 4.1.1.

---

#### 4.1.4 Serviço Técnico de Terceiros

| # | Especificação | Custo (R$) |
|---|--------------|:----------:|
| 1 | Serviço técnico especializado de design de aplicativos | 4.000,00 |
| 2 | Servidor de hospedagem para o site de divulgação | 510,00 |
| 3 | Alteração contratual de endereço da empresa para CIDE | 475,00 |
| 4 | Serviço de impressão de moldes plásticos e montagem das placas nos moldes | 1.500,00 |
| 5 | Marketing: logo, banners, panfletos, camisas | 1.500,00 |
| 6 | Serviço de criação de embalagem da iZBox | 2.000,00 |
| 7 | Serviço técnico especializado em teste de usabilidade | 2.000,00 |
| 8 | Assessoria em Marketing Digital | 2.500,00 |
| 9 | Assessoria em Marketing Digital | 2.500,00 |
| 10 | Assessoria em Marketing Digital | 2.500,00 |
| 11 | Assessoria em Marketing Digital | 2.500,00 |
| | **Total** | **R$ 21.975,00** |

---

### 4.2 Resumo Financeiro e Valor Total

<div align="center">

**⏱️ Duração do Projeto: 9 meses**

</div>

| Item | Valor Total (R$) | % |
|------|:----------------:|:---:|
| Programas de Computador, Máquinas, Equipamentos, Aparelhos e Instrumentos | 0,00 | 0,00% |
| Implantação, Ampliação ou Modernização de Laboratório | 0,00 | 0,00% |
| Recursos Humanos Diretos | 36.258,39 | 36,26% |
| Recursos Humanos Indiretos | 0,00 | 0,00% |
| Livros e Periódicos Técnicos | 0,00 | 0,00% |
| Materiais de Consumo | 2.660,00 | 2,66% |
| Viagens | 8.750,00 | 8,75% |
| Treinamento | 0,00 | 0,00% |
| Serviço Técnico de Terceiros | 21.975,00 | 21,98% |
| Outros Correlatos | 6.750,00 | 14,95% |
| Provisão de Encerramento | 0,00 | 0,00% |
| Custos Incorridos e Constituição de Reserva | 0,00 | 0,00% |
| Margem 10% | 7.639,34 | 9,09% |
| Impostos Retidos em NF (19%) | 15.966,22 | 15,97% |
| **TOTAL** | **R$ 99.998,95** | **100%** |

---

<div align="center">
<sub>Documento gerado a partir do modelo de Plano de Trabalho — versão 1.0</sub>
</div>
