# Great Lakes: Maximum Ice Coverage<br><br/>

### Dashboard
<p align="center">
<img width="650em" src="https://github.com/Power-BI-Solutions/Great-Lakes-Maximum-Ice-Coverage/blob/main/Lakes%20Ice%20Coverage.gif" align = "center"/>
</p>
<br><br/>


### Data Source
- [Great Lakes Historical Ice Coverage 1973 to 2020.xlsx](https://data.world/dataveld/wow2021week07/workspace/file?filename=Great+Lakes+Historical+Ice+Coverage+1973+to+2020.xlsx)

<br><br/>

### Custom Measures

```dax
Average Coverage = CALCULATE(AVERAGE(Lakes_Data[Coverage]),Lakes_Data[Lake]<>"All Lakes")
``` 

```dax
Max Coverage = MAX(Lakes_Data[Coverage])
``` 

<br><br/>

### Model

<p align="center">
<img width="650em" src="https://github.com/Power-BI-Solutions/Great-Lakes-Maximum-Ice-Coverage/blob/main/lakes_ice_data.png" align = "center"/>
</p>
<br><br/>

### Acknowledgements
Source: WoW Power BI (Workout Wednesday)
- [Conditional Formatting](https://www.workout-wednesday.com/pbi-2021-w07/)
- [Forecasting and Anomaly Detection](https://www.workout-wednesday.com/pbi-2021-w09/)

YouTube video tutorials:
- [Conditional Formatting](https://www.youtube.com/watch?v=hU12Y7Cd6n8)
- [Forecasting and Anomaly Detection](https://www.youtube.com/watch?v=GWZFgtjc8c0)
