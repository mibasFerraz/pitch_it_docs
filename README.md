# Repositório de documentação do Pitch It!

Aqui está toda a documentação realizada do projeto Pitch It! ao longo da disciplina de EPS 2024-1 com o professor Dr. Ricardo Matos Chaim.

## Equipe
| Nome | Github | email |
|------|--------|-------|
| Lucas Lima Ferraz | mibasFerraz | lucasllff@gmail.com |

## Localhost 
Para rodar localmente utilizar o comando `python3 -m http.server`

## Back-End
O gerador de pitch e o chatbot deixei atrelado diretamente ao front para facilitar modificações futuras (é necessário criar uma conta no ChatGPT e gerar um token para utilização). 
O Crud de usuário não foi desenvolvido, foi consumido de outro grupo (obrigatório pela matéria). Deixei o front da aplicação de maneira bem "dummy" pra só rodar o front e entender como tudo está funcionando de forma prática.

## Qualidade
Para rodar os testes basta usar o comando `npm test`. Foram atrelados ao SonarCloud, e por o front ser criado com vite, tem que realizar uma configuração extra para o SonarCloud pegar a cobertura de teste.
