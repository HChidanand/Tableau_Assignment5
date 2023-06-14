
# Step 1:
Import File to tableau
# Step 2:- Creat A Worksheets
# Open Worksheet1
Drag Mobile Oparating Systems into Rows
% of Usage to label marks
Measure values to colour & Select Marks as Square instead of Automatic
Apply filter to Mobile Oparating Systems & Select Show Filter
Rename worksheet1 as "Total Count of Usage By OS"

# Open Worksheet2
Drag Mobile Operating Systems to column
Measure values to rows
Measure values to labels & remove no of records from measure values
Apply descending nested sort
Drag measure values to colour
Edit Axis Title as blank instead of count of %
Apply filter to Mobile Operating Systems
Rename worksheet2 as " Operating System Count"

# Open Worksheet3
Drag Date to Column & Convert it month
Drag % of usage to rows
Drag Operating system to colour marks & select add all members
Drag % of usage to lable marks
Apply filter to Mobile Opearting Systems
Rename Worksheet3 as "Usage Volume By Year"

# Open Worksheet4
Select Marks as Pie Chart
Drag % of usage to angle
Drag mobile operating systems to colour
Drag % of usage to lable & conver it to % of total
Now here we have creating Donut Chart
Drag no of records to rows
Select Min instead of Sum
Make dublicate for same
Apply Dule axis to 2nd measure inside the rows
Select 1st Measure & Deselect show header
Go to marks marks cards inside select 2nd parameture & remove all mesure values except sum of % total usage & sum of % of usage
Select colour as white & minimize size as suitable
Apply fitre & select top 10 operating system
Rename Worksheet4 as "Top 10 Mobile Operating Systems"

# Open Worksheet5
Drag date to row & convert it to descrite & select month
Drag Measure Values to text & Apply no of record to % of total
Drag measure name to column
Go to analysis tab select totals and select grand column total
Rename worksheet5 as "Total % Usage"

# Open Dashboard1
Creat 2 vertical object inside canvas
Create 1 Horizontal object inside Vertical1
Creat Vertical 3,4,5 inside Horizontal1
Creat Vertical 6,7 inside Horizontal2
Drag "Total % Usage" to vertical 3
Drag "Top 10 Mobile Operating Systems" to vertical 4
Drag "Total Count of Usage By OS" to vertical 5
Drag " Operating System Count" to Vertical 6
Drag "Usage Volume By Year" to Vertical7
Drag all fiter to inside Vertical2 & remove all except 1 fiter of Mobile Operating Systems
Select Dropdown of filter and Select Apply to worksheet and All Using This data source
