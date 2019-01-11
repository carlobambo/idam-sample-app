# Terega IDAM Third Party Demo App

![Terega logo](https://www.terega.fr/wp-content/uploads/2018/03/terega-main-logo-2.svg =224x47)

Static HTML file with CDN assets for public API demo.


## Demo
This tests file upload and search APIs. To test, please visit [the demo site](https://terega-idam-thirdparty.herokuapp.com "Demo site").

## Local
You can run and test this locally. First, clone this repository.

    $ git clone git@bitbucket.org:Wizyio/idam-thirdparty.git

Then, install the packages

    $ npm install

Edit line 11 of `views/pages/index.ejs`

```javascript
    const apiHost = '[THE_TEREGA_API_HOSTNAME]';
```

You may also use the `localhost:8082` if you also cloned the Terega IDAM api repository

Then, run the server

    $ npm start

The server will serve to `http://localhost:5000`

Open the app on your browser, follow the instructions there and you can now use the APIs.

## Copyright
The Terega and the Terega logo are properties of Terega. No copyright infringement intended.
