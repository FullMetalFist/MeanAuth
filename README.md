## Synopsis

Authentication API backed by MongoDB

## Motivation

Side project to better understand authentication with Node.js


## Installation

Clone into your directory, type
`npm install`
then type
`node app.js`

Check status in MongoDB

```terminal
> show dbs
meanauth    0.000GB

> use meanauth
switched to db meanauth

> show collections
users

> db.users.find()
{ "_id" : ObjectId("596ba1d345fbc0bf8ae85001"), "name" : "JohnJohn", "email" : "dude@g.net", "username" : "Dude", "password" : "$2a$10$Qmm.l007BDoIio1t079AY.Y6RPFfTJsNXMlk83u3Pv/0SF7QKOfky", "__v" : 0 }
{ "_id" : ObjectId("596ba201d6d733bf92bdd5a0"), "name" : "EasyE", "email" : "Eaze@g.net", "username" : "EDude", "password" : "$2a$10$CbMT9t5Ak/8v7IdIzJNhZ.bZeb2t160CV/ACw.0eq5lTJYEVyjYUi", "__v" : 0 }
```


## API Reference

POST `localhost:3000/register`

POST `localhost:3000/authenticate`

GET `localhost:3000/profile`


## Lectures

Following Traversy Media for this project

- [x] [MEAN Stack Front To Back [Part 1] - Project Introduction](https://youtu.be/uONz0lEWft0)
- [x] [MEAN Stack Front To Back [Part 2] - Express Setup & Routes](https://www.youtube.com/watch?v=DQ9pZ2NKXRo)
- [x] [MEAN Stack Front To Back [Part 3] - User Model & Register](https://youtu.be/1ZeDy2QI3OE)
- [x] [MEAN Stack Front To Back [Part 4] - API Authentication and Token](https://youtu.be/6pdFXmTfkeE)
- [x] [MEAN Stack Front To Back [Part 5] - Angular 2 Components & Routes](https://youtu.be/zrViDpWiNVE)
- [x] [MEAN Stack Front To Back [Part 6] - Register Component, Validation & Flash Messages](https://youtu.be/bxZAPoeMr7U)
- [ ] [MEAN Stack Front To Back [Part 7] - Auth Service & User Registration](https://youtu.be/dFftMN32jyQ)
- [ ] [MEAN Stack Front To Back [Part 8] - Login & Logout](https://youtu.be/rt6VSxXL4_w)
- [ ] [MEAN Stack Front To Back [Part 9] - Protected Requests & Auth Guard](https://youtu.be/OILrJmjkId4)
- [ ] [MEAN Stack Front To Back [Part 10] - App Deployment to Heroku](https://youtu.be/cBfcbb07Tqk)

## Contributors

I'm on [Twitter](https://twitter.com/MVilabrera) &
       [StackOverflow](https://stackoverflow.com/users/2533857/fullmetalfist)
Any bugs or feature requests please send me an [issue](https://github.com/FullMetalFist/MeanAuth/issues/new)

## License

Copyright 2017 Michael Vilabrera

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
