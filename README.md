
# Contact Book Console Application

This is a simple console application written in Python for managing contacts. It allows users to add, delete, edit, search, and view contacts from the command line interface.

## Installation

1. Clone the repository or download the code files.
2. Install the required dependencies using pip:
   ```
   pip install beautifultable
   ```

## Usage

1. Run the program by executing the `contact_book.py` file.
   ```
   python contact_book.py
   ```

2. Follow the on-screen prompts to interact with the contact book:
   - **Add contact**: Enter details like name, address, phone number, and email to add a new contact.
   - **Delete contact**: Enter the phone number of the contact you want to delete.
   - **Edit contact**: Enter the phone number of the contact you want to edit, then provide new details for name, address, and email.
   - **Search contact**: Enter a search query and optionally specify a field to sort by (name, address, phone_number, or email).
   - **View contacts**: Lists all contacts currently stored in the contact book.

3. To exit the program, choose the "stop" option from the menu.

## Code Structure

- The `Contact_book` class encapsulates methods for contact management.
- Contacts are stored internally in a dictionary, where the phone number serves as the key and contact details are stored as a list.
- The `BeautifulTable` class from the `beautifultable` library is used for displaying contacts in a tabular format.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this README with additional information or sections as needed!
