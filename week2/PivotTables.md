## What is pivot table ?
Summerizing selected data from raw data 

* What are the four fields of pivot table?

fields:  report filter / column labels / row labels / values
we can sort the data by those field.

### Pivot Tables like Tall, Raw Data   

 Pivot Input data is as on the right...
“Wide” data is on the left.  Sometimes "wide" table data is the result of a Pivot table operation.

<img src="images/pivot ar4.png" width="600" height="410">  
                                                    “Tall” or “Long” data   

To see more, see the section for [Tidy Data](TidyData.md).

## Finding the Pivot Table Command

Video Demos:

* [Mac Excel English Pivot, Count Values](https://youtu.be/fxP81RaPBFQ)
* [Windows Excel French Pivot](https://youtu.be/fsre1PJYDM4)

Step 1. Select your data.(Data set: : FT workers NorthCentral US 1999). Find and Click the PivotTable (“Table Croisée”) on the ribbon toolbar or menu.  
Step 2. *On Windows,* check the “Insert” Ribbon Tab.
	*On Mac,* the “Data” Ribbon Tab.  
Step 3. Also look at the menus (check Insert and Data menus).  

You should get the dialog:  
<img src="images/pivot 1.png" width="600" height="461">   

 *Note: Every column needs a label for this to work!*


Step 4. Click OK (after making sure it shows your selection.)  

On Mac, it makes a “default” pivot table.   On Windows, you need to select the option on the bottom of the suggestions dialog for "Table Vide."

For Mac, it should show the “Builder” open. The command to open it is on top on the ribbon (in case you lose it/close it).

<img src="images/pivot ar1.png" width="600" height="439">   
<img src="images/pivot 2.png" width="374" height="416">   

If you have items in your builder, drag them “out” of the dialog to empty it. Goal is to start from empty:

<img src="images/pivot ar 2.png" width="600" height="445">   
<img src="images/pivot 3.png" width="852" height="417">   


Step 5. How to change value > Average:

<img src="images/pivot 4.png" width="600" height="559">   


Step 6. Grouping : let's group the education years by 5


<img src="images/pivot 5.png" width="585" height="490">

Step 7. Labeling 
* Group 1 > 0-10
* Group 2 > 11-15
* Group 3 > 16-20

<img src="images/pivot 6.png" width="816" height="170">

See the result below

<img src="images/pivot 7.png" width="820" height="170">

### Changing sort order 

* On Windows, right click inside a cell in Values. Choose sort (Trier).
* On Mac, click the Sort button in the Data tab while your mouse is in the column.

### Example : Data set (chi2.csv)
 Let’s do that with chi2.csv, our Chicago dataset.

* Show the top primary crimes in order, descending.

<img src="images/pivot ar5.png" width="276" height="608">   

### Filter Results to "Top 10" on Windows:
Right click on first column item, and you’ll see Filter > Top 10...
(or filter by other options!)  
Get the top 10 crime types.

<img src="images/pivot ar6.png" width="452" height="433">   


### Exercise 1- Do the same operations with Streets now (chi2.csv). (Streets, not block!)  

*What if we wanted to find out which streets had the most arrests?*

Now Add “Arrest” to columns in your pivot table builder:

<img src="images/pivot ar7.png">

Now what about what kind of crimes had the most arrests?

Make Arrests your columns, and the primary type the rows. 
* Sort by Arrests, True.

*Result:*
<img src="images/pivot ar8.png">   


### Filters on Pivot Tables

If you want to dig into a particular type of data, you can make a filter.   
Drag “Primary Type” into the filters area — it will appear above the pivot results —


<img src="images/pivot ar9.png" width="282" height="450">   

and set it to Narcotics.   
<img src="images/pivot ar10.png" width="200" height="93">

[Video of simple filtering on pivot table](https://youtu.be/l1nc62R-68k)


### Nested Rows

If you want to learn more about each ROW (or column) of data, you can add another variable to the same group.       
Try adding Location Description to the Rows under “Street”:  
<img src="images/pivot ar11.png" width="400" height="618">   

**Feel free to change the filter!**

<img src="images/pivot ar12.png" width="400" height="307">   

 
