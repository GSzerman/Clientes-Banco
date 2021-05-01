Nuestro objetivo es predecir si un cliente va a dar de baja su tarjeta de crédito 
para poder enfocar energías de manera proactiva en brindarle a los clientes mejores servicios y evitar que se den de baja
Hay dos columnas que están de mas que debemos eliminar según el creador del dataset.

Fuente de datos: www.kaggle.com/sakshigoyal7/credit-card-customers


Este conjunto de datos consta de 10,000 clientes que mencionan su edad, salario, estado civil, límite de tarjeta de crédito, categoría de tarjeta de crédito, etc. Hay casi 18 características.
Solo tenemos un 16,07% de los clientes que se han agotado


Que significa cada columna:

CLIENTNUM: Número de cliente. Identificador único del cliente titular de la cuenta

Attrition_Flag: "Desgaste". Describe si el cliente está activo o ya se agotó y se fué del banco. Esta es la variable que quiero predecir.

Customer_Age: Variable demográfica - Edad del cliente en años

Gender: Variable demográfica - M = Masculino, F = Femenino

Dependent_count: Variable demográfica - Número de dependientes del cliente

Education_Level: Variable demográfica - Nivel educativo del titular de la cuenta (ejemplo: escuela secundaria, graduado universitario, etc.)

Marital_Status: Variable demográfica: Casado, soltero, divorciado, desconocido

Income_Category: Variable demográfica - Categoría de ingreso anual del titular de la cuenta (<40K, 40K - 60K, 60K− 80K, 80K− 120K,>

Card_Category: Variable de producto - Tipo de tarjeta (azul, plateada, dorada, platino)

Months_on_book: Período de relación con el banco en meses

Total_Relationship_Count: No total. de productos en poder del cliente

Months_Inactive_12_mon: No. de meses inactivos en los últimos 12 meses

Contacts_Count_12_mon: No. de contactos en los últimos 12 meses

Credit_Limit ; Límite de crédito en la tarjeta de crédito

Total_Revolving_Bal: Saldo rotatorio total en la tarjeta de crédito

Avg_Open_To_Buy: Línea de crédito abierta para comprar (promedio de los últimos 12 meses)

Total_Amt_Chng_Q4_Q1: Cambio en el monto de las transacciones (Q4 sobre Q1)

Total_Trans_Amt: Importe total de las transacciones (últimos 12 meses)

Total_Trans_Ct: Total de transacciones (últimos 12 meses)

Total_Ct_Chng_Q4_Q1: Cambio en el recuento de transacciones (Q4 sobre Q1)

Avg_Utilization_Ratio: Índice de uso promedio de la tarjeta

Total_Relationship_Count : Número total de productos en poder de los clientes (tarjetas, cuentas, etc.)

Contacts_count_12_mont : Contiene la cantidad de veces que el banco contactó al cliente y / o viceversa

Total_Amt_Chng_Q4_Q1 : Representa cuánto aumentó el cliente su gasto al comparar el 4º trimestre con el 1º.

Total_Ct_Chng_Q4_Q1 : Similar al anterior pero en número de transacciones.