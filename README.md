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
	
<!-- Generated with glade 3.18.3 -->
<interface>
  <requires lib="gtk+" version="3.12"/>
  <object class="GtkListStore" id="SFL01">
    <columns>
      <!-- column-name col_nom -->
      <column type="gchararray"/>
      <!-- column-name col_text -->
      <column type="gchararray"/>
      <!-- column-name col_typ -->
      <column type="gchararray"/>
      <!-- column-name col_len -->
      <column type="gint"/>
      <!-- column-name col_dec -->
      <column type="gint"/>
    </columns>
  </object> ........


  GtkBuilder *builder = gtk_builder_new_from_string (
"<interface>"
"  <requires lib='gtk+' version='3.12'/>"
"  <object class='GtkListStore' id='SFL01'>"
"    <columns>"
"      <!-- column-name col_nom -->"
"      <column type='gchararray'/>"
"      <!-- column-name col_text -->"
"      <column type='gchararray'/>"
"      <!-- column-name col_typ -->"
"      <column type='gchararray'/>"
"      <!-- column-name col_len -->"
"      <column type='gint'/>"
"      <!-- column-name col_dec -->"
"      <column type='gint'/>"
"    </columns>"
"  </object>"........

"</interface>",
-1);

