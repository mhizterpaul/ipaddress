Simple Server Application

takes a query string in the format 
http://localhost:8080/api/hello?visitor_name=Paul
and returns 
{
    client_ip: 'ip address'
    location: 'user location'
    greeting: `Hello, ${name}! the temperature is ${temperature} degrees Celcius in ${city}
}

you can fork the code 
run npm install
run npm build 
the server should be running at localhost:8080