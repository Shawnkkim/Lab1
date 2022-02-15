# ENGO 551 Lab1 - Beom Sae (Shawn) Kim 

This project is building a book review webiste where users will be able to register for the website with their username and password. After users log in, they can search for books, leave reviews for individual books, and see the reviews made by other people. I also use a third-party API by Google Books, another book review website, to pull in ratings from a broader audience. Finally, users will be able to query for book details and book reviews programmatically via my website’s API.

Registration.html – this webpage let user can register for the website.
Bookdetail.html – this webpage displays details about a book, and user can rate and submit review
Bookserach.html - this webpage let user can search for book by isbn number, publication year, title, or author.
Booklist.html – this webpage shows the search results of the book that user has searched for.
Error.html- This webpage shows an error if there is something wrong in book search.  
Success.html – This webpages shows the success message when the user have been successfully registered for the website.
Layout.html – This webpage is the parental webpage of my web application. 
Loginform.html - This webpage displays the user’s login form.
Application.py – Python code and it is the main file for the flask application.
Import.py - This python code take the information in the books.csv file and import them into a table in the database
