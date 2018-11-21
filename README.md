# PHP reverse shell generator
This is a small python script to generate an obfuscated php reverse shell.

## Usage
1. Generate the payload: ``` python main.py <ip> <port> <filename>```. 
A connection listener will be automatically set up.
2. Upload and execute the payload on the remote host and you will obtain a full tty shell with tab-complenion.
