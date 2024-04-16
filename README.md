# INNER_JOIN_SQL

<PRE>

  SELECT P.NOME AS ALUNO, C.NOME AS CARRO, C.COR, 
C.ANO, COMB.DESCRIÇÃO
FROM PESSOAS P
INNER JOIN CARROS C 
ON P.CODCARRO = C.CÓDIGO
INNER JOIN COMBUSTÍVEL COMB 
ON C.CODCOMBUSTÍVEL = COMB.CÓDIGO
WHERE P.NOME = "Hugo";

  
</PRE>
