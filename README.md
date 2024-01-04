# isabella

1- Abstração para filtrar o que é relevante, Reconhecimento de padrão para consegir identificar padrões que se repetem em um meio, Decomposição para dividir um grande problema em problemas menores fazendo com que eles sejam mais fáceis de se resolver, Algoritmo são uteis como em uma receita de bolo para seguir o passo a passo para a resolição de um problema

2- Segundo as regras da modelagem a gente consegue manter mais consistência nos dados e mais eficiência no seu banco, faz com que você não tenha um banco sobrecarregado de informações repetidas e irrelevantes

3- anexo fluxograma

4- Acho que não precisa de um endereço para o empreendimento e outro para o edifício por que eles tem o mesmo endereço, a diferença é que por exemplo como o empreendimento tem vários edifícios os edifícios serão blocos diferentes.
-Eu colocaria o varchar do nome da tabela TipoContato menor, o nome da tabela CargoFuncionario também.
-Eu mudaria tamanho do varchar do Logradouro, cidade e uf, se estamos tratando de Brasil eles poderiam ser menores.
-O varchar do logradouro do EnderecoDono está escrito errado
-Provavelmente o IdTipo da tabela Unidade deveria ser IdEdificio
-A biometria deveria ser uma entidade ligada aos moradores e ao edifício no qual ele mora e os moradores derevão ter outra maneira de acesso como uma senha para caso a biometria não funcione 
-Estão faltando os namutes