# private + public key

[overview](https://chat.openai.com/c/d143f08d-2a61-4ca4-891e-935647da843f)

- encrypt / decrypt
	-
	  ```
	  message = ...
	  ciphertext = public_key.encrypt(message, ...)
	  
	  ...
	  
	  decrypted_message = private_key.decrypt(ciphertext, ...)
	  ```
- sign / verify
	-
	  ```
	  signature = private_key.sign(message, ...)
	  
	  ...
	  
	  public_key.verify(signature, message, ...)
	  ```