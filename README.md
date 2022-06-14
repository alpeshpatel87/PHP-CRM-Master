# PHP-CRM-Master
Laravel 8 project for managing freelance projects, notes and income


Features:
- CRUDs for Clients, Projects, Notes, Documents and Transactions
- Simple Report for Income per Month
- CRUDs for Settings - Currencies, Transaction Types, Client/Project Statuses
- Based on [AdminLTE 3 Free Theme](https://adminlte.io/themes/dev/AdminLTE/index.html)


## How to use

- Clone the repository with __git clone__
- Copy __.env.example__ file to __.env__ and edit database credentials there
- Run __composer install__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- That's it: launch the main URL and login with default credentials __admin@admin.com__ - __password__

## License

Basically, feel free to use and re-use any way you want.

---
