#Agreagar migracio
add-migration AddConfiguration -Context BibliotecaDbContext


#aplicar migracion
Update-Database -Context BibliotecaDbContext

 
