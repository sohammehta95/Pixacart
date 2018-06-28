# Pixacart
An online marketplace for people to buy and sell their phone-clicked photos

Technologies and Tools:   
NodeJS, MondoDB , Express, Passport (Authentication), Mongoose, Express-Session, Connect-Flash (Flash Msgs), Heroku (Deployment), CloudFlare (Routing + SSL), Google Cloud API, Cloudinary (Media on Cloud), mLab (Mondo on Cloud), Nodemailer (Email Verification)

## Live Demo

Link: https://www.pixacart.com

![Pixacart](/imgs/main.png)



## Features

### Authentication:
  
  * User login with username and password

  * Admin sign-up with admin code

### Authorization:

  * One cannot manage posts and view user profile without being authenticated

  * One cannot edit or delete posts and comments created by other users

  * Admin can manage all posts and comments

### Manage photo posts with basic functionalities

  * Create, edit and delete posts and comments

  
### Search existing campgrounds

* The user is able to search of specific campgrounds based on keywords


### Upload campground photos

* The photos can be uploaded by the user and are stored on cloud with the service of Cloudinary.

### Google Cloud Maps API

The location entered by the user in plain text is geolocated by the Google maps API

### Password Reset with Mail Configuration

The user can reset the password by getting a mail with the reset link.

### Flash Notification Message

* Flash messages responding to users' interaction with the app

* Responsive web design

### Updating Posts and Profule

* Update campground photos when editing campgrounds

* Update personal information on profile page


### Clone or download this repository

```sh
git clone https://github.com/sohammehta95/Pixacart.git
```

### Install dependencies

```sh
npm install
```

or

```sh
yarn install
```

## Technologies Used

### Front-end

* [ejs](http://ejs.co/)
* [Google Maps APIs](https://developers.google.com/maps/)
* [Bootstrap](https://getbootstrap.com/docs/3.3/)

### Back-end

* [express](https://expressjs.com/)
* [mongoDB](https://www.mongodb.com/)
* [mongoose](http://mongoosejs.com/)
* [async](http://caolan.github.io/async/)
* [crypto](https://nodejs.org/api/crypto.html#crypto_crypto)
* [helmet](https://helmetjs.github.io/)
* [passport](http://www.passportjs.org/)
* [passport-local](https://github.com/jaredhanson/passport-local#passport-local)
* [express-session](https://github.com/expressjs/session#express-session)
* [method-override](https://github.com/expressjs/method-override#method-override)
* [nodemailer](https://nodemailer.com/about/)
* [moment](https://momentjs.com/)
* [cloudinary](https://cloudinary.com/)
* [geocoder](https://github.com/wyattdanger/geocoder#geocoder)
* [connect-flash](https://github.com/jaredhanson/connect-flash#connect-flash)

### Platforms

* [Cloudinary](https://cloudinary.com/)
* [Heroku](https://www.heroku.com/)
* [Cloud9](https://aws.amazon.com/cloud9/?origin=c9io)

## License

#### [MIT](./LICENSE)