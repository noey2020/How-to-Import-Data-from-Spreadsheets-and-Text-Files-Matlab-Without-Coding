# How-to-Import-Data-from-Spreadsheets-and-Text-Files-Matlab-Without-Coding

August 27, 2020

I appreciate comments. Shoot me an email at noel_s_cruz@yahoo.com!

Hire me!

Hello and welcome to another MATLAB tutorial. Today we’re going to talk about importing spreadsheet data using the import tool.

The import tool is really straightforward to use, you just go up to the home bar and press the import button here and it asks you to select a file. I have list of possible files to choose from in this folder, some are CSV, excel docs, txt files.

MATLAB supports a wide variety of file types as you can see in the documentation, but today we’re focusing on spreadsheets and text files. That said you can import images, videos, etc outside of the import tool. Additionally, if you have a file such as a JSON, you can use the file read function and import it as text.

Yeah so when you open the import tool, you get a window to select file, select the file you need. Here we’re going to choose this excel file. You can have more than one file open at once, you just tap import data again and you get the same options and then I’m going to select this txt file. And boom we have two documents we can toggle between. In a similar vein, if you have more than one sheet in your excel doc it imports those as well.

When importing txt files, the import tool is relatively smart and can figure out the delimiter in the file. As you can see with this file.

But if it gets it wrong as it did with this baa delimited text file, bsv if you will, you can go up here to the column delimiters and just select the right one. It gives you suggested delimiters with a button here to enter a custom delimiter if what you need is not mentioned. When it comes to fixed width delaminated text files it gets a little trickier. You have to click the fixed width button and then it reformats, and you can take these lines here and move them create the columns.

The import tool can also recognize the variable type of the particular columns. Including datetime and identifying constant characters such as dollar signs or percentages as you can see here.

If you want, you can import the entirety of the spreadsheet as table but let’s say you don’t. You can select and deselect columns by ctrl-clicking or highlight the sections you want or go up here to the range box and select a range of values to import. The values don’t have to be continuous, you can pretty much completely pick and choose so long as the columns are consistent.  

You also don’t have to import as a table, you can import as matrix for example. However, this selection includes values that are not numbers. Brightly highlighted in yellow here. You can control how these un-importable values are imported up here, you can replace them as NaNs or Zeros, or just exclude those rows and/or columns all together. If you don’t specify a rule here and you have an un-importable value, the import tool won’t let you import.

So now the data is selected, you have two options, you can either press the import button and import the data into the workspace like this:

See really simple.

Or you can select the drop down and generate code. You have a couple of different options, you can generate it as a function, script, or live script. Depending on what you need.

This is helpful if you want to automate the importing of one or many files as you can program it to loop though different files by changing the file location and output name on each loop.

I included some posts for reference.

https://github.com/noey2020/How-to-Talk-Model-of-Stock-Market-Prices-

https://github.com/noey2020/How-to-Talk-Digital-Wallets

https://github.com/noey2020/How-to-Talk-Investing

https://github.com/noey2020/How-to-Double-Your-Money-in-5years

https://github.com/noey2020/How-to-Talk-Matlab

I appreciate comments. Shoot me an email at noel_s_cruz@yahoo.com!

Thanks for reading, and happy coding. 

Hire me!

Noel

