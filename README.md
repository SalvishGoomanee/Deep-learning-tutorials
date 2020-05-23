## Regression model with Keras

This notebook is a simple Keras based regression model where four different models with different parameters and number of hidden were compared after training. 


The evaluation metrics pertaining to each were summarised at the end of the notebook.

The models studied were


- A model trained for 50 epochs with unnormalised data and one hidden layer.

- A model trained for 50 epochs with normalised data and one hidden layer.

- A model trained for 100 with normalised data and one hidden layer. 

- A model trained for 50 epochs with normalised data and three hidden layers.

<hr>


### Summary of Results

<!DOCTYPE html>
<html>

   <head>
      <title>HTML Table Cellpadding</title>
   </head>
	
   <body>
      <table border = "1" cellpadding = "5" cellspacing = "5">
         <tr>
            <th>Sections</th>
            <th>MSE</th>
            <th>Mean</th>
            <th>Stan. dev.</th>
         </tr>
         <tr>
            <td>Part A</td>
            <td> 45.60</td>
            <td> 47.25</td>
            <td> 1.27 </td>
         </tr>
         <tr>
            <td>Part B</td>
            <td> 38.08</td>
            <td> 63.06</td>
            <td> 0.20 </td>
         </tr>
         <tr>
            <td>Part C</td>
            <td> 40.58</td>
            <td> 25.82</td>
            <td> 0.25 </td>
         </tr>
         <tr>
            <td>Part D</td>
            <td> 29.92</td>
            <td> 15.83</td>
            <td> 0.27</td>
         </tr>
      </table>
   </body>
	
</html>
