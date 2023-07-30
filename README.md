# Encryption-Decryption-Class-For-PHP

A simple class file to encrypt and decrypt data using standard encryption method

## Installation

Download the class file and place in your project. As simple as it is :)


## Usage

```php
<?php 

include_once "EncryptDecrypt.php";

//create an object of the class
//after then you can access the methods of the class using $key variables
$key = new EncryptDecrypt();

$data = 'Hello World';

//Data encryption example
$encrypted_data = $key->encrypt($data);
echo $encrypted_data;

//Decrypt the data that we've encrypted
$decrypted_data = $key->decrypt($encrypted_data);
echo $decrypted_data;

?>
```

## Need Help?

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

If you have any problem regarding the file please feel free to contact me via email pranaycb.ctg@gmail.com

Happy Coding 🤗🤗

## License

[MIT](https://choosealicense.com/licenses/mit/)
