# Metrics App
_Developer: Chandima Jayasiri (chandimaj@icloud.com)_

<br>
<br>

## Content

This repo contains two versions of the front end apps created using React Material UI framework
[link to online demo](https://metricsapp-factorial.web.app/)
<br>
<br>

## Metrics React App using Ruby on Rails and MySql as a backend api service

### Installation

#### React Application

1. Copy the `metrics_reactapp_onrails` folder
2. Install required node modules `npm install`
3. Start the node server `npm start` or `yarn start`
4. The app should be accessible at the default generated url
5. To connect with the services api, modify api_host url at `metrics_reactapp_onrails/src/Settings/apiSettings.js`

#### Backend Api service Rails app

1. Copy the `metrics_services_rubyapp` folder
2. Configure database settings on `config/database.yml`
3. Install missing gems if needed `$ bundle i`
2. Start the rails server `rails s` or `rake s`
3. The app should be accessible at the default generated url
4. To populate with sample data run `rails db:migrate` and `rails db:seed`. 
The sample data generator can be accessed at `db/seeds.rb`
5. To permit incoming api request (CORS) Modify `config/initializers/cors.rb` to permit the app requests
<br>
<br>
<br>

### React Application using node and local storage for backend service
1. Copy the `metrics_reactapp_onnode` folder
2. Start the node server `npm start` or `yarn start`
3. The app should be accessible at the default generated url
