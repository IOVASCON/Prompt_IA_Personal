# Criando um Personal Trainer IA com Regras Avançadas de Prompt Engineer

## Objetivo

Este projeto é uma extensão do desafio original de Prompt Engineer, onde o objetivo é criar um prompt que gera um plano de treino ideal baseado em diversas variáveis fornecidas pelo usuário. O assistente de personal trainer automatizado, alimentado por IA, agora utiliza regras de negócio mais avançadas, considerando fatores como biotipo corporal, dias disponíveis, tipo de exercício preferido, objetivo do treino, nível de experiência, tempo disponível por sessão e equipamentos acessíveis. O plano de treino personalizado será gerado de forma a atender às características e necessidades específicas de cada usuário.

O projeto utiliza as boas práticas de prompt engineer para garantir que as informações sejam processadas de forma precisa e o treino seja adequado aos objetivos do usuário.

## Introdução

Este projeto visa criar um assistente de personal trainer que gera treinos altamente personalizados. O usuário fornecerá uma série de informações que incluem, além do biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, o objetivo do treino, o nível de experiência, o tempo disponível por sessão e os equipamentos disponíveis.
Com base nessas informações, o assistente gerará um plano de treino completo e ajustado aos objetivos e condições específicas de cada usuário.

As instruções de uso do prompt estão detalhadas nas regras de negócio a seguir.

## Regras de Negócio

Para criar o plano de treino personalizado, o assistente de IA segue as seguintes regras de negócio:

1. **Biotipo Corporal:**

    - O usuário deve identificar seu biotipo corporal, que será usado para ajustar o tipo e a intensidade do treino.
    - Opções: Ectomorfo, Mesomorfo, Endomorfo.

2. **Dias Disponíveis para Treinar:**

    - O usuário deve indicar quantos dias por semana está disponível para treinar. O número de dias influenciará a divisão do treino.
    - Opções: 1 dia (Treino Full Body), 3 dias (Treino ABC), 5 dias (Treino ABCDE).

3. **Tipo de Exercício Preferido:**

    - O usuário deve escolher o tipo de exercício que prefere realizar durante o treino.
    - Opções: Funcional, Maquinário, Peso Livre, Cardio, HIIT.

4. **Objetivo do Treino:**

    - O objetivo principal do treino deve ser informado para ajustar o foco dos exercícios.
    - Opções: Ganho de massa muscular, Perda de gordura, Manutenção física, Melhora de condicionamento físico.

5. **Nível de Experiência:**

    - O nível de experiência do usuário impacta a dificuldade e a complexidade do plano de treino.
    - Opções: Iniciante, Intermediário, Avançado.

6. **Tempo Disponível por Sessão:**

    - O tempo que o usuário tem disponível para cada sessão de treino ajuda a determinar o volume e a estrutura do treino.
    - Opções: 30 minutos, 45 minutos, 1 hora.

7. **Equipamentos Disponíveis:**

    - O tipo de equipamento disponível para o usuário será utilizado para escolher os exercícios mais adequados.
    - Opções: Somente peso corporal, Halteres, Máquinas, Todos.

# PROMPT DO PLANO DE TREINAMENTO A SER ENVIADO À IA

## Prompt para Assistente Personal Trainer IA Expandido

**Objetivo:** Montar um plano de treino personalizado baseado nas seguintes informações fornecidas pelo usuário:

**Entrada de Dados:**

1. **Biotipo Corporal (Escolha um):** ENDOMORFO

    - Ectomorfo (Dificuldade em ganhar massa muscular)
    - Mesomorfo (Facilidade para ganhar massa muscular)
    - Endomorfo (Tendência a acumular gordura)

2. **Dias Disponíveis para Treinar (Escolha um):** 5 DIAS

    - 1 dia (Treino Full Body)
    - 3 dias (Treino ABC)
    - 5 dias (Treino ABCDE)

3. **Tipo de Exercício Preferido (Escolha um):** MAQUINÁRIO

    - Funcional (Melhora da funcionalidade corporal)
    - Maquinário (Uso de máquinas para isolar grupos musculares)
    - Peso Livre (Halteres, barras e exercícios com pesos livres)
    - Cardio (Melhora do sistema cardiovascular)
    - HIIT (Alta intensidade para queima de gordura)

4. **Objetivo do Treino (Escolha um):** GANHO DE MESSA MUSCULAR

    - Ganho de massa muscular
    - Perda de gordura
    - Manutenção física
    - Melhora de condicionamento físico

5. **Nível de Experiência (Escolha um):** INICIANTE

    - Iniciante
    - Intermediário
    - Avançado

6. **Tempo Disponível por Sessão (Escolha um):** 45 MINUTOS

    - 30 minutos
    - 45 minutos
    - 1 hora

7. **Equipamentos Disponíveis (Escolha um):** HALTERES e MÁQUINAS

    - Somente peso corporal
    - Halteres
    - Máquinas
    - Todos

**Prompt:**

"Baseado nas seguintes informações: meu biotipo corporal é [biotipo corporal], eu posso treinar [dias disponíveis] dias por semana, prefiro fazer exercícios [tipo de exercício], meu objetivo principal é [objetivo do treino], tenho nível de experiência [nível de experiência], meu tempo disponível por sessão é [tempo disponível] e eu tenho acesso a [equipamentos disponíveis]. Qual seria o plano de treino mais adequado para alcançar meus objetivos?"

# RESPOSTA DA IA RETORNANDO O PLANO COMPLETO DE TREINAMENTO

## Plano de Treinamento Personalizado

**Informações do Usuário:**

- **Biotipo Corporal:** Endomorfo (Tendência a acumular gordura)
- **Dias Disponíveis para Treinar:** 5 dias
- **Tipo de Exercício Preferido:** Maquinário (Uso de máquinas para isolar grupos musculares)
- **Objetivo do Treino:** Ganho de massa muscular
- **Nível de Experiência:** Iniciante
- **Tempo Disponível por Sessão:** 45 minutos
- **Equipamentos Disponíveis:** Halteres e Máquinas

## Plano de Treino Sugerido

Com base nas suas informações, aqui está um plano de treino personalizado para o seu biotipo endomorfo, com o foco em ganho de massa muscular e utilizando máquinas e halteres. O treino é estruturado para 5 dias por semana, com uma duração de 45 minutos por sessão.

**Dia 1 - Peito e Tríceps**

- Supino inclinado na máquina: 4 séries de 10 repetições
- Supino declinado com halteres: 3 séries de 12 repetições
- Tríceps no pulley (máquina): 4 séries de 15 repetições
- Supino fechado com halteres: 3 séries de 12 repetições
- Flexões: 2 séries até a falha

**Dia 2 - Costas e Bíceps**

- **Pulldown na máquina:** 4 séries de 10 repetições
- **Remada na máquina:** 3 séries de 12 repetições
- **Rosca direta com halteres:** 3 séries de 15 repetições
- **Rosca no banco inclinado com halteres:** 3 séries de 12 repetições
- **Remada com halteres:** 3 séries de 12 repetições

**Dia 3 - Pernas**

- **Leg press na máquina:** 4 séries de 12 repetições
- **Agachamento no Smith machine:** 3 séries de 10 repetições
- **Extensão de pernas na máquina:** 4 séries de 12 repetições
- **Flexão de pernas na máquina:** 4 séries de 12 repetições
- **Elevação de panturrilha com halteres:** 4 séries de 15 repetições

**Dia 4 - Ombros e Abdômen**

- **Desenvolvimento com halteres:** 4 séries de 10 repetições
- **Elevação lateral na máquina:** 4 séries de 12 repetições
- **Abdominal na máquina:** 3 séries de 15 repetições
- **Prancha:** 3 séries de 1 minuto
- **Abdominal infra com halteres:** 3 séries de 12 repetições

**Dia 5 - Treino de Corpo Inteiro (Full Body)**

- **Supino reto na máquina:** 4 séries de 10 repetições
- **Pulldown na máquina:** 4 séries de 10 repetições
- **Agachamento no Smith machine:** 4 séries de 10 repetições
- **Desenvolvimento com halteres:** 3 séries de 12 repetições
- **Abdominal na máquina:** 3 séries de 15 repetições

**Dicas Adicionais:**

    1. Aumente a Carga Gradualmente: À medida que se sentir mais confortável com os exercícios, aumente gradualmente a carga dos halteres e as configurações de peso nas máquinas.
    1. Controle da Dieta: Como endomorfo, é importante controlar a ingestão calórica e seguir uma dieta rica em proteínas para apoiar o ganho de massa muscular enquanto evita o acúmulo excessivo de gordura.
    3. Atenção à Postura: Preste atenção à postura em todos os exercícios, especialmente ao usar máquinas, para evitar lesões e maximizar os ganhos musculares.

**Recomendações Finais:**

    1. Consistência e Paciência: Lembre-se de que os resultados vêm com o tempo e a consistência. Siga o plano de treino regularmente, ajustando as cargas de acordo com seu progresso.
    2. Descanso Adequado: O descanso entre os dias de treino é fundamental para a recuperação muscular. Tente manter um intervalo de pelo menos 24 horas entre os treinos para cada grupo muscular.
    3. Nutrição: Combine o treino com uma dieta balanceada, priorizando proteínas, carboidratos complexos e gorduras boas para maximizar o ganho de massa muscular.

**Nota:** Caso sinta desconforto ou dor ao realizar qualquer exercício, é importante consultar um profissional da saúde ou um treinador especializado para ajustar o treino de forma adequada.
Conclusão

Este plano de treino foi elaborado para otimizar o ganho de massa muscular enquanto utiliza as máquinas e halteres disponíveis. Ao seguir o plano com disciplina e combinar com uma alimentação balanceada, você estará no caminho certo para alcançar seus objetivos.

## Resumindo

1. **Você informa o texto do prompt pre-elaborado:** Esse texto contém todas as variáveis fornecidas pelo usuário (biotipo corporal, dias disponíveis, tipo de exercício, etc.). Esse é o momento em que você diz à IA exatamente o que ela precisa para gerar o plano de treino.

2. **A IA processa esse prompt e retorna o plano completo:** Com base nas informações que você passou no prompt, a IA gera o plano de treino personalizado.

Você sempre precisa fornecer esse prompt, que inclui as variáveis do usuário, para que a IA entenda o contexto e devolva uma resposta completa, que pode ser usada como plano de treino.

Assim, sim, o processo é sempre o mesmo:

    - Você dá o prompt pre-elaborado.
    - A IA retorna o plano de treino completo com base nesse prompt.

Depois disso, você pode formatar a resposta, converter em PDF, e enviar ao usuário final.

# RECOMENDAÇÕES

Recomendações para atualização e melhorias no processo de geração e envio de planos de treino personalizados utilizando IA:

1. Automatização do Processo de Geração do Prompt

Atualmente, você precisa montar manualmente o prompt a cada vez que recebe as informações do usuário. Uma melhoria seria automatizar a geração do prompt com base nas respostas dos usuários. Isso pode ser feito criando um formulário ou interface (por exemplo, uma página web) onde o usuário pode selecionar suas opções. O backend geraria automaticamente o prompt baseado nessas respostas, eliminando a necessidade de escrever o prompt manualmente.

2. Integração Direta com a API da IA

Se você está usando o ChatGPT ou outra IA para gerar o plano de treino, considere integrar diretamente com a API do OpenAI ou outra API de IA. Com essa integração, o seu sistema enviaria as informações do usuário automaticamente para a IA, sem que você tenha que fazer isso manualmente. O sistema geraria o prompt e enviaria o resultado de volta ao usuário sem intervenção manual.

3. Melhoria na Personalização do PDF

Atualmente, o PDF é gerado de maneira estática. Você pode melhorar a personalização do documento, incluindo o nome do usuário, data, e talvez até um logo da sua marca ou serviço. Além disso, adicionar gráficos simples sobre o progresso ou estimativas de desempenho futuros pode aumentar o valor percebido pelo usuário.

4. Opções de Feedback Automático

Adicione uma funcionalidade de feedback automático após o envio do plano. Pergunte ao usuário como foi a experiência após algumas semanas de treino e, com base nas respostas, gere uma recomendação de ajustes automáticos. Isso aumenta o engajamento e permite melhorar o plano ao longo do tempo.

5. Versão de Ajuste do Treino

Além do plano de treino original, considere adicionar uma funcionalidade de ajuste dinâmico do treino com base no progresso do usuário. Você pode criar um ciclo onde, após um determinado período, o usuário informa seu progresso, e o sistema automaticamente gera uma versão ajustada do plano de treino (mais avançado, com variações de carga, ou maior intensidade).

6. Opções de Exportação e Envio

Automatize o processo de exportação para PDF e envio do documento. Em vez de gerar manualmente o PDF, implemente uma solução que faça a conversão automaticamente, e também inclua funcionalidades de envio via WhatsApp ou e-mail diretamente pelo sistema, garantindo uma entrega rápida ao usuário.

7. Banco de Dados para Histórico e Análise

Implemente um banco de dados que armazene os planos de treino gerados para cada usuário. Isso permite que você ofereça:

    Planos de continuidade: Criação de novos planos baseados em históricos anteriores.
    Análise de Progresso: Visualize o progresso de cada usuário ao longo do tempo e ajuste os planos de treino automaticamente com base em dados anteriores.

8. Feedback por Inteligência Artificial

Além de gerar planos, use a IA para fornecer feedback inteligente. Ao receber informações sobre como o usuário se sentiu ou progrediu com o plano, o sistema pode sugerir ajustes de forma personalizada, como intensificar a carga, aumentar o tempo de treino ou focar em áreas específicas.

## Material de Apoio

    Documentação da API do OpenAI
    Twilio WhatsApp API
    ReportLab para geração de PDFs
