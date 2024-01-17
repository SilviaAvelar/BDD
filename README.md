.... Exercício escrito em Gherkin ...

Gherkin é uma linguagem usada para descrever o comportamento de um sistema de forma estruturada e legível. Ele é frequentemente usado em conjunto com o Behavior Driven Development (BDD) e estruturas de teste como o Cucumber. Os cenários Gherkin são escritos em um formato que é fácil de entender para as partes interessadas técnicas e não técnicas, e podem ser usados para especificar o comportamento esperado de um sistema de forma clara e concisa.

Os cenários de Gherkin consistem em uma série de etapas, cada uma das quais é precedida por uma palavra-chave como "Given", "When" ou "Then". Essas palavras-chave indicam o papel da etapa no cenário, com as etapas "Given" descrevendo o contexto inicial, as etapas "When" representando a ação ou evento que está sendo testado e as etapas "Then" especificando o resultado esperado.

Aqui está um exemplo de um cenário simples de Gherkin:
Feature: Login
    Scenario: Successful login
    Given I am on the login page
    When I enter a valid username and password
    And I click the login button
    Then I should be logged in and see the dashboard

Nesse cenário, a etapa "Fornecido" define o contexto inicial indicando que o usuário está na página de logon. A etapa "Quando" descreve a ação que está sendo executada, que é inserir um nome de usuário e senha válidos e clicar no botão de login. A etapa "Então" especifica o resultado esperado, que é que o usuário deve estar conectado e ver o painel.

Os cenários de Gherkin podem ser usados para especificar o comportamento de um sistema em um alto nível e podem ser usados para impulsionar o desenvolvimento de testes automatizados. Ao escrever cenários em um formato claro e conciso, é mais fácil garantir que todos os envolvidos no processo de desenvolvimento entendam o comportamento esperado do sistema e possam trabalhar juntos para construir um produto de alta qualidade.
