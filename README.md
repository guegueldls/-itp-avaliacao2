# -itp-avaliacao2
# Sistema de Gestão de Alunos e Notas em C

## Identificação
- Nome: Miguel Nascimento Francelino
- Opção de Projeto: 1. Boletim de uma pequena turma

## Descrição
O programa gerencia dados acadêmicos de até 10 alunos. Ele utiliza matrizes estáticas para armazenar os nomes e as 3 notas de cada aluno, e alocação dinâmica (`malloc`) para gerenciar o vetor de médias. Suas principais funcionalidades incluem:
- Cálculo individual de médias (evitando perdas de precisão com divisão por ponto flutuante).
- Verificação de status acadêmico ("Atingiu a meta" vs. "Não atingiu a meta").
- Cálculo da média geral da turma e identificação da maior média.
- Validação rigorosa de limites (quantidade de alunos entre 1 e 10, e notas entre 0.0 e 10.0).

## Compilação e Execução
No terminal (utilizando GCC), execute os seguintes comandos:

## Testes
Teste 1(Erro)
Quantos alunos ha na sala (1 a 10)?
15
Erro! Somente uma quantidade de alunos entre 1 e 10.

Teste 2(Certo)
Quantos alunos ha na sala (1 a 10)?
2
Quais seus nomes?
Miguel Lucas
Quais foram suas notas (intervalo de 0.0 a 10.0)?
5 7 8.5
8 7.5 9.3

--- Relat├│rio Individual dos Alunos ---
Aluno: Miguel
Notas: 5.0, 7.0, 8.5
Media: 6.8
Situa├º├úo: Atingiu a meta

Aluno: Lucas
Notas: 8.0, 7.5, 9.3
Media: 8.3
Situa├º├úo: Atingiu a meta

--- Estat├¡sticas Gerais ---
M├®dia geral da turma: 7.6
Maior m├®dia da turma: 8.3

Pressione Enter para sair...

## Link do Youtube
https://youtu.be/QkN973Gwcdk?si=AzcyosGB0xHorc0-

```bash
gcc Avaliacaoitp2.c -o programa
./programa

