# dockercompose-angular

Docker development environment for angular development

Run the following to set up:
```bash
git clone https://github.com/KrisGray/dockercompose-angular.git;
cd dockercompose-angular/server;
git clone https://github.com/KrisGray/<angular project>.git;
cd ..
docker-compose up --build
```
```bash
docker exec -it angular_webserver_1 bash
cd <angular project>
npm install;
exit
```

```bash
docker exec -it angular2_webserver_1 bash
```
