to build:<br>
docker build -t dizzzm/coding/devops/nodeappweb:v1 <br>

to run:<br>
docker run -d -m="512m" --cpu-period=100000 --cpu-quota=50000 -p 80:80  dizzzm/coding/devops/nodeappweb:v1<br>

to push the image to docker hub:<br>
docker push dizzzm/coding/devops/nodeappweb:v1<br>
