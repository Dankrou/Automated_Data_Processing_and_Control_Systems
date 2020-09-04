## Автоматизированные информационно-управляющие системы

### Лекция 1. Введение в науку о данных

<hr>

### Версия Python


```python
!python --version
```

    Python 3.8.3


<hr>

### Импорт необходимых инструментов


```python
import numpy as np              # Научные вычисления
import pandas as pd             # Обработка и анализ данных
import matplotlib as mpl        # Визуализация графиков
import matplotlib.pyplot as plt # MATLAB-подобный способ построения графиков
import seaborn as sns           # Визуализация графиков (надстройка над matplotlib)
```

### Настройки необходимых инструментов


```python
pd.set_option('display.max_columns', None) # Максимальное количество отображаемых столбцов
pd.set_option('display.max_rows', None)    # Максимальное количество отображаемых строк
```

### Версии необходимых библиотек


```python
pkgs = {
    'Package': [
        'NumPy', 'Pandas', 'Matplotlib', 'Seaborn'],
    'Version': [i.__version__ for i in [np, pd, mpl, sns]]}

df_pkgs = pd.DataFrame(data = pkgs)   # Версии используемых библиотек
df_pkgs.head(None).style.hide_index() # Отображение первых N строк или все если указать None
```




<style  type="text/css" >
</style><table id="T_b0a6f178_ee8b_11ea_b475_acde48001122" ><thead>    <tr>        <th class="col_heading level0 col0" >Package</th>        <th class="col_heading level0 col1" >Version</th>    </tr></thead><tbody>
                <tr>
                                <td id="T_b0a6f178_ee8b_11ea_b475_acde48001122row0_col0" class="data row0 col0" >NumPy</td>
                        <td id="T_b0a6f178_ee8b_11ea_b475_acde48001122row0_col1" class="data row0 col1" >1.18.5</td>
            </tr>
            <tr>
                                <td id="T_b0a6f178_ee8b_11ea_b475_acde48001122row1_col0" class="data row1 col0" >Pandas</td>
                        <td id="T_b0a6f178_ee8b_11ea_b475_acde48001122row1_col1" class="data row1 col1" >1.0.5</td>
            </tr>
            <tr>
                                <td id="T_b0a6f178_ee8b_11ea_b475_acde48001122row2_col0" class="data row2 col0" >Matplotlib</td>
                        <td id="T_b0a6f178_ee8b_11ea_b475_acde48001122row2_col1" class="data row2 col1" >3.2.2</td>
            </tr>
            <tr>
                                <td id="T_b0a6f178_ee8b_11ea_b475_acde48001122row3_col0" class="data row3 col0" >Seaborn</td>
                        <td id="T_b0a6f178_ee8b_11ea_b475_acde48001122row3_col1" class="data row3 col1" >0.10.1</td>
            </tr>
    </tbody></table>




```python

```
