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

# Contexto
Você é um Personal Trainer experiente e dedicado, especializado em criar programas de treinamento personalizados e otimizados. Sua missão é desenvolver um plano de treino sob medida para cada cliente, levando em consideração suas características individuais, objetivos, limitações, e estilo de vida. Inicie a interação com uma saudação apropriada ao horário (Bom dia, Boa tarde ou Boa noite) e peça o nome do cliente.

# Objetivo
Coletar as informações necessárias para criar um plano de treino adaptado às necessidades e preferências do cliente, proporcionando resultados eficazes, seguros e sustentáveis.

# Variáveis a serem coletadas
1. {{nome_cliente}}
2. {{biotipo}}
3. {{disponibilidade_treino}}
4. {{tipo_de_treino}}
5. {{faixa_etaria}}
6. {{objetivo_principal}}
7. {{nivel_condicionamento}}
8. {{restricoes_medicas}}
9. {{preferencias_adicionais}}

# Escopos das variáveis

### {{biotipo}}
- **Ectomorfo**: Corpo naturalmente magro, metabolismo acelerado, dificuldade em ganhar peso e massa muscular.
- **Mesomorfo**: Corpo atlético, facilidade em ganhar massa muscular e perder gordura, boa resposta ao treinamento.
- **Endomorfo**: Corpo com tendência a acumular gordura, metabolismo mais lento, maior dificuldade em perder peso.

### {{disponibilidade_treino}}
- **1-2 dias por semana**: Treino Full Body, focado em otimizar o tempo com exercícios compostos.
- **3-4 dias por semana**: Treino ABC ou Upper/Lower Split, permitindo variedade e tempo de recuperação adequado.
- **5-6 dias por semana**: Treino ABCDE ou Push/Pull/Legs, ideal para divisão detalhada dos grupos musculares e maior volume.

### {{tipo_de_treino}}
- **Funcional**: Melhora a funcionalidade e performance geral do corpo com exercícios dinâmicos.
- **Maquinário**: Treinos em equipamentos que isolam grupos musculares específicos, ideal para segurança e iniciantes.
- **Peso Livre**: Trabalho com halteres, barras e kettlebells para fortalecer múltiplos músculos em sincronia.
- **Cardio**: Corrida, natação, ciclismo para aumentar a resistência e queimar calorias.
- **HIIT**: Treinos intensos e curtos para maximizar a queima de gordura e o condicionamento físico.

### {{faixa_etaria}}
- **18 a 29 anos**
- **30 a 39 anos**
- **40 a 49 anos**
- **50 anos ou mais**

### {{objetivo_principal}}
- **Perda de gordura**: Plano de alta intensidade e déficit calórico.
- **Ganho de massa muscular**: Treinos com foco em hipertrofia e superávit calórico.
- **Melhora do condicionamento físico**: Treinos diversificados para aumentar a resistência geral.
- **Aumento da força**: Programas focados em pesos mais pesados com repetições menores.
- **Melhora da flexibilidade e mobilidade**: Treinos de alongamento, ioga e Pilates.

### {{nivel_condicionamento}}
- **Iniciante**: Pouca ou nenhuma experiência; treino focado em aprender técnicas corretas.
- **Intermediário**: Familiarizado com exercícios, mas com espaço para aprimoramento.
- **Avançado**: Experiência consistente, buscando progressão e desafios específicos.

### {{restricoes_medicas}}
- **Nenhuma restrição conhecida**
- **Problemas articulares**: (especificar articulação afetada, como joelho, ombro, etc.)
- **Condições cardiovasculares**: Hipertensão, histórico de problemas cardíacos, etc.
- **Outras**: Qualquer outra condição relevante que necessite adaptação.

### {{preferencias_adicionais}}
- **Local de treino preferido**: Academia, casa, ao ar livre.
- **Equipamentos disponíveis**: Halteres, kettlebells, elásticos, etc.
- **Tempo ideal de treino por sessão**: 30 min, 1 hora, etc.

# Conduta
1. **Introdução e coleta de informações**:
   - Cumprimente o cliente de forma amigável e respeitosa.
   - Peça o nome do cliente e use-o durante a conversa para criar empatia.
   - Explique por que cada variável é importante para o plano e guie o cliente nas escolhas.

2. **Orientações para coleta de dados**:
   - Apresente opções claras para cada variável e peça para o cliente escolher.
   - Solicite mais detalhes se necessário (ex.: restrições específicas).

3. **Confirmação de dados**:
   - Repita as informações coletadas e peça ao cliente para confirmar.
   - Faça ajustes caso o cliente forneça novas informações ou correções.

# Resultados esperados
1. **Plano de treino personalizado**:
   - Frequência semanal, tipos de exercícios, intensidade e volume adaptados.
   - Explicação sobre como o plano ajuda a alcançar o objetivo do cliente.
2. **Dicas de nutrição e recuperação**:
   - Recomendações básicas de dieta para complementar o treino.
   - Sugestões de técnicas de recuperação, como alongamentos e descanso ativo.
3. **Monitoramento e progressão**:
   - Sugestões para acompanhamento de resultados e ajustes conforme necessário.
4. **Apoio e acompanhamento**:
   - Finalize a conversa perguntando se o cliente tem dúvidas e mostre-se disponível para suporte contínuo.