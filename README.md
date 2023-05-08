In order to begin the console, you can run either python3 console.py or ./console.py in the command line.

Classes that are currently supported include BaseModel, User, City, State, Amenity, Review, and Place.

The console currently supports the following commands:

create <class name>, which will create an object of the class declared by user;
show <class name> <id>, which will display the object information if it exists;
destroy <class name> <id>, which will delete the object if it exists;
all <class name>, where the class name input is optional and the console will display all instances, or all instances of a specified object;
update <class name> <id> <attribute name> <attribute value>, whilch will update an instance attribute of a previously declared object.
Additionally, the console also supports the following command formats:

<class name>.all(), which will display all instances of the specified class;
<class name>.count(), whilch will display the number of instances of the specified class;
<class name>.show(<id>), whilch will display the instance with correct id and class;
<class name>.destroy(<id>), which will delete the instance with correct id and class;
<class name>.update(<id>, <attribute name>, <attribute value>), which will update an instance of the given class and id with the new attribute;
<class name>.update(<id>, <dictionary representation>), which will update an instance of the given class and id with a dictionary of key value pairs that will be new attributes for the objects.
**<class name>.create(=) create an instance of the class
