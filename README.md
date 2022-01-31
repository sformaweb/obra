# Demo de obra

1. Creación da database "obra" e táboas de proba "usuarios" (funcionarios) e "persoas" (individuos que se rexistrarán no SOL) utilizando phpmyadmin.
2. En cada unha das táboas decídense os campos (columnas) a cubrir, no caso de "persoas" son unha aproximación aos campos que se corresponderían cos do formulario de entrada da app.
3. Dentro da táboa "usuarios" créanse 3 entradas (tamén mediante phpmyadmin), que representan posibles traballadores do SOL con acceso á aplicación.
4. Antes de nada, é necesario instalar algúns paquetes no proxecto: npm, bootstrap, parcel e popper, para obter ditas dependencias de funcionalidade.
   - Coma sempre, facemos un .gitignore para non subir ao repositorio os arquivos innecesarios.
   - Tamén creamos os arquivos style.scss (estilos) e index.php (primeira pantalla de datos).
   - E facemos algúns cambios nas rutas de package.json para que se cree unha carpeta "build", que representará o contido da app.
5. Unha vez iniciada a base de datos e as dependencias do proxecto, comezamos a construir o esquelete de programación da app:
   - Primeiro é imprescindible un php de conexión coa base de datos "obra", seguido dun formulario de login onde se identifican os usuarios e iníciase a sesión.
   - No index.php incluimos un 'require' á conexion.php, un pequeno formulario de búsqueda por nome e unha parte con html para a saída dos datos da base "persoas" por pantalla.
   - Se o login funciona cos usuarios creados, obtemos unha pantalla na que podemos incluir novas "persoas" cun formulario no que os campos a cubrir corresponden coas columnas da      táboa "persoas" (nuevo.php).
   - Ademais, créanse os arquivos php coas funcións de gardar, modificar, eliminar e actualizar rexistros de persoas, adaptados sempre aos campos da táboa.
6. 
