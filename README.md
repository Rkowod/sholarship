## About Scholarship

Scholarship is a web appliaction for graduation project which may facilitate all the services like request to get scholarship, extend, cancele , change supervisor and change fellowship and all these services has been transfer from manually process to electronic.

## Getting Started

- Clone the repository `git clone https://github.com/rkowod/scholarship.git`.
- Make a copy of `.env.example` as `.env`
- Run the following the project folder `docker-compose up`
- then run the following commands
    ```
    $ docker exec -it scholarship_php_1 sh
    $ php artisan migrate --seed
    ```

After that, you can navigate to http://localhost:5555

**Note:** Use this account to get all privileges

Email `admin@gmail.com`

Password `AdminScholarship`

## Snapshots of the web application


![Home page](https://github.com/rkowod/scholarship/blob/master/snapshots/Screenshot_1.png)


![Dashboard](https://github.com/rkowod/scholarship/blob/master/snapshots/Screenshot_2.png)


![User dashboard](https://github.com/rkowod/scholarship/blob/master/snapshots/Screenshot_3.png)


![Register to scholarship](https://github.com/rkowod/scholarship/blob/master/snapshots/Screenshot_4.png)
