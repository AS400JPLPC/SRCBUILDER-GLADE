# SRCBUILDER-GLADE
* .glade to * .hpp file conversion



	cerr <<"Options:" << endl;
	cerr <<"-h -H,--help                        Show this help message" << endl;
	cerr <<"-p -P,--path           Path......   Specify the path" << endl;
	cerr <<"-f -F,--file           File......   specify the file" << endl; 
	
	cerr <<"\nex: -p \"/home/xxx/GTK/\"  -f \"DYSPLAY\" " << endl;







	srcbuilder   /myPath/   myFile  conversion automatique

	out > myFile.glade to myFile.hpp

	ex:
	<?xml version="1.0" encoding="UTF-8"?>
	
	voir exemple DDSREP.glade  to DDSREP.hpp

	GtkBuilder *builder = gtk_builder_new_from_string (
.......
,
-1);

