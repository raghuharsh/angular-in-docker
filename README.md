1. This is a dockerized Angular Starter Project

2. To run the sample code, do the following:

    Go to the directory which contains the Dockerfile
    Run the following commands in the terminal/command line:    
    - docker build -t angular:starter .
    - docker run -v ${PWD}:/app -v /app/node_modules -p 4200:4200 --rm angular:starter
    
3. Go to http://localhost:4200/ in your browser to view it.