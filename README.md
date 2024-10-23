# **Library Management System Flask**

## **About**

A Library Management Web Application.It Allows a librarian to track books and their quantity, members, and transactions.
(Built with Flask, MySQL)

# Functionality 🛠️
The application covers the following key functionalities:

# Index Page
**1.Reports**

**2.Books**

**3.Members**

**4.Transaction**



# Database Tables 🗄️
**Report** This table stores information about various User and Book Report. Each Book is identified by a unique Book_id.


# Book Views 👀
The application provides easy-to-use views for the following:

**1.Add new Books.**

**2.Edit existing Book details.**

**3.View the list Book with their respective information.**



# Member page

**1.Add new Member.**

**2.Edit existing Member details.**

**3.View the list of Member with their respective information.**



# Transaction Page
Add new Transaction to record the transfer of Book between Users.
Edit existing movement details if necessary.
View the list of Book movements with relevant information.



# Report 📊
The application generates a comprehensive report that displays the balance quantity of each Book in each Members. The report is presented in a grid view with the following columns.
**Report** Find the book details and high paying books




# Search Book Page
Tha application search Books Using Book Title and Auther.



## **Getting Started**

1. Install requirements
   ```sh
   pip install -r requirements.txt
   ```
2. Setup MySQL and replace host, user, password values in `setupDB.py`, `app.py` and `test.py` as required </br></br>
3. Create Database and Tables using `setupDB.py`
   ```sh
    cd utils
    python setupDB.py
    cd ..
   ```
4. Run app
   ```sh
   python app.py
   ```
**Note: Ensure you have Python and Flask installed on your system before starting the application.**

*Access the application in your web browser by visiting
