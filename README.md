# Facebook_Authentication

Simple facebook authentication app in Node adn express

## Steps

### create App-id and paste

link : https://developers.facebook.com/apps

In below code, replace {your-app-id} with your created appId

```
  window.fbAsyncInit = function() {
  FB.init({
    appId      : '{your-app-id}',
    cookie     : true,  // enable cookies to allow the server to access
                        // the session
    xfbml      : true,  // parse social plugins on this page
    version    : 'v2.8' // use graph api version 2.8
  });
  ```
### Run code

>node index.js
