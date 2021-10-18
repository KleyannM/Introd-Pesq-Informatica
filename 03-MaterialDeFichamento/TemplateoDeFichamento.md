# Energy Efficient Computing through Productivity-Aware Frequency Scaling

L. Ponciano, A. Brito, L. Sampaio and F. Brasileiro, "Energy Efficient Computing through Productivity-Aware Frequency Scaling," 2012 Second International Conference on Cloud and Green Computing, 2012, pp. 191-198, doi: 10.1109/CGC.2012.59.

## 1. Fichamento de Conteúdo


O artigo trata da eficiência da computação em relação ao consumo de energia elétrica. É falado sobre os modos comuns de resolver o problema do alto consumo de energia e o porquê
de esses modos não serem tão eficientes, por exemplo o método de reduzir a frequência do processador, o qual apesar de realmente reduzir o consumo de energia, acaba também reduzindo o desempenho do aplicativo. Também é mencionado sobre como as políticas no nível do aplicativo são muito mais eficientes do que as políticas no nivel do Sistema Operacional, enquanto as políticas a nível de tarefa está entre as duas outras. No trabalho relacionado ao artigo, é apresentado o PAFS, uma política DFS não diretamente ligada nem ao apicativo e nem ao SO, nesta política, a frequência do processador é alterada de acordo com uma medida de produtividade. O PAFS funciona diminuindo aos poucos a frequência do clock do processador até ocorrer algum erro no desempenho, a partir desde ponto a frequência volta a subir até que o erro esteja resolvido de forma satisfatória. Para as pesquisas, o PAFS foi comparado com outras medidas de controle da economia de energia e desempenho. Os resultados mostram que o PAFS obtém uma economia de energia superior aos métodos comuns de realizar essa tarefa, isso sem perder produtividade.

## 2. Fichamento Bibliográfico 



* _CPU Clock Frequency_ (frequência do clock da CPU) é a velocidade na qual o processador trabalha (página 1).
* _Productivity_ (produtividade) é o desempenho da CPU ao realizar suas tarefas (página 1).
* _Policy for dynamic frequency scaling_ (política para escala de frequência dinâmica) São políticas estabelecidas para determinar como o sistema opera para reduzir o uso de energia elétrica e manter um bom desempenho (página 1).

## 3. Fichamento de Citações 


* _"Reducing processor frequency may reduce power consumption, as the lower the processor frequency the lower its power consumption [3]. On the other hand, except in very specific cases (e.g., due to contention issues, as we show later), reducing processor frequency will cause a negative impact on applications’ performance."_
* _"Application-level policies define DFS at application design time. This approach allows optimizing both processor power consumption and application performance"_
* _"the main contribution of PAFS is to empower users to dynamically control power consumption based on application’s productivity needs"_
* _"In this work we propose productivity-aware dynamic frequency scaling (PAFS), which is a DFS policy decoupled from both the application and the operating system. It changes processor frequency based on a productivity metric, which consists on one or a combination of several performance metrics"_
