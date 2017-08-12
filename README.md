
oc login
oc new-project spring-boot-jwt
oc new-app codecentric/springboot-maven3-centos~https://github.com/antoniosignore/jwt_demo.git
oc get services
oc expose service jwtdemo
