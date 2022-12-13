# book-adviser
It is a web app with books list, for which  users can leave recensions.

---------------------------------------------------------------------------------------------------------
Application description:

The main idea of the project is to help book readers find a book by recensions of the other readers.

The application has a book list. They could be sorted by genres, authores and its date of publication.

An user can leave a recension on the certain book. A recension consists of book quality mark( displayed in stars), book complexity and recension description. It is attached to the book and is visible for other users which could interact with it by rating it from -5 to 5 (where -5 corresponds to 'I have an opposite opinion' abd 5 is 'I am completely agree'). The recensions with the highest retings from other users are shown on the very top.

There is also a possibility to sort books by given quality marks (where is the biggest amount of 'five stars') and complexity.

Also in the future there could be a possibility of friendship between readers for following recensions of each other.

----------------------------------------------------------------------------------------------------------

User interface supports 2 languages: English( default ) and Ukrainian.

----------------------------------------------------------------------------------------------------------

Stack of used technologies:

DB: PostgreSQL
Backend: Django framework (Python)
Frontend: Angular framework (Typescript), SCSS, Bootstrap


Database scheme:
![image](https://user-images.githubusercontent.com/58745562/207330539-50a7df77-2047-4581-b57d-effe5a761c1e.png)


### How to start server:  
`pipenv shell`
`pipenv install`
`./book_adviser/manage.py migrate`
`./book_adviser/manage.py runserver 8006`
