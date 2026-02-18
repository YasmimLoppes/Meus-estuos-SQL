ORDER BY nota DESC;
# 📊 Meus Estudos de SQL

Repositório dedicado a registrar minha evolução, desafios práticos e correções de bugs durante meus estudos de SQL para Engenharia de Dados.

## 🛠️ Correção de Sintaxe: Operadores de Comparação
Neste pequeno exercício prático, identifiquei e corrigi um erro comum de sintaxe que pode travar consultas importantes.

*O Desafio:*
O erro aconteceu ao tentar usar o operador de comparação "maior ou igual". No SQL, a ordem correta é >= e não =>.

*Código Corrigido:*
```sql
SELECT nome_aluno, nota
FROM portal_da_faculdade
WHERE nota >= 7
ORDER BY nota DESC;
