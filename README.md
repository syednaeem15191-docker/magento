# magento

#### `docker login -u ${DOCKER_USERNAME} -p ${DOCKER_PASSWORD}`

##### push lumen 9
* `docker-compose up --build -d magento2`
* `docker tag lumen_lumen9 syednaeem15191/magento2`
* `docker push syednaeem15191/magento2`
* `docker tag lumen_lumen8 syednaeem15191/magento2`
* `docker push syednaeem15191/magento2`
* `docker-compose stop`
