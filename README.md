# Prompt_Engineer_Personal_Trainer_IA
Agora é a hora de brilhar, construi um perfil de destaque na DIO! Explorei todos os conceitos explorados até aqui e repliquei neste projeto prático.
Para isso, criei este repositório e aumentei ainda mais meu portfólio de projetos no GitHub, o qual posso fazer toda diferença em minhas entrevistas técnicas 😎

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

"Baseado no biotipo **[ECTOMORFO/MESOMORFO/ENDOMORFO]**, com uma disponibilidade de **[X]** dias por semana, e com preferência por **[TIPO DE EXERCÍCIO]**, o plano de treino ideal deve incluir **[DETALHES DO TREINO ESPECÍFICO]**. Para alcançar o objetivo de **[OBJETIVO]**, recomenda-se seguir um treino **[TIPO DE TREINO]** combinado com **[OUTRO EXERCÍCIO]**."

Esse prompt gera uma resposta que considera todos os fatores inseridos pelo usuário para oferecer um plano de treino personalizado.

---

## 🎯 Prompt de Resposta Aprimorado

"Com base nas características fornecidas, identificamos que seu biotipo é **[ECTOMORFO/MESOMORFO/ENDOMORFO]**, 
o que indica que seu metabolismo tende a **[PERFIL METABÓLICO]**, 
resultando em **[FACILIDADE/DIFICULDADE]** para **[GANHAR MASSA/PERDER GORDURA]**. 

Com uma disponibilidade de **[X]** dias por semana para treinos, 
a periodização ideal envolverá um plano dividido em fases de **[ESTRATÉGIA DE TREINO]**, 
otimizando **[DESENVOLVIMENTO MUSCULAR/DESEMPENHO/CONDICIONAMENTO CARDIOVASCULAR]**.


Dado que você prefere realizar exercícios do tipo **[FUNCIONAL/MAQUINÁRIO/PESO LIVRE/CARDIO/HIIT]**, 
será montado um plano com foco em **[DETALHES DO EXERCÍCIO]**, priorizando **[FORÇA, RESISTÊNCIA, MOBILIDADE]** 
e integrando exercícios como **[EXEMPLOS DE EXERCÍCIOS ESPECÍFICOS]**. 


O treinamento será periodizado em **[MICROCICLOS/MACROCICLOS]**, 
incorporando técnicas de sobrecarga progressiva para maximizar o ganho de **[MASSA/RESISTÊNCIA/CAPACIDADE AERÓBICA]** 
sem sobrecarregar o sistema muscular ou cardiovascular.


Para atingir o objetivo de **[GANHO DE MASSA/PERDA DE GORDURA/AUMENTO DE RESISTÊNCIA]**, o plano será estruturado da seguinte forma:

Segunda a sexta-feira: Treinamento **[FOCADO EM GRUPOS MUSCULARES ESPECÍFICOS, COM ÊNFASE NO DESENVOLVIMENTO FUNCIONAL E HIPERTROFIA]**.

Sábado/Domingo: Atividades regenerativas como **[CAMINHADAS/CARDIO LEVE/YOGA]**, otimizando a recuperação e prevenindo lesões.


Além disso, estratégias complementares como **[ESTRATÉGIAS NUTRICIONAIS]** e **[DESCANSO ADEQUADO]** serão essenciais para maximizar os resultados.

É altamente recomendado incorporar **[MÉTODOS DE RECUPERAÇÃO]** como **[CRIOTERAPIA, MASSAGENS DESPORTIVAS]** para garantir que seu corpo tenha o tempo necessário para se adaptar e crescer.


Ao longo do plano, será realizada uma avaliação contínua de **[METAS DE PERFORMANCE E COMPOSIÇÃO CORPORAL]**, ajustando o volume e a intensidade conforme necessário, garantindo assim a máxima eficiência e sustentabilidade no progresso. 

O uso de métodos de treinamento avançado como **[DROP SETS/SUPERSETS/INTERVALOS DE ALTA INTENSIDADE]** será incorporado nos treinos para acelerar seus resultados e otimizar o tempo disponível."

---

## 🎯Prompt adaptado para Claude 3

" Baseado nas informações fornecidas, você é responsável por criar um plano de treino personalizado para o usuário. Aqui estão as informações que você deve considerar:

- Biotipo do usuário: **[ECTOMORFO/MESOMORFO/ENDOMORFO]**
- Dias disponíveis por semana para treinos: **[NÚMERO DE DIAS]**
- Tipo de exercício preferido: **[FUNCIONAL/MAQUINÁRIO/PESO LIVRE/CARDIO/HIIT]**
- Objetivo do usuário: **[GANHAR MASSA/PERDER GORDURA/AUMENTAR RESISTÊNCIA]**

Com essas informações, crie uma resposta personalizada. Siga este modelo:

1. **Biotipo**: Explique as características do biotipo corporal do usuário e como isso impacta o plano de treino.
   
2. **Dias de treino**: Sugira um tipo de treino adequado ao número de dias disponíveis, como "Treino Full Body" (1 dia), "Treino ABC" (3 dias) ou "Treino ABCDE" (5 dias).
   
3. **Tipo de exercício preferido**: Detalhe os benefícios do tipo de exercício escolhido pelo usuário e como ele será incorporado ao plano de treino.
   
4. **Objetivo do usuário**: Propor um plano de treino específico focado no objetivo (ganhar massa, perder gordura ou aumentar resistência). Inclua recomendações extras, como exercícios complementares.
   

Por exemplo:

"Baseado no biotipo **Mesomorfo**, com uma disponibilidade de **5 dias por semana**, e com preferência por **Peso Livre**, o plano de treino ideal deve incluir uma divisão de treinos **ABCDE**, onde cada dia focará em um grupo muscular diferente. 

Para alcançar o objetivo de **Ganhar Massa**, recomenda-se seguir um treino focado em **Hipertrofia**, utilizando sobrecarga progressiva em exercícios compostos como agachamentos, levantamento terra, e supino. 
Além disso, recomenda-se incorporar atividades regenerativas, como caminhadas leves e sessões de yoga para uma recuperação adequada."

Responda utilizando esse modelo, ajustando os detalhes de acordo com as informações fornecidas."


