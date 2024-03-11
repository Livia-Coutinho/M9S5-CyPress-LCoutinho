# Atividade - Utilizando o cypress
## Semana 5 - Módulo 9 - Programação
### Livia Coutinho - Turma 3 - Engenharia de Software
<br>
<br>
<br>

## 1. O que é o Cypress e para que serve?

O Cypress é uma ferramenta de teste de frontend de código aberto, que é usada principalmente para testar aplicativos da web modernos. Ele oferece uma abordagem completa para testar aplicativos da web, incluindo automação de testes, gravação de vídeos e capturas de tela, depuração, entre outros recursos. O Cypress é conhecido por sua facilidade de uso e pela capacidade de escrever testes eficazes de forma rápida e simples.

## 2. Vantagens e desvantagens do Cypress em relação a outras ferramentas de teste.

Vantagens:
- Interface amigável e fácil de usar, permitindo que até mesmo iniciantes escrevam testes rapidamente.
- Integração contínua e contínua (CI/CD) perfeita com várias plataformas.
- Capacidade de executar testes diretamente no navegador, proporcionando um ambiente realista.
- Grande variedade de comandos e asserções que facilitam a escrita de testes robustos.
- Capacidade de depuração fácil com a ajuda de uma interface gráfica interativa.

Desvantagens:
- Suporte limitado para aplicativos móveis, pois é focado principalmente em testes de aplicativos da web.
- Pode ser necessário algum esforço para configurar e personalizar o ambiente de teste.
- Nem todos os navegadores são suportados igualmente, o que pode limitar a cobertura de teste.

## 3. Arquitetura do Cypress.

O Cypress segue uma arquitetura client-server, onde o código de teste é executado no navegador e se comunica com o servidor Cypress. Ele consiste em três principais componentes:

- Test Runner: A interface gráfica que permite escrever, organizar e visualizar testes, bem como executá-los e depurá-los.
- Drivers: Os drivers são responsáveis por controlar o navegador e executar os comandos do teste. No Cypress, o driver Cypress é integrado ao navegador, o que proporciona um controle mais direto e eficiente.
- Servidor: O servidor Cypress é responsável por iniciar e encerrar o processo do navegador, bem como por coordenar a comunicação entre o Test Runner e o Driver.

## 4. Seletores de elementos no Cypress.
No Cypress, os seletores de elementos funcionam de maneira semelhante ao CSS ou jQuery, permitindo selecionar elementos com base em seus atributos, classes, IDs, etc. Alguns exemplos de seletores comuns incluem:

- cy.get('selector'): Seleciona um elemento usando um seletor CSS.
- cy.contains('text'): Seleciona um elemento que contém o texto especificado.
- cy.get('[attribute="value"]'): Seleciona um elemento com um atributo específico e valor.

## 5. Comandos e asserções no Cypress.
O Cypress fornece uma ampla gama de comandos e asserções para interagir com elementos da página e verificar seu estado. Alguns exemplos incluem:

- Comandos:
    - cy.visit(): Visita uma página específica.
    - cy.get(): Seleciona um elemento na página.
    - cy.click(): Simula um clique em um elemento.

- Asserções:
    - cy.contains(): Verifica se um elemento contém o texto especificado.
    - should('be.visible'): Verifica se um elemento está visível na página.
    - should('have.class'): Verifica se um elemento possui a classe especificada.

## 6. Descrição das etapas de preparação de um testes de interface, execução e verificação no Cypress.

Preparação do teste:

1. Escrever um script de teste utilizando o editor de código ou o Test Runner do Cypress.
2. Definir os passos do teste, como visitar uma URL, interagir com elementos da página e verificar o estado esperado.
3. Organizar o código de teste em suites e casos de teste para melhor gerenciamento.

Execução do teste:

1. Iniciar o servidor Cypress.
2. Selecionar e executar os testes desejados no Test Runner.
3. Observar a execução dos testes em tempo real e monitorar eventuais falhas.

Verificação do teste:

1. Revisar os resultados dos testes, incluindo possíveis falhas e erros.
2. Analisar os logs e capturas de tela gerados durante a execução dos testes.
3. Corrigir quaisquer problemas identificados e iterar no processo de desenvolvimento e teste conforme necessário.

## 7. Como estruturar testes de forma eficiente no Cypress?

Algumas práticas recomendadas para estruturar testes de forma eficiente no Cypress incluem:

- Organizar os testes em suites e casos de teste lógicos para facilitar o gerenciamento e a execução.
- Reutilizar código sempre que possível, evitando duplicações e mantendo os testes mais concisos e legíveis.
- Dividir os testes em cenários independentes e isolados para garantir que possam ser executados de forma independente e em qualquer ordem.
- Utilizar variáveis e configurações para parametrizar os testes e facilitar a execução de testes em diferentes ambientes.
- Incorporar as melhores práticas de desenvolvimento de software, como testes de unidade, integração e end-to-end, para obter uma cobertura abrangente e confiável.