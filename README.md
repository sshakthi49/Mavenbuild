This was added in Branch1.

HelloWorld Servlet example with corresponding Dockerfile

Use Maven Build first to create war file in Target folder.

mvn clean package

"From Branch-1"

docker build -t mavenbuild .

Once this is done u will be see image using docker image

Use below command to run the container

docker run -d -p 8080:8080 --name dockercontainer mavenbuild

This was added from Branch-2

This was added directly in the GITHUB

Added again from GITHUB
