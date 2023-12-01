# arduino-docker-serial-test




    cd <repo dir>
    docker build -t my-image .

 to run


    docker run -d -p 80:80 --name my-container my-image
or

    docker run -d -p 80:80 --name my-container -v $(pwd):/code my-image



