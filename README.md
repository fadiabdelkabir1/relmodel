PS: if an attrebute has infront of it a * it means its a unique identifier for that relation, and if theres an # it means its a migreted identifier

7abit nekteb houni direct manghir mano93ed nimporti fil ficher XD 

Hotel(*Hotel_ID,Hotel_name,#Type_ID)
Type(*Type_ID,Type_Name)
Category(*Category_ID,Category_name,Price,Beds_Number)
Room(*Room_ID,Floor,#Hotel_ID,#Category_ID)
Employee(*Employee_ID,Employee_Name,Employee_Specialty,#Director_ID,#Hotel_ID)
