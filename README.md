# DataTrabajoEstadistica

#Las presentes variables se relacionan al lado social de las variables independientes, y permitiran entender si existe una relacion entre estas y el presupuesto designado a la compra de armamento militar. 

#CPI2016_FullDataSetWithRegionalTables_200409_135127 corresponde a la Variable CPI.
El indice de percepcion de corrupcion (CPI)  esta elaborado por Transparencia Internacional, que es una coalicion global contra la corrupcion. Este indice clasifica a diferentes paises alrededor del mundo segun sus niveles percibidos de corrupcion en el sector publico, segun expertos y empresarios, mas no la opinion publica. Estos datos se calculan a partir de 13 fuentes externas que puntuan a los paises en su propia escala. De esta manera, el CPI es una estandarizacion del 0 - 100 que sirve para poder realizar comparacion y rankear a los paises. Por ultimo, Transparencia Internacional toma en cuenta a paises que solo tengan presencia en minimo 3 de las 13 fuentes para reforzar la fiabilidad. No obstante, es importante mencionar que esta data no toma en cuenta para su elaboracion: fraude fiscal, lavado de dinero o flujos ilicitos de dinero; pero es importante mencionar que es una data que trata de medir la corrupcion de manera mas completa y es revisada regularmente por evaluadores independientes. 
En el presenta trabajo se usara la data correspondiente al 2016 que toma en cuenta a 176 paises. 

#2016_population1.xlsx corresponde a la Variable Refugiados 2016.
Los datos fueron recogidos de la pagina de el Alto Comisionado de las Naciones Unidas para los Refugiados (UNHCR). La base de datos contiene información sobre poblaciones desplazadas por la fuerza a lo largo de casi 70 años de actividades estadísticas. Cubre poblaciones desplazadas como refugiados, solicitantes de asilo y desplazados internos, incluida su demografía. También, se incluyen los apátridas. Los datos provienen principalmente de los gobiernos y también de las operaciones del ACNUR. Esta variable no presente una escala, sino que son la cantidad total de Refugiados por pais. 
Para el trabajo se tomo la data perteneciente al 2016 y que toma en cuenta a 185, por otro lado, se elimino la fila correspondiente a los apatridas. 

#CPI+REF.
Es la base correspondiente al merge entre las anteriores variables. Cabe indicar que debido a la ausencia de valores entre paises, se pasaron a eliminar estos. 
