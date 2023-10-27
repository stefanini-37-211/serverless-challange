# Serverless Challenge

# Antes de começar....

- [Keep it simple](https://pt.wikipedia.org/wiki/Princ%C3%ADpio_KISS), entendemos que você possui suas prioridades e nossa proposta com esse desafio é ter uma idéia geral de como você faz seus códigos, toma suas decisões arquiteturais e o seu conhecimento geral sobre os assuntos abordados. 🧙‍♂️
- Foque no essencial, mas lembre-se também que quanto mais itens você atender mais se destacará perante a concorrência. 💪

# Primeira parte - Backend

O desafio que propomos é provisionar uma infraestrutura na AWS, em que se tenha uma lambda que seja capaz de registrar em um banco de dados relacional ou não relacional, dados sobre funcionários de uma empresa e o frontend CRUD dessa API caso a vaga tenho como requisito frontend.

## Requisitos
 1. Utilizar Clean Architectute 🧓 <br/>
 2. Seu desafio precisa estar versionado no Github, em um repositório público. <br/>
 3. Documentação é primordial e vamos nos guiar por ela para instalar e rodar o projeto, incluindo testes unitários. <br/>
 4. Um funcionário deve possuir como atributos : Id , Idade , Nome e Cargo.<br/>
 5. Salvar as informações necessárias em um banco de dados relacional ou não relacional de sua escolha dentro de uma infraestrutura AWS<br/>
 6. Será necessário que a Lambda consiga consultar, deletar e atualizar um funcionário e que ele esteja acessível via internet.<br/>
 7. Os recursos podem ser provisionados por serverless framework ou terraform.<br/>
 8. Realizar testes unitários com JEST de preferência ou outra ferramenta. 🧪<br/>

## ⭐Pontos extras se você:
- Criar testes unitários
- Usar clean Architecture
- Utilizar injeção de dependências
- Utilizar conventional commits https://www.conventionalcommits.org/en/v1.0.0/

# Segunda parte - Frontend (se a sua vaga pede)

Aqui você precisa criar uma interface CRUD que consuma a API criada anteriormente utilizando de PREFERÊNCIA o framework solicitado na descrição da vaga que você recebeu.
Caso haja complicações ao conectar com a API, pode usar dados mockados mesmo.

## ⭐Pontos extras se você:
- Consumir a API
- Criar testes unitários
- Der atenção ao gerenciamento de Memória: Preste atenção especial ao desempenho e evite vazamentos de memória.
- Der atenção à responsividade: O aplicativo deve ser responsivo e funcionar corretamente em diferentes tamanhos de tela e orientações.
- Utilizar algum padrão de nomenclatura de Arquivos
- Tiver cuidado quanto à estrutura de Diretórios
- Tiver cuidado quanto à responsabilidade de cada componente

# Observações 🔍
- Não tem problema se você não conseguir finalizar tudo! Não deixe de enviar seu desafio por isso!
- Sinta-se livre para explicar como você atendeu aos itens no README do projeto.

# Cuidados ⚠️
- Não há necessidade de deixar as lambdas criadas na AWS, caso queira, pode evidenciar o funcionamento das mesmas com capturas e subir junto no projeto
- Não deixe suas chaves ou URLs expostas no projeto
