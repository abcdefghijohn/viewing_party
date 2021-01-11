## Viewing Party

Viewing Party in an application in which a user can access information about motion pictures from the database of [TheMovieDB](TheMovieDB.org).
By way of consuming various free API endpoints available on the TheMovieDB.org, Viewing Party can search for and render specific film information to users. Registered users can find other registered users and add them as friends. Registered users also have the ability to schedule and create a viewing party for any movie found on the database, and any friends of that user can be invited to the viewing party.

Viewing Party is live and running on Heroku [Here](https://guarded-refuge-05465.herokuapp.com)

## Group Members
[Carson Jardine](https://github.com/carson-jardine)

[John Kim](https://github.com/abcdefghijohn)

[Todd Estes](https://github.com/Todd-Estes)

## Versions

Ruby 2.5.3

Rails 5.2.4.3



## Local Setup

1. Fork and Clone the repo: https://github.com/Todd-Estes/viewing_party.git
2. Install gem packages: `bundle install`
3. Setup the database: `rails db:{create, migrate}`

## Schema

![alt text](https://user-images.githubusercontent.com/66448493/101704525-30729400-3a42-11eb-9614-2a2db85f750e.png)

## User Roles

**Visitor** - A visitor has the ability to keyword search for any film located on TheMovieDB.org, and they can also see the top 40 highest reviewed films located on the database, as well. Users can select an information page for any available film which includes the film's title, genre info, cast, average review, number of reviews, and individual reviewer information.

**Registered User** - A registered user has all of the capabilities of a regular visitor, with the additional abilities of searching and befriending other registered users and inviting them to scheduled viewing parties for any film on the database.

## Learning Goals

**Abstraction and Encapsulation**

-Created and utilized POROs, Facades, and Service Objects

**API Consumption**

-Called and rendered data from multiple API endpoints

-Utilized and followed basic HTML and CSS conventions to render view templates

**Authentication**

-Used Sessions for login/logout functionality

-Limited functionality to authorized users

-Used BCrypt to hash user passwords

## Screenshots

![image](https://user-images.githubusercontent.com/66448493/101707913-72eb9f00-3a49-11eb-9cec-ca1effb2a7d0.png)
===
![image](https://user-images.githubusercontent.com/66448493/101708358-500dba80-3a4a-11eb-9eac-e47814ef06e0.png)
===
![image](https://user-images.githubusercontent.com/66448493/101708212-08872e80-3a4a-11eb-81b5-d7babcd4de84.png)
===
![image](https://user-images.githubusercontent.com/66448493/101708437-77fd1e00-3a4a-11eb-969f-affe6b13ff7f.png)

## Acknowledgements
Special Thank You to the following:

Our Instructors:
* [Ian Douglas](https://github.com/iandouglas)
* [Dione Wilson](https://github.com/dionew1)


* [The MovieDB](TheMovieDB.org) for providing the movie data that is used in this application.
