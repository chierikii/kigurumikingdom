Rails app generated with [lewagon/rails-templates](https://github.com/lewagon/rails-templates), created by the [Le Wagon coding bootcamp](https://www.lewagon.com) team.
# 🐼 Kigurumi Kingdom

-Project-
We connect individuals with the colorful and charismatic mascots they love. We strive to create a community where fans and enthusiasts can easily discover, interact with, and learn more about these beloved characters through our user-friendly platform. Our ultimate goal is to create joy and cultural awareness by fostering meaningful connections between people and their favorite mascots.

<img width="1679" alt="Screenshot 2023-03-13 at 4 36 00 PM" src="https://user-images.githubusercontent.com/52782804/224636441-015e5d92-25c7-40ae-be4a-dd4f99f9fcfc.png">
<img width="1680" alt="Screenshot 2023-03-13 at 4 36 23 PM" src="https://user-images.githubusercontent.com/52782804/224636466-14d9ea45-eab0-4a29-b796-bdf6c22ee807.png">
<img width="1678" alt="Screenshot 2023-03-13 at 4 37 01 PM" src="https://user-images.githubusercontent.com/52782804/224636501-9bb07db3-79fe-4412-a39e-10f4bbdf621d.png">

<br>
App home: https://kigurumikingdom.herokuapp.com/
   

## Getting Started
### Setup

Install gems
```
bundle install
```
Install JS packages
```
yarn install
```

### ENV Variables
Create `.env` file
```
touch .env
```
Inside `.env`, set these variables. For any APIs, see group Slack channel.
```
CLOUDINARY_URL=your_own_cloudinary_url_key
MAPBOX_API_KEY=your_own
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

## Team Members
- [Jim Deeth](https://github.com/MosDeef)
- [Gilary Bacnis](https://github.com/gillaryb)
- [Anri Tomita](https://github.com/Anri009)
- [Chieri Kii](https://github.com/chierikii)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

