# ScaleUpNation App
This repo contains a frontend and backend for a ScaleUpNation Bussines App. It uses Typescript, Koa, routing-controllers and TypeORM in the backend and React/Redux in the frontend. The backend exposes a REST API. The app runs with yarn start on client side and nodemon dev on the server side.

_______________________________________________________________________________

### Installation:

Clone this repository. Run yarn to install all libraries.

on Server folder: Run 'yarn tsc' to compile. Run 'nodemon .' on the target folder.

on Client folder: Run yarn start to listen app on local port.

_______________________________________________________________________________

### List of features:

1. Upload CSV:

   After CSV upload, it adds new companies with all related info and updates the companies that already exist in database. Headers of CSV have to be as follow:

    Name;Source;Business;Location;Info

2. Manual changes on the table. Every change is saved and can be viewed in reports.

3. Track updates made to the database table. See changes over time as different types of graphs. See top ten list of companies based on percentage growth of FTE.

_______________________________________________________________________________

### Manual:

Log in with given credentials. In Homepage, choose one of the 3 routes (full data, reports, top companies).

List page -> See or update existing fields. Upload the csv file.

Reports page -> Fetch all the reports, or filter them by different factors. Once there you can plot the graphs for a better visualization (the more csv files uploaded the better representation of these graphs would be).

Top companies -> See a top list of the companies with the highest growth in percentage over a year based on the last recorded value and the first value recorded within one year.
