# TrenchCoatsManager
 A trench coats manager application, providing two application modes: admin and user mode. The user can also add trench coats to a shopping basket which is stored externally.
 
 
 ## Features
 - a window lets the user choose the application mode (```user``` or ```admin``` mode). Also, the user is allowed to ```change``` the type of file (between ```CSV``` and ```HTML```) where the shopping basket is displayed (providing the user enters user mode and adds something to the basket)
 - multiple undo/redo functionality for the add, remove, update operations and for all the features related to the shopping basket (e.g., adding a product to the shopping basket)
 - key combinations for the undo/redo functionality (```Ctrl-Z``` and ```Ctrl-Y```) 
 
 ### Admin mode features:
 - display a table with all the available trench coats and their representative photos (for each trench coat, its color matches the one of the trench coat in the image)
 - add a new trench coat
 - remove an existing trench coat
 - update an existing trench coat
 - display statistics: a pie chart of all the available sizes
 - switch to user mode

 ### User mode features:
 - display button: see the trench coats in the database, having a given size, one by one. If the size is empty, then all the trench coats will be considered. When the user chooses this option, the data of the first trench coat (size, colour, price, quantity) is displayed, along with its photograph
 - the trench coat's photograph is displayed by launching a browser and opening the trench coat's link
 - the user can choose to add the trench to the shopping basket. In this case, the price is added to the total sum the user has to pay. The total sum will be shown after each purchase. Also, the quantity of the added trench coat (how many trench coats of that type are in the database) will decrease. If the quantity reaches zero, the trench coat will be deleted from the database
 - choose not to add the trench coat to the basket and to continue to the next. In this case, the information corresponding to the next trench coat is shown and the user is again offered the possibility to buy it. This can continue as long as the user wants, as when arriving to the end of the list, if the user chooses next, the application will again show the first trench coat
 - show shopping basket button: display the shopping basket in a table
 - show shopping basket externally button: display the shopping basket in a ```CSV``` or ```HTML``` format, depending on the user's choice

 ## Project Screenshots
 ### Choose the application mode window:
 <p align="center"> <img src="https://github.com/EmanuelPutura/TrenchCoatsManager/blob/main/img/choose_mode.png" height="500"/> </p>
 
 ### Admin mode window:
 <p align="center"> <img src="https://github.com/EmanuelPutura/TrenchCoatsManager/blob/main/img/admin_mode.png" height="500"/> </p>
 
 ### User mode window:
 <p align="center"> <img src="https://github.com/EmanuelPutura/TrenchCoatsManager/blob/main/img/user_mode.png" height="500"/> </p>
 
 ### Size statistics:
 <p align="center"> <img src="https://github.com/EmanuelPutura/TrenchCoatsManager/blob/main/img/statistics.png" height="500"/> </p>

 ### Shopping basket displayed in a table:
 <p align="center"> <img src="https://github.com/EmanuelPutura/TrenchCoatsManager/blob/main/img/show_basket.png" height="500"/> </p>

 ### Shopping basket displayed externally, in ```HTML``` format in this case:
 <p align="center"> <img src="https://github.com/EmanuelPutura/TrenchCoatsManager/blob/main/img/show_basket_externally.png" height="500"/> </p>
