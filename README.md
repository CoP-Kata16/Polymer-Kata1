Pasos Previos

	Crear una nueva carpeta y ejecutar:
	
	git clone https://github.com/CoP-Kata16/Polymer-Kata1.git

	Desde el directorio raíz del respositorio crear una carpeta con vuestros nombre para subirlo al repo.
	
Para consulta de comandos GIT:

	https://github.com/ejalarcon/Taller-Git

Práctica 1

	Crear el web component <custom-card>
	
		Constará de los siguientes elementos:
		
			- Un fichero index.html desde el cual se utilizará el componente creado
			- Un fichero custom-card.html donde estará definido el web component.
			- Fichero estilos.css donde guardaremos los estilos del componente.


Práctica 2

	- Crear el web component <bbva-weather>
	- Descargar imagenes que se van a utilizar el componente.

Constará de los siguientes elementos:

	- Un fichero index.html desde el cual se utilizará el componente creado
	- Un fichero bbva-weather.html donde estará definido un web component con el mismo nombre.
		* Nuestro compoente utilizará el web component de polymer <iron-image>, para poner una imagen de background
		en función de la consulta a una API Rest.
		* La consulta de la API Rest se hará mediante el web component de polymer <iron-ajax> 

	- Un fichero bbva-current.html donde se creará otro web component con el mismo nombre del fichero.
		* Este compoente utilizará el web component de polymer <paper-styles>
		* Obtendremos los datos de humedad,temperatura, descripción y ciudad del componente  <bbva-weather>
	 
Url API rest:

		http://api.openweathermap.org/data/2.5/weather?lat=37.779827&lon=-3.7929867&units=metric&lang=es&appid=44db6a862fba0b067b1930da0d769e98

Práctica 3

	- Crear un nuevo componente <bbva-forecast> que nos diga la previsión del tiempo en 15 días.

Url API rest:

		http://api.openweathermap.org/data/2.5/forecast/daily?lat=37.779827&lon=-3.7929867&cnt=7&mode=json&units=metric&lang=es&appid=44db6a862fba0b067b1930da0d769e98








