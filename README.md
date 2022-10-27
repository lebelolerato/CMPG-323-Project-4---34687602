# CMPG-323-Project-4---34687602
RPA

In this project we are automating the process of logging in, registering into a web page and also inputing data. The we test each data input from the excel file if its valid or not as we input it.

## This is what is happening in my Automation project:
So firstly I am using the UiPath community app and instead of using the modern design experience, I used the classic design experience.
  
  ### Steps
      1. We read the data in each spreadsheet
      2. Create DataTables for Zone, Category, and Device
      3. Create the appropriate column names or attributes for each DataTable 
      4. We type Each row in each spread sheet into the specifc DataTable
      5. Save the data in the each DataTable in a variable for refence later
      
  ### Steps for logging in
 
      2. Click the login button on the menu or left panel
      3. Type your email into the the "Email" TextBox
      4. Type your Password into the "Password" Textbox
      5. Click the log in button at the bottom
      
 ### Steps for Intserting
 
      1. Click Zones or Categories or Devices on the left side
      2. Click the + icon next to the name on the Table on your right corner
      3. Type into the specific fields reading from the specific DataTables
      4. Click "Add" button
      
      For inserting the Device I added an If statement for when the IsActive == True then the UiPath automation should automatically check the active checkbox and if         not then click the add button
      
 ### Steps for Delete
 
      1. Click Zones or Categories or Devices on the left side
      2. Click the dusbin icon nexg to the item you want to delete
      3. Click the delete button.
 
 ### Steps for Update
      
      1. Click Zones or Categories or Devices on the left side
      2. Click the Pen icon next to the item you wanna edit 
      3. Read the Text thats already present 
      4. Save it in a variable
      5. Edit the text by adding the word "EDITED" next to the existing text which is store in a variable
      6. Click the "Save" button
      7. Click the "Back to list" url
      
