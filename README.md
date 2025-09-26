# AnaliseRFV

Abaixo uma planilha de dados sobre compras de clientes, 1 cliente pode ter várias compras em diferentes datas. 
<img width="537" height="706" alt="image" src="https://github.com/user-attachments/assets/5ec8368b-24bf-46c0-8379-d79c60092f8b" />

É possivel a existência de clientes que não compram há muitos dias ou tenham feito compras há pouco tempo, isto  influencia a recência. Então para começar, substitui a data por uma coluna chamada "Dias Última compra", equivalente a data atual menos a ultima data de compra registrada
<img width="360" height="481" alt="image" src="https://github.com/user-attachments/assets/f61d480d-b319-4cf3-81b2-00c5f0b2974f" />

Após isso, algumas definições de intervalos para classificar cada cliente, aplicando-se a quantidade de pedidos por clientes e ao ticket médio de cada cliente.

<img width="1618" height="455" alt="base rfv01" src="https://github.com/user-attachments/assets/9386a2f3-9892-420f-8e83-e73604e4c62c" />


Case com clientes rfv baixo(inativo):
<img width="1059" height="689" alt="Captura de tela 2025-09-25 211434" src="https://github.com/user-attachments/assets/87c0d8cd-8cbe-4e35-8b66-e36805fc9f9d" />



Case com clientes mais preocupantes/prioritários rfv alto(ativo):
<img width="1044" height="612" alt="Captura de tela 2025-09-25 211513" src="https://github.com/user-attachments/assets/0d988083-b29c-4a09-8dee-91c463e20263" />
