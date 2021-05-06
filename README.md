# DAML-Smart_Parking-Project
Codigo utilizado na implementação de uma rede Blockchain


Linguagem: DAML

Como vai funcionar o blockchain?

•	Registo do Carro
Através de uma APP, o condutor regista o seu carro com as informações do mesmo, como por exemplo, matrícula, o titular do carro, marca, modelo etc. Desta forma, é enviado para o blockchain a informação, na qual, o Issuer ou entidade confirma os dados atribuindo um ID para o registo e posteriormente guardar na ledger.
•	Reservar uma vaga de estacionamento 
O condutor/user através da APP procura o parque de estacionamento e pergunta para a mesma se a vaga está livre/ocupada. Posto isto, a APP faz um pedido à rede blockchain e a rede verifica no ledger se a vaga está realmente livre/ocupada. Caso esteja livre, o condutor reserva o espaço.
•	Mudança do estado da vaga
IOT BOX - através da câmara, esta deteta a placa do veículo e a vaga de estacionamento passando automaticamente o espaço de livre/reservado para ocupado. A informação é enviada para a rede blockchain e posteriormente guardada no ledger.
•	Chegada do veículo ao parque
Na chegada do veículo ao parque, o IOT BOX, vai verificar se o veículo tem saldo na Wallet > 0 e se tem uma reserva. Caso o veículo não tenha saldo suficiente, ele deverá utilizar outro sistema para entrar no parque (Machine-to-Machine)
•	Pagamento
À saída do parque, é enviada uma mensagem de fim de estacionamento à rede e é efetuado o pagamento automático do montante consoante o tempo de ocupação da vaga de estacionamento. Se o condutor não tiver saldo suficiente é descontado na mesma o valor, ficando com saldo negativo. Desta forma, só é possível voltar a estacionar no parque quando liquidar esta dívida.
O IOT BOX então muda o estado da vaga de ocupado para livre.

•	Tokens
O condutor tem a opção de comprar antecipadamente um determinado nº de tokens, servindo de modo de pagamento, para ocupar a vaga de estacionamento. Haverá também, a possibilidade de o condutor comprar X de Tokens e a empresa oferecer X de tokens como incentivo.
Nota: prove of stake

