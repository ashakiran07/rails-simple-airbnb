## Simple AirBnB-like Rails Application
This Rails application is designed to resemble Airbnb, allowing users to browse a list of flats and perform basic CRUD operations. Below are the key features and components of the application:

## 1. Home Page:
   
 ## Index
![p1](https://user-images.githubusercontent.com/45171753/166428794-9a6a4ea0-99a8-456d-b548-b475e57e4c9b.png)

Upon visiting the application, users are greeted with a home page displaying a list of available flats.
Each flat is represented with essential details such as title, description, price, location, and an image.

## 2. Flat Listings:

Users can browse through the list of flats to find the one that suits their preferences.
The flats are initially seeded into the database to provide users with a starting list.

## Search engine (Active record)
![p2](https://user-images.githubusercontent.com/45171753/166428800-559fa644-bad6-4bb3-b52f-e939b75672f0.png)

## 3. CRUD Operations:

Create: Users with appropriate permissions (admin or registered users) can add new flats to the listing. They can provide details such as title, description, price, location, and upload an image.
Read: Users can view detailed information about each flat by clicking on its listing. They can see the full description, location, price, and images associated with the flat.
Update: Authorized users can edit the details of existing flats. They can modify the title, description, price, location, and replace the images.
Delete: Users can also delete flats from the listing if they are no longer available or relevant.

## Show
![p3](https://user-images.githubusercontent.com/45171753/166428803-0702cf89-6caf-42d6-9053-35a7368d4e80.png)

## Edit Form
![p4](https://user-images.githubusercontent.com/45171753/166428809-f2bab60b-1246-410e-9dbd-ffa7e7cf5de2.png)

## 4. Seed Data:

To provide users with an initial set of flats to browse, the application is seeded with a predefined list of flats. These flats contain realistic data to simulate a real-world scenario.

## Seed
![p5](https://user-images.githubusercontent.com/45171753/166428825-0de01649-9c4c-4492-b7e3-13ebdb3f1b53.png)

## 5. Deployment:

The application can be deployed to a hosting service such as Heroku for public access, allowing users to interact with the flats listings online.

## 6. Technologies
This project was created with:

 - [Ruby](https://www.ruby-lang.org/pt/)
 - [Rails](https://rubygems.org/gems/rails)
 - [ERB](https://ruby-doc.org/stdlib-2.7.1/libdoc/erb/rdoc/ERB.html) (for template system with Ruby)
 - [Pry-byebug](https://rubygems.org/gems/pry-byebug/versions/3.4.0?locale=pt-BR) (for debugging)
 - [Bootstrap](https://getbootstrap.com/)
 - Simple_form
 - Postgresql
   
## 7. Future Enhancements:

Additional features such as user reviews, search functionality, and booking management could be implemented in future iterations to enhance the user experience further.
