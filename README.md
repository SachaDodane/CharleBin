Project Name : CharleBin

CharleBin is a minimalist, open source online pastebin where the server has zero knowledge of pasted data.
Data is encrypted and decrypted in the browser using 256bit AES.

For this project, you need PHP. The minimum version is PHP 8.2.
Here is a link to download PHP : https://www.php.net/downloads.php.

To install locally the project, clone the project, then go to the root of CharleBin and make : bin/composer install.

Once you have programmed, you need to start the server. 
So, go to the root of the project and make : php -S localhost:8080.
Then, you can type "localhost:8080" on your browser to access to CharleBin.

For testing, go to the root of the project and make : curl -s localhost:8080 | grep -q "<title>CharleBin</title>".