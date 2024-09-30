# Dia 5: Fundamentos do Teste de Software (Back-End)

## Tarefas do Dia
- [x] **Fundamentos do Teste de Software (Back-End)**
- [x] **A Pirâmide de Testes**
- [x] **Aprofundamento na Pirâmide de Testes**

## Reuniões
- [x] **Daily às 14h20**

## Resumo

- [A Pirâmide de Testes (Medium)](https://medium.com/creditas-tech/a-pirâmide-de-testes-a0faec465cc2)
- [The Practical Test Pyramid (Martin Fowler)](https://martinfowler.com/articles/practical-test-pyramid.html)

### Importância da Pirâmide de Testes
A **pirâmide de testes** é essencial para otimizar o processo de desenvolvimento de software, garantindo uma estrutura eficiente de testes. Seu principal objetivo é assegurar que a maior parte dos testes seja rápida e de fácil execução (como os testes de unidade), permitindo a detecção de falhas de forma ágil. Ao manter um número limitado de testes de ponta a ponta, que são mais complexos e demorados, a pirâmide contribui para a eficiência do ciclo de desenvolvimento e a qualidade do software.

### A Pirâmide de Testes

A pirâmide de testes fornece uma diretriz sobre a quantidade e tipo de testes em cada nível da aplicação. Ela equilibra cobertura de testes e eficiência para garantir uma abordagem mais produtiva.

1. **Testes de Ponta a Ponta (e2e)**:
   - Simulam o comportamento do usuário, cobrindo os principais fluxos da aplicação.
   - São mais complexos e demorados, e por isso devem ser utilizados com moderação.

2. **Testes de Unidade**:
   - Focados em pequenas partes do código, são rápidos, independentes e eficientes.
   - Ideais para validar funcionalidades específicas de maneira ágil e com feedback imediato.

3. **Testes de Integração**:
   - Verificam a interação entre diferentes unidades do sistema.
   - Têm uma complexidade intermediária e são importantes para garantir que as partes do sistema funcionem corretamente em conjunto.


## Curiosidades

- **Origem do Termo**: O conceito da pirâmide de testes foi popularizado por Mike Cohn em seu livro *"Succeeding with Agile"*.
- **Ênfase na Velocidade**: Testes de unidade são projetados para serem rápidos e fornecerem feedback quase imediato, sendo cruciais para ciclos de desenvolvimento rápidos.
- **Custo de Manutenção**: Testes de ponta a ponta costumam ser mais caros e complexos de manter, devido à necessidade de ambientes mais elaborados.
- **Influência no Design**: Testes de unidade podem ajudar a guiar o design do código, promovendo simplicidade e coesão, além de facilitar a manutenção e evolução do software.