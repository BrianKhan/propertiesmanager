This class is used for loading properties from XML files that can
 then be used throughout an application. Note that this class is
 a singleton, and so can be accessed from anywhere. To get the
 singleton properties manager, just use the static accessor:
 
 PropertiesManager props = PropertiesManager.getPropertiesManager();
 
 Now you can access all the properties it currently stores using
 the getProperty method. Note that the properties_schema.xsd file
 specifies how these files are to be constructed.