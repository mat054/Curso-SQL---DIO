# Curso-SQL---DIO

No modelo de ordem de serviço de uma oficina foram criadas as seguintes entidades, peça, cliente, ordem de serviço, veículo, serviço, equipe de mecânicos e mecânicos. Modelo funciona da seguinte forma, 

Cliente possui como atributos id cliente, nome, email e CPF. 

Veículos possui como atributos, IB veículo, Placa, Modelo do veículo, Quilometragem.
 
Mecânicos possuem como atributos, ID mecânicos, Nome, Especialidade, Endereço. 

Equipe mecânicos tem como atributos, ID equipe mecânicos, Integrantes, Especialidade da equipe. 

Serviço possui como atributo, ID dos serviços, Tipo(concerto/revisão), Descrição do serviço.
 
Ordem de serviço possui como atributos, ID da ordem do serviço, Data de emissão, Valor, Status, Data de conclusão. 

Por fim temos peça que possui como atributos o ID da peça, descrição, Valor. 

Os relacionamentos funcionaram da seguinte forma, Cliente pode possuir mais de um veículo mas cada veículo pertence a apenas um cliente. Veículo é analisado por uma equipe de mecânicos, e neste sentido. Equipe de mecânicos podem possuir mais de uma ordem de serviço e cada ordem de serviço pode possuir mais de uma equipe de mecânicos. Um modelo de peça pode estar presente em mais de uma ordem de serviço e uma ordem de serviço pode constar mais de uma peça. Os serviços podem possuir mais uma ordem de serviço para aquele  mesmo serviço, e uma ordem de serviço pode constar vários serviços. A equipe de mecânicos pode realizar vários serviços mas cada serviço está relacionado apenas uma equipe de mecânicos e além disso cada equipe de mecânicos possui vários mecânicos mas cada mecânico pertence apenas uma única equipe de mecânicos.
