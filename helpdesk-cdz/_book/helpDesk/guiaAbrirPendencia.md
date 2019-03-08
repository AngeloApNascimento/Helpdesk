# Guia Abrir / Analisar Pendência

#### Objetivo
Este documento tem como objetivo descrever o processo de abertura e acompanhamento de pendências relacionadas aos Sistemas Sonner.

#### Responsável
Usuário do Sistema / Analista de Suporte

## Tarefas/Atividades
#### Abrir pendência.
Para abrir uma pendência deve ser informado os seguintes campos:
* Tipo de Pendência:
    - Sistema: Pendências que tem origem no uso do sistema e suas funcionalidades;
    - Técnica:
* Usuário: Deverá ser informado o usuário solicitante da pendência;
* Tipo de Problema:
    - Erro de Sistema: Um problema que prejudica a execução de uma operação ou funcionamento do sistema;
    - Melhoria: Uma melhoria ou aprimoramento de um recurso ou funcionalidade existente;
    - Melhoria Futura: Uma melhoria ou aprimoramento de um recurso ou funcionalidade existente;
    - Nova Funcionalidade: Uma nova funcionalidade ou característica que ainda não foi desenvolvida;
    - Procedimento Operacional: Um problema derivado ou que pode ser resolvido através de procedimento operacional;
* Formulário: Deverá ser informado o menu no sistema de origem da pendência;
* Prioridade:
    - Bloqueio: Impede o andamento do trabalho ou uso de uma funcionalidade;
    - Crítico: Não impede o andamento do trabalho ou uso de uma funcionalidade, mas tem alto impacto no resultado;
    - Normal: Não impede o andamento do trabalho ou uso de uma funcionalidade, mas tem baixo impacto no resultado;
    - Baixa: Não impede o andamento do trabalho e a solução é conhecida;
    - Trivial: Não impede o andamento do trabalho;
* Resumo: Descreva a pendência de forma resumida e que faça sentido;
* Descrição: Descreva a pendência de forma que quem venha a ler não fiquem com dúvidas do que se trata;
* Anexos: Anexe qualquer evidência necessária para o entendimento da pendência. Ex: Print, Documentos, Planilhas, etc.;

#### Tipo de Problema: Erro de Sistema.
Quando o tipo de problema for “Erro de Sistema” o campo descrição da pendência deverá conter pelo menos as seguintes informações:
* Módulo: Informar qual módulo do sistema está com erro Ex: Ouvidoria que pertence ao sistema de PDF - Protocolo Documentos e Fluxos
* Versão atual do Sistema: A versão atual de sistema em produção
* Menu: Descrever o menu para simulação Ex: Ouvidoria / Relatórios da Ouvidoria – Atendimento

A descrição deverá conter todos os procedimentos realizados no sistema e todos os campos utilizados, filtros, relatórios, datas / período Ex: dd/mm/aaaa até dd/mm/aaaa, logs de erros e descrever todo o cenário de teste utilizado para simular o erro.

Deverá também ser gerado um backup full da base do cliente, sem os arquivos de log e sem os arquivos digitais. Consultar guia “Gerar Backup Sonner”.

#### Tipo de Problema: Melhoria / Melhoria Futura / Nova Funcionalidade.
Consultar guia “Especificar Requisitos”.

#### Tipo de Problema: Procedimento Operacional.
Quando o tipo de problema for “Procedimento Operacional” o analista de suporte deverá descrever o passo a passo de como resolver o procedimento no sistema e enviar a pendência para responsabilidade do solicitante.

#### Envio de Pendência para o Suporte Técnico.
Após documentação da pendência de acordo com o tipo de problema, a pendência deverá ser enviada para o suporte técnico.

Para realizar o envio clique com o botão direito sobre a pendência e selecione a opção **“Enviar pendência para o Suporte Técnico”**.

Nesse momento será automaticamente criado um Jira para ánalise da equipe de desenvolvimento sonner.

#### Referências
Sistema de Suporte Sonner.