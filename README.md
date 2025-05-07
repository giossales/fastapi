# FastAPI

Build your FastAPI image:
´docker build -t myimage .´

Run the container:
´docker run -d --name mycontainer -p 80:80 myimage´

Check it on the container's URL:
´http://127.0.0.1/items/5?q=somequery´

To view the API documentation, access:
 ´http://127.0.0.1/docs´
