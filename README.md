Changes made from raw dataset file 
1.	Adjusted rows and columns using- Alt+H+O+I and Alt+H+O+A
2.	Fixed the client row (removed all values in ()) via using find and replace- Made 31 changes 
3.	Changed client name row from lower to upper case via creating a new column Named as client name and using (=lower: selecting old row named as client as reference) once done copied the client name column and pasted the data again as value so the reference will not come (Alt + H + V +V)
4.	Fixed the contact column via creating a new column named as contacts used the formula (TRIM(PROPER(D3)) then dragged the same on the entire contact column then again pasted as value so you won’t get the reference error once done deleted the old contact column
5.	The data in the department column was mixed with the region names so separated the two- Made a new column named as region then DATA- Text to column- set delimiter as _ as the region names were after the _ .
6.	Removed duplicates (Data – Data tools – remove duplicates)3 duplicates were removed 
7.	Few entries were blank so replaced them with NA via using find and replace – Go to special- Blanks -NA – Ctrl + Enter
8.	In the profit column some of the values were showing as error as few entries were missing in the revenue/profit column so used   ( IFERROR ) 	and dragged the same for the entire profit margin column.
9.	Formatted the Header (bold and changed colors)
10.	Removed grid lines 
