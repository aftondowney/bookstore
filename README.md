# _The Dusty Jacket Bookstore_

#### A website for a small bookstore written in Drupal  | April 22, 2016

#### By: Afton Downey

## Description

This website is for a small bookstore. Users can sign up to leave book reviews. They can also contact the site administrator with a contact form. They can view the most recent 3 book reviews.

## Prerequisites

You will need the following things properly installed on your computer:<br>
• [Drupal](https://www.drupal.org/project/drupal)<br>
• [MAMP] (https://www.mamp.info/en/)

## Setup/Installation Requirements

1. Open Terminal and clone this repository: https://github.com/aftondowney/bookstore.git
2. In your browser navigate to ```http://localhost:8888/phpmyadmin```, here is where you can select the Import tab and in the project directory go to ```sites > db-backups > bookstore.sql(6).zip``` and click GO at the bottom of your screen
3. Also in phpmyadmin, recreate the user you created initially in the database (username: book_admin and password: book, can also be found in the settings.php file)
4. Open MAMP, select ```Preferences```, select ```Web Server``` tab, direct the ```Document Root``` at the top level of your project folder
5. Navigate to ```http://localhost:8888```
6. Login as user:admin pw:password

## Known Bugs

N/A

## Support and Contact Details

If you have any issues, questions, ideas, or concerns contact me through GitHub. If you would like to make a contribution to the code, feel free to do so and notify me by e-mail.

## Technologies Used

• Drupal<br>
• phpMyAdmin<br>
• PHP<br>
• GIT<br>

## License

Copyright (c) 2016  |  Afton Downey  |  Epicodus  |  Portland, OR
