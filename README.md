---
marp: false
theme: gaia
size: 4:3
/*
 * @auto-scaling true
 */
---

# Definições
-
    Tratamento de erros de forma adequada.
-   
    Garantir que o tratamento de erros não se torne um problema maior que os erros.
-
    Entender que um comportamento mais simples pode ser o mais adequado ao erro ocorrido.
    ![DEF](Inicial.png)
---

# Conceito e Funcionamento
-
    Utilização de caminhos diferentes para o mesmo resultado.
-
    Ampliar as possibilidades de chegar no mesmo resultado para contornar os problemas.
-
    Explorar as opções para ajudar o usuário nos erros que a aplicação pode apresentar.

    ![CON](Conceito.png)
---

# Aplicabilidade
-
    Quando temos um erro e desejamos uma solução que contorne o erro e leve o usuário para a utilização.
-
    Permitir que o usuário tenha a experiência de não saber que houve um erro e que ele chegou na utilização final.
-
    Sair de soluções conhecidas e promover uma nova forma de prevenção de erros.

    ![APLIC](Aplicabilidade.jpg)
---

# Casos de uso
-
    Exemplo onde o fallback poderia ser implementado para encontrarmos um caminho diferente para o tratamento de um erro:

    ![CASO](Imagem%201.png)
-
    Neste caso a inserção do fallback traria a necessidade de implementação de diversos outros tratamentos.
    
---

# Conclusão
-
   Implementar um tratamento de erros mal concebido pode trazer mais problemas do que o erro em si.
-
    Optar pelo caminho mais conhecido não indica ausência de opções de tratamento de erros.
-
    Um tratamento implementado em ambiente de desenvolvimento/testes pode criar problemas no ambiente de produção.
    
    ![CONCL](Conclus%C3%A3o.jpeg)
---