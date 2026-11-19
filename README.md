# Proyecto_Final_Metodos

## Tema del proyecto
**Tema:** Análisis del crecimiento poblacional y la estimación de la esperanza de vida al nacer en condados de Estados Unidos durante los años 2016-2025.
## Objetivos
- Desarrollar y evaluar un modelo numérico que estime la esperanza de vida al nacer por condado, año a partir del crecimiento poblacional, tasas de natalidad y mortalidad bruta, mediante ajustes por mínimos cuadrados, descomposición LU y representar su trayectoria entre años mediante splines cúbicos.
- Cuantificar los errores de las estimaciones de esperanza de vida mediante el error absoluto medio y la raíz del error cuadrático medio, comparando los valores calculados con las referencias históricas para evaluar la presición del modelo.
- Desarrollar la función de interpolación mediante splines cúbicos mediante las estimaciones anuales de esperanza de vida por condado para representar su evolución temporal y aproximar valores intermedios dentro del periodo analizado.

## Descripción del proyecto 
Se analizará la relación que hay entre el crecimiento poblacional y la esperanza de vida al nacer en los condados de Estados Unidos durante los años 2016-2025. Lo que se va a realizar es un modelo que estimará la esperanza de vida, para esto se va a utilizar los datos de el crecimiento poblacional, las tasas de natalidad y mortalidad bruta disponibles para cada condado del año y año. Para este modelo se va utilizar el método de mínimos cuadrados. De igual forma, predecir el crecimiento poblacional del año siguiente utilizando los indicadores previamente mencionados.

El crecimiento poblacional es la combinación de diversos factores combinados como lo son nacimientos, defunciones y migración. Un crecimiento similar pude resultar en combinaciones distintas de dichos factores, por lo que el modelo considerará el crecimiento como factor predictivo principal y el resto de los factores como indicadores complementarios del cambio.

Para el desarrollo de estos modelos se hizo usó de dos dataset que poseen las variables anteriormente mencionadas y de igual manera están agrupadas por condados. El dataset principal es el US Country Population Change, Births, Migrations que posee los datos desde el 2020-2025. El segundo dataset que se utilizó es USA Country Population Total que posee datos desde el 2016-2021, ambos datasets se obtuvieron de Kaggle. Al faltar indicadores complementarios se tomaron del Census Bureau y como verificación y de apoyo complementario el IHME para verificar las referencias históricas de esperanza de vida.

## Número de grupo
**Grupo:**  7

## Integrantes
- Cesar Canizares
- Esteban Moreta
- Byron Silva
  
## Variables Independientes
- Crecimiento Poblacional
- Tasa de natalidad
- Tasa de mortalidad bruta
- Tasa de migración interna neta
- Tasa de migración internacional neta
  
## Variables Dependientes
- Esperanza de vida al nacer del año actual
- Crecimiento poblacional del año siguiente
  
## Métodos a usar
- Splines Cúbicos
- Mínimos Cuadrados
- Descomposición LU

## Asignatura
Métodos Numéricos - ICCD412

## Institución 
Escuela Politécnica Nacional
