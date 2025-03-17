# 📚 Parker's Cafe Scramble

Ongoing project made with React. Search for cafes around Tokyo and add your favorites to an ever-growing list!
![parkerscafescramble home](https://github.com/user-attachments/assets/04ce5eae-c359-4069-ab5b-75a79f9340d8)


<br>
App home: http://127.0.0.1:5173/react-workshop/
   

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
Inspired by my friend's obsession with coffee. I wanted to create an app that would help him find what he needs whenever he visits me in Tokyo. Mainly to save time deciding on which cafe to go haha.

## Team Members
- Jason R. Rocha(https://www.linkedin.com/in/jason-rocha-37188a150/)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License
