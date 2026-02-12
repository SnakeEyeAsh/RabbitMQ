Probar el procesamiento de peticiones con un curl como el adjunto 
Invoke-RestMethod -Uri http://localhost:3000/comprar -Method Post -ContentType "application/json" -Body '{"id": 101, "producto": "Teclado", "email": "alumno@escuela.com"}'
