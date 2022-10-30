
events {}

http{
   includes mime.types;
   
   server{
   listen 80;
   server_name name.example.com;
   
   root /sites/demo;
   }

}
