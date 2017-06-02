# dockercompose-angular

Docker development environment for angular development

Run the following to set up:
Use [angular-hero-tutorial](https://github.com/KrisGray/angular-hero-tutorial) as an example project below
```bash
git clone https://github.com/KrisGray/dockercompose-angular.git;
cd dockercompose-angular/server;
git clone https://github.com/<angular project>.git;
cd ..
docker-compose up --build
```
```bash
docker exec -it dockercomposeangular_webserver_1 bash
cd <angular project>
npm install;
ng --version
ng serve
```

To check out the working project go to http://localhost:4200
