![](https://img.shields.io/badge/Microverse-blueviolet)

# Vet-clinic-database-database-performance-audit

> Optimize slow queries in the database.

## Built With

- PostgreSQL

## Screen Shots

### explain analyze SELECT COUNT(*) FROM visits where animal_id = 4;

#### Before 

![1](https://user-images.githubusercontent.com/24830039/155482381-244bc431-23ef-4fff-80f2-4950989db3a1.png)

#### After 

![Kazam_screenshot_00004](https://user-images.githubusercontent.com/24830039/155482531-6a60a80d-9680-40b5-9691-ab7c2122d2bb.png)

### explain analyze SELECT * FROM visits where vet_id = 2;

#### Before

![2](https://user-images.githubusercontent.com/24830039/155482699-60c40856-7c1a-41c7-899d-4deb4ab393c8.png)

#### After

![Kazam_screenshot_00005](https://user-images.githubusercontent.com/24830039/155482759-3fb4a3f3-af26-49a4-ac7a-6a3463d8d79b.png)

#### explain analyze SELECT * FROM owners where email = 'owner_18327@mail.com';

#### Before

![3](https://user-images.githubusercontent.com/24830039/155482883-d2cbb53f-f29b-4ec0-887d-44b973d44c16.png)

#### After

![Kazam_screenshot_00006](https://user-images.githubusercontent.com/24830039/155482912-1aedc500-fd5c-4621-a0e5-a15fbe62044b.png)


## Authors

👤 **Tshephang Mampa**

- GitHub: [tmampa](https://github.com/tmampa)
- LinkedIn: [Tshephang Mampa](https://linkedin.com/tshephangmampa)
- Twitter: [Tshephangm\_](https://twitter.com/tshephangm_)

👤 **Author2**

- GitHub: [@od-c0der](https://github.com/od-c0d3r)
- LinkedIn: [Omar Rashad](https://linkedin.com/in/omarrashad)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration
- etc

## 📝 License

This project is [MIT](./MIT.md) licensed.
