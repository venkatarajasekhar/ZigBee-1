CC2530DB/SensorDemo.eww is the workspace file which defines the project path and different compile setting for this project;
CC2530DB/SensorDemo.ewp is the project file which descripts the source files, compile option and other setting for this project; the change to the IDE will be written into this file;
source directory is the source files.

ATTENTION: I assume the Z-Stack is put in C:\Texas Instruments\ZStack-CC2530-2.5.1a which represents by the system enviroment variable %Z_HOME%, you can use it in *.ewp file under option tags, for tags file you must use the whole path. I don't why.

after compile and link, IDE will generate 
1.file directories:CollectorEB/SensorEB where obj and image files will be put; 
2.file directories settings where C-SPY files be put;
3.SensorDemo.dep which is source file dependent files;