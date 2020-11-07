# Caso-de-estudio-Covid19-RPM


Para este trabajo se usó un dataset obtenido de https://github.com/Atharva-Peshkar/Covid-19-Patient-Health-Analytics el cual cuenta con un .csv con los datos de pacientes de covid19.
Este dataset fue obtenido originalmente de Kagle: https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset. 

La base de datos cuenta con información de casos de covid19 en pacientes de diferentes paises. 

Los atribtuos de cada uno son:

id - El identificador del paciente (número)
location - Ciudad
country - País
gender - Género
age - Edad
sym_on - Fecha de los síntomas
hosp_vis - Fecha en que visitó hospital
vis_wuhan - 1 si el paciente visitó Wuhan, 0 en caso que no
from_wuhan - 1 si el paciente es de Wuhan, 0 en caso que no
death - 1 si el paciente falleció, 0 en caso que no
recov - 1 si el paciente se recuperó, 0 en caso que no
symptom1 - Síntoma
symptom1 - Síntoma
symptom3 - Síntoma
symptom4 - Síntoma
symptom5 - Síntoma
symptom6 - Síntoma

El objetivo es determinar para un paciente si muere de covid o no. Para esto el atributo objetivo es death. Se va a utilizar un modelo de Gradient Boosted Trees para el modelo en RapidMiner.
Se utiliza Cross Validation con 10 folds.

Se obuvó un accuracy de 94,41% +/- 1,59%



