# Angular

This project was generated with [angular-cli](https://github.com/angular/angular-cli) version 1.0.0-rc.1.

## Development server
First you have to install [angular-cli](https://github.com/angular/angular-cli).

#angular-laravel
- First clone via `git bash` or download.
- Go to your root folder and run this command
```
npm install
```
- After `npm install` again run this command to install `bootstrap, tether and jquery`
```
npm install bootstrap@next
```
- Download [laravel-api](https://github.com/eliyas5044/laravel-api), which i used as a RESTful api.
- Run your `angular` app by this command
```
ng serve -o 
```
(for my case) type :  "npm start"

(in your laravel folder)
run your `laravel` api by this command
```
php artisan serve
```
You will see this app will load data from your api.

and 

to prevent porting get cancelled by used port : 
references : http://stackoverflow.com/questions/39091735/port-4200-is-already-in-use-when-running-the-ng-serve-command/42896146#42896146

(example) 
```
netstat -ano | findstr :4200
taskkill /f /PID 11096
```
Enjoy!