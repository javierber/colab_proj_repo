# Sales Predicitons

### Goal

Try and predict the improving sales of products at various supermarkets and grocery stores using different variables.  Presenting my findings using Data Visualizations, along with Machine Learning showing Linear Regression and Decision Tree models 

The following project had data from the Sales_Prediction CSV file.  Which has sales prediction for food items sold at various stores. The data was ETL'd (Extract, Transform, Load). We extracted data from the CSV file, cleanse the data to improve data quality and establish consistency, Load data into a target dataframe. We then created and analyze the data with visuals, and incoporated machine learning applications to evaluate and develope predictive modeling. 

A slideshow is also included for non-technical audiences to show the findings that impacts sales and help predict sales improvement. See the README_SalesPredictions.md

### Data Visuals
![Sales_Prediction_2021](https://user-images.githubusercontent.com/15024128/144360947-d355c643-499a-4068-900f-cf0367deaa15.jpg)
![Sales_Prediction_2021_slide2](https://user-images.githubusercontent.com/15024128/144361026-444b0f06-36e9-4182-b85b-d06e00378163.jpg)
![Sales_Prediction_2021_Slide3](https://user-images.githubusercontent.com/15024128/144361084-c5336022-c38f-45bb-84a3-7de283b366b8.jpg)
![Sales_Prediction_2021_Slide4](https://user-images.githubusercontent.com/15024128/144361090-130ec7c9-293e-4442-9131-3e09db4f8aee.jpg)
![Sales_Prediction_2021_Slide5](https://user-images.githubusercontent.com/15024128/144361099-6ce305df-25c9-4351-b48c-7889dd96eb98.jpg)


### Machine Learning Models


<table>
<tr>
<th>Linear Regression Model Train scores: </th>
<th>Linear Regression Model Test scores:</th>
</tr>
<tr>

<td>

| RMSE | R2 |
|--|--|
| 1140.23043238183 | 0.5606876504550881 |

</td><td>

| RMSE | R2 |
|--|--|
| 1094.4274329515092 | 0.5658639847125961 |

</td></tr> </table>


<table>
<tr>
<th>Decision Tree Model Train scores: </th>
<th>Decision Tree Regression Model Test scores:</th>
</tr>
<tr>

<td>

| RMSE | R2 |
|--|--|
| 740.0890143888215 | 0.8149214572188905 |

</td><td>

| RMSE | R2 |
|--|--|
| 1316.0877848650157 | 0.3721995954349131 |

</td></tr> </table>
