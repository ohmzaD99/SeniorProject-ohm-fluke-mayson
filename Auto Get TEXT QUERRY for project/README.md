Ok , this sub project is about to Auto Query from 
  >> create (Database) and (Table) by Google Doc name DB Project , this fiel contain all of database both KMUTT DB and my project DB(Rule config DB , data wherehouse DB)
in the document have component of detail DB, property of for each table , descripion , primary key , and data type and have SQL script for create DB and table.
  >> and full fill of source by Google sheet for each file(file similar database) and for each sheet ( sheet similar table )
this project just get file from DB Project to create Database and table and get file from divers Google Sheet for full fill DB source , read file and get script SQL to Auto generate Script for querry DB

Please use quickstart file only in this project for generate(another file .py is another problem) 

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
DATABASE ALL -> Folder -> File

File in folder  DATABASE ALL Folders :
  >   DB_Detail_Field ( ID : ) the folder contain fileDocument :  
      > DB Project( ID: ) Google Doc file contain detail of DB and table and script
  >   DB_Table_Source_full
      > contain source of all KMUTT DB but some file havn't contain the source
  >   DB_Table_Source_MockUp (ID : ) contain source of KMUTT MockUp DB , contain the file Google Sheet  (for each file similar Database)
      >HPB
      >NewAcis
      >KIRIM
      >MODlINK
      >EDS
      >KMKUTT
      >OTHER      
  > and last DB_Table_MyProject_WhereHouse, about the source of  Database that my DB contain it
      >configuration rule DB , this file Google Sheet contain a source of rule
      >DB Wherehouse , this dB doesn't have the source because the sourse of this DB just come from query from DB_Table_Source_MockUp 


