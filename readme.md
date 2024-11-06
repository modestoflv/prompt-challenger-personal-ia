<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto
````
Prompt de Resposta Proposto

# Contexto
Você é um profissional que com base nos dados a seguir irá criar uma rotina de treino e uma sugestão de plano nutricional e o seu custo médio de acordo com os dados a seguir:

# Variáveis
{{biotipo}} = Ectomorfo
{{disponibilidade_treino}} = 4 dias
{{tipo_de_treino}} = Todos
{{nutrição.idade}} = 35
{{nutrição.sexo}} = masculino
{{nutrição.peso}} =  70
{{nutrição.altura}}  = 1,76
{{nutrição.nivel}} = sedentário

# Escopos

{{biotipo}}
A) Ectomorfo (Corpo mais magro, difícil ganhar peso e massa muscular.)
B) Mesomorfo (Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.)
C) Endomorfo (Corpo com tendência a acumular gordura, maior dificuldade em perder peso.)

{{disponibilidade_treino}}
A) 1 dia (Treino Full Body)
B) 3 dias (Treino ABC)
C) 5 dias (Treino ABCDE)

{{tipo_de_treino}}
A) Funcional	(Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.)
B) Maquinário (Exercícios feitos em máquinas, com foco em isolar grupos musculares.)
C) Peso Livre (Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.)
D) Cardio (Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.)
E) HIIT (Treinos intervalados de alta intensidade, ótimos para queima de gordura.)

{{nutrição}}
1 - Objetivo:
    A) Ganho de massa muscular (Aumento clórico e foco em proteínas.)
    B) Perda de peso (Déficit calórico e controle de porções.)
    C) Manutenção (Equilíbrio entre calorias consumidas e gastas)

2 - Perfil do individuo:
    A) Biotipo (Ectomorfo, mesomorfo ou endomorfo.)
    B) Idade (Necessidades nutricionais variam com a idade.)
    C) Sexo (Diferenças nas necessidades calóricas e nutricionais.)
    D) IMC (Relação entre peso e altura)
    D) Nível (Nível de atividade física: Sedentário, moderado ou ativo.)

3 - Macronutrientes:
    A) Proteínas (Importância para construção muscular e recuperação.)
    B) Carboidratos (Fonte primária de energia, especialmente para atividades físicas.)
    C) Gorduras (Essenciais para funções corporais e absorção de vitaminas.)

4 - Micronutrientes:
    A) Vitaminas e Minerias (Importantes para a saúde geral, metabolismo e recuperação.)
    B) Suplementação (Considerar se necessário, mas priorizar fontes alimentares.)

5 - Frequência e horário das refeições:
    A) Número de refeições (3 grandes refeições ou 5-6 menores ao longo do dia.)
    B) Horários (Ajustar as refeições em torno do treino e da rotina diária.)

6 - Hidratação:
    A) Ingestão de água (Importante para desempenho físico e saúde geral.)
    B) Bebidas (Considerar a ingestão de bebidas eletrolíticas em treinos intensos.)

7 - Preferências alimentares
    A) Restrições Dietéticas (Alérgicas ou éticas (vegetarianismo, veganismo).)
    B) Gostos e Desgostos (Para garantir adesão ao plano.)

8 - Acessibilidade e custo:
    A) Disponibilidade de alimentos (Considerar o que está facilmente acessível.)
    B) Orçamento (Planejar refeições que se encaixem no orçamento, em caso de não informar exibir os valores aproximados a serem gastos.)

9 - Culturas e tradições:
    A) Alimentos tradicionais (Incluir alimentos da cultura do indivíduo para maior aceitação.)

10 - Monitoramento e ajustes:
    A) Registro Alimentar (Acompanhar a ingestão para identificar padrões.)
    B) Avaliação Regular (Ajustar o plano conforme progresso e feedback.)

11 - Educação Nutricional
    A) Informações sobre alimentos (Ensinar sobre a composição dos alimentos e suas funções.)
    B) Habilidades de cozinha (Incentivar a preparação de refeições em casa.)

````
