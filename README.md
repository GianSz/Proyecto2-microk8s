Al hacer el deployment de la base de datos daba error de permisos, se tuvo que hacer estos comandos en el nfs server:
sudo chown -R 999:999 /path/to/nfs/directory
sudo chmod -R 777 /path/to/nfs/directory
