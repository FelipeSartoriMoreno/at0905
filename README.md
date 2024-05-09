# at0905
1. Comparando Datas
Funcionalidade:
Esta função compara duas datas inseridas pelo usuário e exibe qual delas é maior, menor ou se são iguais.

Detalhes da Implementação:
Obtenção dos Valores das Datas: Utiliza o método getElementById() para acessar os elementos HTML que contêm as datas inseridas pelo usuário.
Conversão em Objetos Date: Os valores das datas são convertidos em objetos Date para possibilitar a comparação.
Comparação das Datas: Usa operadores de comparação (>, <, ===) para comparar as datas e determinar a relação entre elas.
Geração da Mensagem: Com base no resultado da comparação, gera uma mensagem indicando qual data é maior, menor ou se são iguais.
Exibição na Página: A mensagem gerada é exibida na página dentro de um elemento <p>

2. Calculando Intervalo entre Datas
Funcionalidade:
Esta função calcula o intervalo em dias entre duas datas inseridas pelo usuário

Detalhes da Implementação:
Obtenção dos Valores das Datas: Usa getElementById() para acessar os elementos HTML que contêm as datas inseridas pelo usuário.
Conversão em Objetos Date: Os valores das datas são convertidos em objetos Date.
Validação das Datas: Verifica se a primeira data é anterior à segunda para garantir que o cálculo seja válido.
Cálculo do Intervalo em Milissegundos: Calcula a diferença absoluta em milissegundos entre as duas datas.
Conversão para Dias: Converte a diferença em milissegundos para dias.
Exibição na Página: O intervalo em dias é exibido na página dentro de um elemento <p>.
3. Exibindo Data Atual
Funcionalidade:
Esta função retorna a data e hora atuais no formato específico hora:minuto - dia/mês/ano.

Detalhes da Implementação:
Criação do Objeto Date: Utiliza o construtor Date() para criar um objeto contendo a data e hora atuais.
Extração dos Componentes da Data e Hora: Extrai a hora, minuto, dia, mês e ano do objeto Date.
Formatação da Data e Hora: Formata esses componentes em uma string seguindo o formato desejado.
Exibição na Página: A string formatada é exibida na página dentro de um elemento <p>.
