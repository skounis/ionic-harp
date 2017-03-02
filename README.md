# Ionic Harp
A static NodeJS webserver for Heroku, with **Ionic** in mind!

## Web content / Ionic `www`
Copy the content of the `www` folder of your **Ionic Application** into the `www` folder.

## Local
Install dependencies `npm install` and run the server `harp server www`. You should get something similar to:
```
------------
Harp v0.23.0 – Chloi Inc. 2012–2015
Your server is listening at http://localhost:9000/
Press Ctl+C to stop the server
------------
```
Open your browser and navigate to http://localhost:9000

## Heroku

Create a new Heroku application, eg: `ionic-harp`.

Navigate to the **Deploy** tab and select **GitHub** as the deployment method.

Search for your Github repo where your version of this repo is forked to, eg: `skounis/ionic-harp`, and select **Connect**.

Enable Automatic Deploys for your `master` branch.

Commit your changes in your GitHub repo and then open the URL of your Heroku App.
