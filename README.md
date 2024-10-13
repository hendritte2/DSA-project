# Phonebook Application

This project implements a simple phonebook using basic linear data structures (arrays) in *JavaScript*. It allows for basic contact management functionalities such as inserting, searching, updating, and deleting contacts.

## Features
- Add a new contact (name, phone number).
- Search for a contact by name or phone number.
- Display all contacts.
- Delete a contact by name or phone number.
- Update a contact’s information.
- Sort contacts by name (optional).
- Analyze search efficiency.

## Data Structure
The phonebook uses a *JavaScript array* to store contacts. Each contact is represented as an object with two properties: name and phone.

## Functions:

### 1. *addContact(name, phone)*
Adds a new contact to the phonebook if both name and phone are provided.

*Algorithm:*
- Check if both name and phone are not empty.
- If valid, create a new contact object with name and phone.
- Append the new contact to the phonebook array.
- Print a success message.
- If either name or phone is empty, print an error message.

*Example:*
javascript
addContact("Alice", "123-456-7890");
// Output: "Contact added successfully!"


### 2. *searchContact(searchTerm)*
Searches for a contact by name or phone in the phonebook.

*Algorithm:*
- Iterate through each contact in the phonebook array.
- If a contact's name or phone matches the searchTerm, store the result and break the loop.
- If a contact is found, print the contact's details. Otherwise, print "Contact not found!".

*Example:*
javascript
searchContact("Alice");
// Output: "Found: Alice - 123-456-7890"


### 3. *displayAllContacts()*
Displays all the contacts in the phonebook.

*Algorithm:*
- If the phonebook is empty, print "No contacts available".
- Otherwise, iterate through the array and print each contact's name and phone number.

*Example:*
javascript
displayAllContacts();
// Output: "Alice - 123-456-7890"


### 4. *deleteContact(deleteTerm)*
Deletes a contact from the phonebook by name or phone.

*Algorithm:*
- Iterate through the phonebook.
- If a contact's name or phone matches the deleteTerm, remove that contact from the array.
- Print "Contact deleted successfully" and break the loop.
- If no contact is found, print "Contact not found!".

*Example:*
javascript
deleteContact("Alice");
// Output: "Contact deleted successfully!"


### 5. *updateContact(updateTerm, newName, newPhone)*
Updates the details of a contact identified by name or phone.

*Algorithm:*
- Iterate through the phonebook.
- If a contact's name or phone matches the updateTerm, update the name or phone if the new values are provided.
- Print "Contact updated successfully!".
- If no contact is found, print "Contact not found!".

*Example:*
javascript
updateContact("Alice", "Alicia", "987-654-3210");
// Output: "Contact updated successfully!"


### 6. *sortContacts()* (Optional)
Sorts the contacts in the phonebook by name in ascending order.

*Algorithm:*
- Sort the phonebook array by name.
- Print "Contacts sorted by name".

*Example:*
javascript
sortContacts();
// Output: "Contacts sorted by name."


## Notes on Efficiency:
- All operations (insert, search, update, delete) use *linear search, which has a time complexity of **O(n), where **n* is the number of contacts in the phonebook.
- The sort function has a time complexity of *O(n log n)*.

Team Members
Hendritte Musambani 224080911, Meme Wetu 224087932, Mwalunga Stefanus 223090421 ,Unombwiro Tjikune
223006300

Silvio G Vries
 224032321

Sylvanus Shilyomunhu
224091514
