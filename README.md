# PromoE-DA-Modulo3-sprint1-Ana-Catalina-Natalia

### Propietarias
Ana Isabel López Navarro, Natalia Barquín Urbistondo y Catalina Tomas Jaume Miquel
Estudiantes en Adalab, Bootcamp: Data Analytics, Promoción E (Evelyn)
### Descripción del proyecto
En este repositorio se encuentran los ejercicios realizados como evaluación del Bootcamp: Data Analytics, Promocion E (Evelyn), que se realiza para poder comprobar que se han asumido los objetivos de aprendizaje del curso.

Estos ejercicios, además de reflejar la progresión de aprendizaje, quedarán disponibles para consultas futuras.

El proyecto de esta evaluacion tiene como objetivo realizar diferentes modelos de aprendizaje supervisado para ayudarnos a predecir los resultados de dos datasets.



### Estructura
    <PromoE-DA-Modulo3-sprint1-Ana-Catalina-Natalia>
        <data>
            <regresion_lineal>
                <supermarket_1.csv>
                <supermarket_1.pkl>
                <supermarket_2.csv>
                <supermarket_2.pkl>
                <supermarket_3.csv>
                <supermarket_4.pkl>
                <supermarket_estand.csv>
                <supermarket_estand.pkl>
                <supermarket_norm.csv>
                <supermarket_norm.pkl>
                <supermarket_sales-Sheet1.csv>
            <regresion_logistica>
                <df_cat_1.csv>
                <df_num_1.pkl>
                <df_travel_1.pkl>
                <df_travel_balanceado_b.csv>
                <df_travel_balanceado.csv>
                <df_travel_estenc.csv>
                <df_travel_modelo.csv>
                <df_travel_test_50>
                <df_travel_test_60.csv>
                <df_travel insurance.csv>
        <regresion_lineal>
            <Pair_ML1_Intro.ipynb>
            <Pair_ML2_Test_Estadisticos.ipynb>
            <Pair_ML3_correlacion_covarianza.ipynb>
            <Pair_ML4_Iasunciones.ipynb>
            <Pair_ML5_normalizacion.ipynb>
            <Pair_ML6_estandarizacion.ipynb>
            <Pair_ML7_ANOVA.ipynb>
            <Pair_ML8_encoding.ipynb>
            <Pair_ML9_RLineal_ML10_metricas.ipynb>
            <Pair_ML11_DecisionTree_ML12_RandomForest.ipynb>
        <regresion_logistica>
            <Pair_RLO1_EDA.ipynb>
            <Pair_RLO2_Preprocesadp.ipynb>
            <Pair_RLO3_Ajuste_RLO4_metricas.ipynb>
            <Pair_RLO5_DecisionTree_RLO6_RandomForest.ipynb>
        <README>



### Data

1. Regresion_lineal:

[supermarket-sales](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales):


    Branch: Branch of supercenter (3 branches are available identified by A, B and C).
    
    City: Location of supercenters

    Customer type: Type of customers, recorded by Members for customers using member card and Normal for without member card.

    Gender: Gender type of customer
    
    Product line: General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel

    Unit price: Price of each product in $

    Quantity: Number of products purchased by customer

    Tax: 5% tax fee for customer buying

    Total: Total price including tax

    Date: Date of purchase (Record available from January 2019 to March 2019)

    Time: Purchase time (10am to 9pm)

    Payment: Payment used by customer for purchase (3 methods are available – Cash, Credit card and Ewallet)

    COGS: Cost of goods sold

    Gross margin percentage: Gross margin percentage

    Gross income: Gross income

    Rating: Customer stratification rating on their overall shopping experience (On a scale of 1 to 10)

2. Regresión logística:

[travel-insurance](https://www.kaggle.com/datasets/mhdzahier/travel-insurance):

    Target: Claim Status (Claim.Status)

    Name of agency (Agency)

    Type of travel insurance agencies (Agency.Type)

    Distribution channel of travel insurance agencies (Distribution.Channel)

    Name of the travel insurance products (Product.Name)

    Duration of travel (Duration)

    Destination of travel (Destination)

    Amount of sales of travel insurance policies (Net.Sales)

    Commission received for travel insurance agency (Commission)

    Gender of insured (Gender)

    Age of insured (Age)




### Librerías usadas
[Numpy](https://numpy.org/doc/)

[Pandas](https://pandas.pydata.org/docs/user_guide/index.html)

[sidetable](https://pypi.org/project/sidetable/)

[Matplotlib](https://matplotlib.org/3.5.1/plot_types/index.html)

[Seaborn](https://seaborn.pydata.org/)

[scipy](https://docs.scipy.org/doc/scipy/)

[math](https://docs.python.org/3/library/math.html)

[datetime](https://docs.python.org/3/library/datetime.html)

[itertools](https://docs.python.org/3/library/itertools.html)

[researchpy](https://researchpy.readthedocs.io/en/latest/)

[IPython.core.interactiveshell](https://ipython.org/ipython-doc/rel-0.12.1/api/generated/IPython.core.interactiveshell.html)

[warnings](https://docs.python.org/3/library/warnings.html)

[sklearn](https://scikit-learn.org/0.18/_downloads/scikit-learn-docs.pdf)

[statsmodels](https://conference.scipy.org/scipy2010/slides/skipper_seabold_statsmodels.pdf)

[imblearn](https://imbalanced-learn.org/stable/)

[tqdm](https://pqdm.readthedocs.io/_/downloads/en/latest/pdf/)