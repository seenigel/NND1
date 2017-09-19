# Working with Data

Most of the time, when you get data, it's going to come in either **spreadsheet** or **pdf** form. Spreadsheets are the preferred way, because it's easy to take spreadsheet data and turn it into charts and web projects.

- **Tip**: When trying to download data, look for files that end in **.xls**, **.xlsx**, **.csv**, or **tsv**. 

Once you've got a file, you can open it up [Google Sheets](https://sheets.google.com), which is free and absolutely fantastic for making sense of data. *We'll be working in Google Sheets from here on out.*

## Don't be afraid of spreadsheets!

I know, they look intimidating and they make you want to fall alseep, but they're actually a very orderly way to keep track of large amounts of information.

So let's take a look at a typical spreadsheet:

[Today's worksheet](https://docs.google.com/spreadsheets/d/16qzSpZGxTqzR2SS_tRTXJY3nUZEGNCy0ZJcwY8Yc1mg/edit?usp=sharing). It's a selection of datasets (groups of information) from a bunch of sources across the city that you'd probably deal with very often as a metro reporter. It includes:

- 2016 High School Graduation Rates (by district) 
- Motor Vehicle Collisions in West Harlem
- Median Asking Rents in New York City neighborhoods in 2009 and 2016.

Open it, then select **File > Make a Copy** to create a copy for yourself. 

![Spreadsheet Screenshot](spreadsheet.png)

(Microsoft Excel looks generally the same)

There are a couple of key concepts to know when it comes to spreadsheets.

- A vertical line of boxes is called a **column**. (You know, like columns in a building.)
  - Columns are identified by the letter above the first square. (So the first column is named A, the second is named B, and so on.)
- A horizontal line of boxes is called a **row**.
  - Rows are identified by the number in the right left corner. So the first row is 1, the second is 2.
- Each little spreadsheet box is called a **cell.** Cells each have their own unique ID number that comes from the **Column Letter** and the **Row Number**. So the very first cell is named A1. The one to the right of it is named B1. The one below A1 is A2.
- Little section below the toolbar is called the **Formula Bar**. It displays the contents of the cell you've clicked, and it's also where you can write **functions,** which are awesome little commands that you can use to do cool things to the information in your spreadsheet.
- At the very bottom of the page there are little tabs. These tabs are called **worksheets**. A spreadsheet can have multiple worksheets, and you can get send information back and forth between each worksheet. (More on this in a later session.)

For most spreadsheets, the first row contains **Headers**, which are basically just descriptions of what's included. And each row is usually a separate instance of data.

## Working With Data

Now, before we can work with the data, the first thing we have to do is make sure it's in a workable state. A lot of times we'll download data and it will contain a bunch of junk that we don't care about. Fortunately, there are two quick tools we can use to try to quickly find what we're looking for: **sort** and **filter**.

## Sort and Filter

These commands let you do exactly what they sound like. Sort let you arrange the rows in the spreadsheet based on one of the columns headers, and filter lets you temporarily hide rows that you don't need to see.

Both commands can be accessed by highlighting your column header and then clicking this icon:

![Filter Icon](filter.png)



One you do that you'll see little upside-down triangles next to each column header. Clicking a triangle will open a up a little box that gives you the option to sort the spreadsheet and filter out views.

![filter box](filter_box.png)

**Try it**: In the **Sort and Filter** tab, try to filter out all of the grades **except* 6th Grade**. And then try to sort the data by test score from highest to lowest.

## Functions

As mentioned above, functions are little instructions that you can use to quickly do math, or format text.

Functions usually have the following syntax:

**=FUNCTION_NAME(First Cell, Second Cell)**

Take for example the screenshot below:

![sum1](sum1.png)

If I wanted to add the values A2 and B2, I would use the **SUM** function and write:

**=SUM(A2, B2)**

![sum2](sum2.png)

You can also quickly add up a range of numbers by writing **=SUM(First Cell:Last Cell)**

## Other Common Functions:

- =AVERAGE: This lets you get the average of a group of numbers
- =MEDIAN: Finds the median number (the middle number in a group of numbers)
- =PRODUCT: Lets you multiply numbers
- =PROPER: Turns WiErD and SHOUTY text into properly formatted text
- =COUNT: Counts the number of rows in a column
- ​

## Percent Change 
To find out how two numbers have changed, you can calcuate the percent change. The formula is
- **=((new -old)/old)**

  **Try It**: In the Median Rent worksheet, calculate the percent change in neighborhood rent prices.



## Further Reading
- [Common Excel Functions](../resources/CommonFormulasFunctions.pdf)

## Questions?

Email or call me!
- nchiwaya@gmail.com
- 347-901-9095