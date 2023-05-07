Download Link: https://assignmentchef.com/product/solved-lab-5-water-consumption
<br>
The city of Paris, Texas tracks how much water is consumed by its citizens on a monthly basis.  The City Manager would like statistics about the consumption.  She would like to know the months with the highest and lowest consumption, the yearly average, and the yearly total.  NOTE:  Water consumption is measured in CCF (centum cubic feet)

The main function should:

Create an array to store the twelve months of consumption.

Call the following functions, passing the array to all but the print headers function:

<ol>

 <li><strong>Get data from user</strong>: The function should use a loop to ask the user for the amount consumed for 12 months, using the appropriate month name and store the data in the consumption array.</li>

</ol>

<strong>     Input Validation:</strong> Do not accept negative numbers.

Your screen dialog might look similar to this (user input is shown in <strong>bold</strong>):

<table width="0">

 <tbody>

  <tr>

   <td width="632">Enter water consumption in CCF for January: <strong>500000</strong>Enter water consumption in CCF for February: <strong>400000</strong><strong>Etc.</strong>…</td>

  </tr>

 </tbody>

</table>




<ol start="2">

 <li><strong>Print the headers</strong>: which should ask for the year of the report to be displayed in the header and print the headers.   <strong>Input Validation:</strong> The year should be validated to be between 2005 and 2020.</li>

 <li><strong>Display the consumption</strong>: Using the data from the consumption array, display the consumption for the year for each month with appropriate month labels.</li>

 <li><strong>Get lowest consumption</strong>: Using the data from the consumption array, determine the month with the lowest consumption, print the month name and the amount of the consumption for that month.</li>

 <li><strong>Get highest consumption</strong>: Using the data from the consumption array, determine the month with the highest consumption, print the month name and the amount of the consumption for that month.</li>

 <li><strong>Get total and average consumption</strong>: Using the data from the consumption array calculate the total and average of all months for the year and print them.</li>

</ol>




<strong>Sample Output</strong>

<table width="0">

 <tbody>

  <tr>

   <td>                  2016 Consumption Report for Paris, Texas Month     Consumption in CCF—————————-January    500000February   250000Etc.. The lowest consumption was in March with 100000 CCFThe highest consumption was in July with 900000 CCFThe total consumption for the year: 2000000 CCFThe average consumption for the year:  500000 CCF</td>

  </tr>

  <tr>

   <td> </td>

  </tr>

 </tbody>

</table>

<strong>Modularity</strong> Your program must be a modular program. Your main function should not contain any loops. It should call all of the functions described above, calling a total of 6 functions

<strong>Additional Requirements:</strong>

<ol>

 <li>Do not use global variables in any assignment. A global variable is a variable that is declared outside any function. It is okay to use global constants.</li>

 <li>When passing the array to a function that does not modify it, use the const keyword to prevent any modification to the array.</li>

 <li>To find the minimum and maximum values sort the array first.</li>

</ol>


