## File Share

A web application to **share files** on the internet **securely**. 

**Technologies** : NodeJS, MongoDB

### Features  

+ You can use the web application to share a file with someone over the internet.

+ You can securely share the file by adding a password, so that when the user opens the link, they must enter the same password that you used to download the file.

+ Once the file is downloaded by the user, it is deleted from the server. As a result, no data will be saved.


### Steps to run the project 

1. Create .env file and store the link to MongoDB Database and Port Number . 

```
DATABASE_URL=mongodb-connection-link
PORT=3000
```

2. Install all dependencies 

```
npm i 
```

3. Run the project 
```
npm start
```

### Demo 

![Project-video](/Project-demo/file-share.gif)

