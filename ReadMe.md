## Demo Blog App

### Created with React.js and ASP.NET Core

- To Run the Project you need to <code>git clone</code> this repo
- cd into the 'demoblog' directory and run <pre>dotnet run</pre>

### Requirements

- Dotnet SDK 7.0
- Git
- Node.js 

### How the Project is Built

#### Backend 

- The project is build with ASP.NET Core, which includes Models, Controllers and some Configurations in Program.cs. 
- The Backend Routes are Proxied using the '/api' context, and thus endpoints are respectively '/api/contacts', '/api/articles'
- The Database Used is Entity Framework, and it was configured by adding the appropriate packages and two Context Files for Articles, Contacts. And These Context Files were registered in Program.cs


#### Frontend

- The Frontend has a proxy setup file which points to the context, api, and has the appropriate Create React App structure.
- The <code>src</code> directory has all the components and respective pages, which is mainly centered around the App page.


#### Testing Notes

- To Create additional articles, you can use /api/articles POST with the appropriate body.

Enjoy using the App!
