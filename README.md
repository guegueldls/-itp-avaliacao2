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

```bash
gcc Avaliacaoitp2.c -o programa
./programa
