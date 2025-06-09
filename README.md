# 📚 Tokyo Turntable

Tokyo Turntable is a mobile web-app that helps users find shows to go to in the Tokyo area. It webscrapes venues and show listings, then it automatically pairs the bands to spotify so you can hear what they sound like. 

![image](https://github.com/user-attachments/assets/decf20b3-5022-41ed-bc70-5bd126fd1f22)
<br>
App home: www.tokyoturntable.com
   

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
We webscraped www.tokyogigguide.com for this student project, and appreciate the work they have done to actually connect people to live shows in Tokyo for over 20 years. 

## Team Members
- [Will Sebastian](https://github.com/MaddRussian)
- [Julian Schoenfeld](https://github.com/carved-duck)
- [Hikari Hashiguchi](https://github.com/hikari-h)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License
