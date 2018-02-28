Simple .gov template in php. 

index.php handles very simple routing. It sets a session variable of the value in the url then requires
master.php which pulls elements together to make the equired page. 

Inside the stylesheet folder is an image folder which is referenced in the css. Only way I could get these to display. 

The structure of the project uses an MVC (model, view, and controller). Pages and page elements go in the 'Views' folder,
'model' refers to objects and getting data from a data source, and controller is the business logic and code to move data
from the code in the 'model' to the view and vice versa.  