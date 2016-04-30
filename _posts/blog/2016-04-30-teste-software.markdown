---
layout: post
title:  "13 Tipos de Testes de Software"
date:   2016-04-30
author: Tonia Dias
categories: 
- blog
- teste
- software
- tipos
img: 20160430.png
thumb: thumb-sustentabilidade.png
comments: true
---

O processo de engenharia de um software produzido é estruturado em diversas fases, porém uma atividade fundamental é ter os testes que serão realizados bem detalhados e que cubram grande parte das funcionalidades da solução desenvolvida. Existe porém diversos tipos de testes que podem ser aplicados a cada fase do ciclo produtivo<!--more-->, sendo estas:

+ TESTE DE CONFIGURAÇÃO: é o tipo de teste que valida se o software desenvolvido é executado no hardware especificado para execução do sistema.

+ TESTE DE INSTALAÇÃO: verifica todo o processo de instalação do software em diferentes ambientes suportados e diferentes condições de máquina (com baixa memória, problemas de rede, interrupção na instalação,..., dentre outros).

+ TESTE DE INTEGRIDADE: valida a robustez do sistema perante as falhas. Neste tipo de testes o sistema é submetido a situações que podem causar falha no sistema, como por exemplo queda de banco de dados ou quedas de energia.

+ TESTE DE SEGURANÇA: um dos principais pontos a serem avaliados em uma solução é a sua segurança referente aos dados trabalhados pelo sistema. São validados neste teste se os acessos ao sistema são realizados de forma segura e se as informações manipuladas não são facilmente extraídas do sistema sem autorização.

+ TESTE FUNCIONAL: este é o teste mais realizado atualmente nas empresas, pois valida se a aplicação está fazendo tudo que deveria fazer, se todos os requisitos solicitados pelo cliente foram atendidos e se cumpre as regras de negócio estabelecidas.

+ TESTE DE UNIDADE: é a realização de testes em um componente ou classe do sistema de forma isolada, sem considerar suas relações com os demais componentes da solução.

+ TESTE DE INTEGRAÇÃO: para este tipo de teste é feita a validação das integrações, internas ou externas, do sistema. São validadas as comunicações e troca de informações entre componentes e serviços.

+ TESTE DE VOLUME: em sistemas que utilizam banco de dados, é importante testar se o volume de informações trafegadas pode afetar diretamente o banco. Este teste realiza esta validação de volumetria considerando o tráfego normal de dados entre a aplicação e o banco de dados.

+ TESTE DE PERFORMANCE: realiza a validação da performance do sistema, e pode se dividir em três tipos.

  > TESTE DE CARGA: testa o software sob condições normais de uso avaliando o tempo de resposta, número de transações por minuto, usuários simultâneos, ...

  > TESTE DE STRESS: o sistema é avaliado sob situação de stress e picos excessivos de uso.

  > TESTE DE ESTABILIDADE: valida se o sistema se mantém funcional de maneira satisfatória após um período de utilização.

+ TESTE DE USABILIDADE: tipo de teste mais focado na experiência do usuário na utilização da solução, validando a facilidade de uso, o entendimento e organização do layout, acesso a funcionalidades.

+ TESTE DE CAIXA BRANCA E CAIXA PRETA: os testes de caixa branca são realizados testes considerando o código do sistema e sua arquitetura interna avaliando possíveis falhas arquiteturais da solução. Já no teste de caixa preta são avaliados os fatores externos a codificação, como interfaces com outros sistemas e layouts de tela.

+ TESTE DE REGRESSÃO: são os testes de um componente ou de todo o sistema para identificar se uma melhoria ou correção gerou alguma falha.

+ TESTE DE MANUTENÇÃO: são os testes que avaliam se mudanças no ambiente operacional afetaram diretamente o funcionamento da solução.

É muito difícil em um ambiente corporativo aplicar todas estas abordagens de teste. Geralmente só se aplica as abordagens que garantem a qualidade da implantação e funcionamento do sistema. Porém é bom ter sempre em mente que quanto maior for o tipo de testes aplicados, maior será a cobertura e garantia da qualidade da solução criada.

E você quantos testes aplica em seu ambiente de desenvolvimento de soluções ? Deixe seus comentários sobre o artigo.