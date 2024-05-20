![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Laboratorio | Limpieza de datos categóricos

Para esta práctica de laboratorio, usaremos el conjunto de datos del Caso de Negocio de Análisis de Clientes. Este conjunto de datos se puede encontrar en la carpeta `files_for_lab`. En esta práctica de laboratorio exploraremos datos categóricos. También puede continuar trabajando en el mismo cuaderno Jupyter de la práctica de laboratorio anterior. Sin embargo eso no es necesario.

### Instrucciones

1. Importe las bibliotecas necesarias si está iniciando un nuevo cuaderno.
2. Cargue el csv. Utilice la variable `customer_df` como `customer_df = pd.read_csv()`.
3. ¿Qué debemos hacer con la columna `customer_id`?
4. Cargue las variables continuas y discretas en las variables `numericals_df` y `categorical_df`, por ejemplo:
    ```py
    numérico_df = cliente_df.select_dtypes()
    categorical_df = cliente_df.select_dtypes()
    ```
5. Trace cada variable categórica. ¿Qué puedes ver en las tramas? Tenga en cuenta que en la práctica de laboratorio anterior utilizó un diagrama de barras para trazar datos categóricos, con cada categoría única en la columna en el eje x y una medida apropiada en el eje y. Sin embargo, esta vez probarás una trama diferente. Esta vez, en cada gráfico de la variable categórica tendrá cada categoría única en la columna del eje x y el objetivo (que es numérico) en el eje y.
6. Para los datos categóricos, verifique si es necesario realizar alguna limpieza de datos.
**Sugerencia**: Puede usar la función `value_counts()` en cada una de las columnas categóricas y verificar la representación de diferentes categorías en cada columna. Analice si esta información podría usarse de alguna manera para la limpieza de datos.