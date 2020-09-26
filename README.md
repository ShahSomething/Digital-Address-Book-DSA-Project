# Digital Address Book
An address book is used to maintain the records of your acquaintances. Each entry in an
address book usually consists of a few standard fields (for example: first name, last
name, address, e-mail address, mobile phone number). This project is an electronic way of
storing your contacts. This program will enable the user to add, delete or search through his
contacts without having to carry an address book all the time. Using this program is much easier
and faster than using an address book.

# Features
The main functions of this program are:
1. A user can enter a record of new acquaintances.
2. Users can delete a record from the list.
3. Users can view the list of all contacts.
4. Users can search through all the contacts.
5. User can generate a printable Text File

# Description
The main advantage of this program is that it uses Hash Table. Hash Table is a
very useful Data Structure because it can minimize the time required to add, delete,
search and display Contacts. Hash Tables use a Hash Function for this purpose but one
drawback of using a Hash function is that it can return the same index for different keys
resulting in the collision of keys. To resolve the collision problem I have used a process
known as Chaining. In the chaining Process a Linked List is required so that we can add
as many nodes as possible. In Linked List, memory can be dynamically allocated and
released using pointers.
One node of the Linked List contains the next pointer and all the variables to store
data of a single contact like name, address, phone number etc.
