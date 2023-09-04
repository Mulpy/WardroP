Rails app generated with [lewagon/rails-templates](https://github.com/lewagon/rails-templates), created by the [Le Wagon coding bootcamp](https://www.lewagon.com) team.
Project description goes here

This app was created as part of a student exercise for the Le Wagon Tokyo Web Development Bootcamp. The project was an AirBnB clone to design a website that specialized in clothes rentals.  Apparel owners can view and approve/reject rental requests.  Rentees can mark whether the rented item was successfully delivered. 

_DROP SCREENSHOT HERE_
<br>
App home: https://wardrop-f993abaafe8e.herokuapp.com
   

## Getting Started
### Setup

Install gems
```
bundle install
```

### ENV Variables
Create `.env` file
```
touch .env
```
Inside `.env`, set these variables. For any APIs, see group Slack channel.
```
CLOUDINARY_URL=your_own_cloudinary_url_key
```

### DB Setup
```
rails db:create
rails db:migrate
rails db:seed
```

### Run a server
```
rails s
```

## Built With
- [Rails 7](https://guides.rubyonrails.org/) - Backend / Front-end
- [Stimulus JS](https://stimulus.hotwired.dev/) - Front-end JS
- [Heroku](https://heroku.com/) - Deployment
- [PostgreSQL](https://www.postgresql.org/) - Database
- [Bootstrap](https://getbootstrap.com/) — Styling
- [Figma](https://www.figma.com) — Prototyping

## Acknowledgements
The Le Wagon Tokyo Teaching Staff

## Team Members
- [Gary Topping](www.linkedin.com/in/gary-topping)
- [Alvin (Ken) Yau]()
- [James Lau]()
- [Ritsuki Toshima]()

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
