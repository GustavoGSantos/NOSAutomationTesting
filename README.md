# NOSAutomationTesting

## 1. Escolher uma ferramenta para automatizar testes à seguinte Api REST, explica o porquê dessa escolha. https://gorest.co.in/
A Ferramenta escolhida foi o Postman, devido a interface amigável, templates básicos de teste prontos, criação de pré scripts para testes quando necessário, criação de coleções e váriáveis globais e de ambiente com fácil reutilização.

## 2. Explica os use case de teste;
Os casos de uso desses testes são validar a criação de usuário, validar atualização de dados do usuário, deletar usuário e consultar usuários criados.

## 3. Em automação, com resposta desta API gorest.co.in/public/v2/todos 
### 3.1. Aplica uma validação de schema ao resultado;
### 3.2. Valida se todos os resultados têm status completed;
### 3.3. Interpreta e valida o valor “due_on”
O ponto 3.3 não ficou muito claro para mim.

# DevOps, CI/CD:
## 4.1. Explica e justifica uma implementação de testes de carga a esta API;
Os testes de carga são necessários para avaliar o comportamento da API em diferentes condições, por exemplo, um acesso simultaneo de vários usuários para avaliar o desempenho da api, taxa de erros e possíveis melhorias de infraestrutura.

## 4.2. Como implementarias uma solução de Continuous Testing, justifica;
Uma integração com a pipeline para execução de testes a cada criação de merge request acredito que seria uma boa solução para continuous testing.