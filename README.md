# OBI Soluções Colaborativas
Este repositório público foi criado para que os estudantes do 1º semestre dos cursos de tecnologia que irão participar da Olimpíada Brasileira de Informática (OBI) possam compartilhar suas soluções para as questões de anos anteriores. O objetivo é incentivar o estudo de lógica, algoritmos e a prática colaborativa.

## Como contribuir?

Para enviar a sua solução, siga o fluxo padrão do GitHub:

# Opção A: Utilizando o Git Bash / Terminal

1. Faça um **Fork** deste repositório.
   
   <img width="1366" height="768" alt="fork copia" src="https://github.com/user-attachments/assets/b046d6cb-51f7-48de-b327-b14bd71a64ca" />

   <img width="1366" height="768" alt="fork copia 2" src="https://github.com/user-attachments/assets/604779ff-22de-4b19-8ad4-52178caf672b" />

2. Navegue até o diretirio onde estão seus repositorios (ex: `C:\Users\Seu-Usuario\Documents\GitHub`). Clone o seu fork localmente: `git clone https://github.com/SEU-USUARIO/nome-do-repositorio.git`
3. Acesse a pasta criada e crie uma branch para a sua questão: `git checkout -b solucao-nome-da-questao`
6. Adicione o seu código na pasta correspondente (ex: `Nivel_Universitario/Fase_1/Nome_da_Questao/solucao_seu_nome.c`).
7. Faça o commit e o push:
   `git add .`
   `git commit -m "Solução: Nome da Questão (Ano - Fase)"`
   `git push origin solucao-nome-da-questao`
9. Abra um **Pull Request** para o repositório principal.

   <img width="1366" height="768" alt="pull request 1" src="https://github.com/user-attachments/assets/d8bab572-cc93-4c40-b528-cd2d28951d5c" />

   <img width="1366" height="768" alt="pull request 2" src="https://github.com/user-attachments/assets/e9a77755-90a6-47b9-b64b-cf87088d0920" />

## Estrutura do Repositório

Para masnter a organização, tente seguir esta estrutura de pastas:

```text
/
└── 2025
    └── Nível (Ex: Nível_Universitario)
       └── Fase (Ex: Fase_1, Fase_2)
          └── Nome_da_Questao
             ├── solucao_wictor.py
             └── solucao_vicente.c   
             
```

## Regras de Convivência
  * Respeite o código do colega. Comentários construtios são sempre bem-vindos!
  * Procure seguir as boas práticas: idente seu código, use nomes de variáveis que façam sentido com o contexto e sempre adicione comentários explicando a lógica que você utilizou para chegar ao resultado.
