# Simple Python File Transfer Server
A simple file transfer server written in Python 3, that allows the user to download files located on the server. The server can handle and serve multiple clients at the same time and send files in the same/child directories.

## Usage
- Run the server.py file, entering the port you wish for the server to run on.
- Now, users can run the client.py file and connect to the server by entering the IP address and port displayed on your server.
- A user can enter the name of a file on the server (in the same folder as the server.py) and download that file - the file will appear in the same directory as the client.py file, named from_server+filename.

## Requirements
- Python 3.7+
- Socket Module (standard library)
- Threading Module (standard library)
- OS Module (standard library)

## License
[MIT](https://choosealicense.com/licenses/mit/)
