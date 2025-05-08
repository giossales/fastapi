# FastAPI

Build your FastAPI image:  
`docker build -t myimage .`  

Run the container:  
`docker run -d --name fastapicontainer -p 80:80 myimage`  

Check it on the container's URL:  
`http://127.0.0.1/`  

To view the API documentation, access:  
`http://127.0.0.1/docs`

To run it anytime:  
`sudo docker start fastapi_container`  

Then access:  
`http://localhost:8080`  
`http://localhost:8080/docs`  
