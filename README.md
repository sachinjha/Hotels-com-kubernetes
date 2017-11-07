# The Hotels Microservices journey

This a micro services example the team is developing.


### Deploy Hotels Microservices as Cloudfoundary apps on Bluemix
* [Deploy your own Hotels Microservices with IBM DevOps Toolchain](TOOLCHAIN-README.md)

> [![Deploy To Bluemix](./.bluemix/create_toolchain_button.png)](https://console.ng.bluemix.net/devops/setup/deploy?repository=https%3A%2F%2Fgithub.com%2Fkalyani75%2FHotels-com.git&cm_mmc=github-readme--native-_-acme-_-create-toolchain&cm_mmca1=000019RT&cm_mmca2=10004796)


hotels-event-create pipeline and hotels-onboarding-ui pipeline require API\_KEY  and API\_SECRET in order to make the API calls to generate events for onboarding of hotels. These values can be obtained by registering as a consumer in API Connect developer portal and subscribing to the Events API. 

Once the API\_KEY  and API\_SECRET values are obtained, one should update the configuration parameters in Deploy Stages of these pipelines and restart them. This will successfully deploy the openwhisk actions and onboarding-ui application.


### Deploy Hotels Microservices as containers in Kubernetes Cluster on Bluemix
> [![Deploy To Bluemix](./.bluemix/create_toolchain_button.png)](https://console.ng.bluemix.net/devops/setup/deploy?repository=https%3A%2F%2Fgithub.com%2Fsachinjha%2FHotels-com-kubernetes.git&cm_mmc=github-readme--native-_-acme-_-create-toolchain&cm_mmca1=000019RT&cm_mmca2=10004796)
