# Sistema de Gestão das Olimpíadas (SGO)

## Descrição do Projeto

O Sistema de Gestão das Olimpíadas (SGO) é uma aplicação destinada a gerenciar todos os aspectos das Olimpíadas, incluindo o cadastro de competições, inscrição de atletas, alocação de locais para provas, controle de resultados e geração de relatórios de medalhas. Este sistema visa garantir a coordenação eficiente dos eventos e a integração das diferentes partes envolvidas.

## Regras de Negócio

1. **Cadastro de Competições**
   - O sistema deve permitir o cadastro de competições com detalhes como nome da modalidade, data, horário, local e lista de atletas inscritos.

2. **Inscrição de Atletas**
   - Atletas de diferentes países podem se inscrever em competições específicas. Cada atleta pode participar de várias competições, mas só pode representar um país por modalidade.

3. **Alocação de Locais**
   - Os locais para as competições devem ser alocados para evitar conflitos de horário. Um local só pode abrigar uma competição por vez.

4. **Controle de Resultados**
   - Após as competições, os resultados devem ser registrados, determinando o atleta vencedor e os classificados em segundo e terceiro lugares.

5. **Relatórios de Medalhas**
   - O sistema deve gerar relatórios de medalhas, mostrando o desempenho de cada país com base nas medalhas conquistadas (ouro, prata e bronze).

## Histórias de Usuário

- **US01 - Cadastrar Competição**: Como administrador, quero cadastrar competições para que eu possa gerenciar os eventos das Olimpíadas.
- **US02 - Inscrever Atleta**: Como atleta, quero me inscrever em competições para participar dos eventos.
- **US03 - Alocar Local**: Como coordenador, quero alocar locais para as competições para evitar conflitos de horário.
- **US04 - Registrar Resultados**: Como juiz, quero registrar os resultados das competições para determinar os vencedores.
- **US05 - Gerar Relatórios de Medalhas**: Como analista, quero gerar relatórios de medalhas para avaliar o desempenho dos países.
- **US06 - Editar Competição**: Como administrador, quero poder editar as informações de uma competição já cadastrada para corrigir erros ou atualizar detalhes como data, horário ou local.
- **US07 - Cancelar Inscrição de Atleta**: Como atleta, quero poder cancelar minha inscrição em uma competição caso não possa participar, para que minha vaga possa ser disponibilizada para outro atleta.
- **US08 - Atualizar Resultados**: Como juiz, quero poder atualizar os resultados das competições se houver algum erro na entrada dos dados ou alterações nos resultados, para garantir que as informações estejam corretas.
- **US09 - Visualizar Relatório de Medalhas por País**: Como gestor, quero visualizar um relatório detalhado das medalhas conquistadas por cada país para analisar o desempenho geral e tomar decisões estratégicas para futuras competições.

## Diagramas

### Diagrama de Caso de Uso
![Diagrama de Caso de Uso](imagens/diagrama-de-caso-de-uso.png)
- **Casos de Uso Principais:** Cadastrar Competição, Inscrever Atleta, Alocar Local, Registrar Resultados.

### Diagrama de Classes
![Diagrama de Classes](imagens/diagrama-de-classes.png)
- **Classes Principais:** Competição, Atleta, Local, Resultado, País.

### Diagrama de Pacotes
![Diagrama de Pacotes](imagens/diagrama-de-pacotes.png)
- **Pacotes:** Pacote de Inscrições, Pacote de Alocação, Pacote de Relatórios, etc.

### Diagrama de Componentes
![Diagrama de Componentes](imagens/diagrama-de-componentes.png)
- **Componentes:** Interface de Usuário, Módulo de Inscrições, Módulo de Alocação, Módulo de Relatórios.

### Diagrama de Implantação
![Diagrama de Implantação](imagens/diagrama-de-implantacao.png)
- **Arquitetura Física:** Servidores, Bancos de Dados, Dispositivos dos Usuários.


