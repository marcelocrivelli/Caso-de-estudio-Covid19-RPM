# Caso-de-estudio-Covid19-RPM


Para este trabajo se usó un dataset obtenido de https://github.com/Atharva-Peshkar/Covid-19-Patient-Health-Analytics el cual cuenta con un .csv con los datos de pacientes de covid19.
Este dataset fue obtenido originalmente de Kagle: https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset. 

La base de datos cuenta con información de casos de covid19 en pacientes de diferentes paises. 

Los atribtuos de cada uno son:

<ul>
  <li>id - El identificador del paciente (número)</li>
<li>location - Ciudad</li>
<li>country - País</li>
<li>gender - Género</li>
<li>age - Edad</li>
<li>sym_on - Fecha de los síntomas</li>
<li>hosp_vis - Fecha en que visitó hospital</li>
<li>vis_wuhan - 1 si el paciente visitó Wuhan, 0 en caso que no</li>
<li>from_wuhan - 1 si el paciente es de Wuhan, 0 en caso que no</li>
<li>death - 1 si el paciente falleció, 0 en caso que no</li>
<li>recov - 1 si el paciente se recuperó, 0 en caso que no</li>
<li>symptom1 - Síntoma</li>
<li>symptom1 - Síntoma</li>
<li>symptom3 - Síntoma</li>
<li>symptom4 - Síntoma</li>
<li>symptom5 - Síntoma</li>
<li>symptom6 - Síntoma</li>
</ul>

El objetivo es determinar para un paciente si muere de covid o no. Para esto el atributo objetivo es death. Se va a utilizar un modelo de Gradient Boosted Trees para el modelo en RapidMiner.
Se utiliza Cross Validation con 10 folds.

Se obuvó un accuracy de 94,41% +/- 1,59%



