# Random Password Generator

A simple JavaScript project that generates secure random passwords based on selected criteria.

## Features

* Generate passwords of any length
* Option to include:

  * Lowercase letters
  * Uppercase letters
  * Numbers
  * Symbols
* Input validation to ensure proper password generation

## How It Works

The function builds a pool of allowed characters based on user preferences, then randomly selects characters from that pool to create a password.

## Usage

1. Set your desired password length:

   ```javascript
   const passwordLength = 12;
   ```

2. Choose character options:

   ```javascript
   const includeLowercase = true;
   const includeUppercase = true;
   const includeNumbers = true;
   const includeSymbols = true;
   ```

3. Generate the password:

   ```javascript
   const password = generatePassword(
       passwordLength,
       includeLowercase,
       includeUppercase,
       includeNumbers,
       includeSymbols
   );
   ```

4. Output:

   ```javascript
   console.log(`Generated password: ${password}`);
   ```

## Example Output

```
Generated password: A7$fK2@pL9!
```

## Project Structure

```
.
├── index.js
└── README.md
```

## Future Improvements

* Add a user interface (HTML/CSS)
* Copy to clipboard feature
* Password strength indicator
* Save generated passwords securely

## Author

Gabriel

## License

This project is open source and available under the MIT License.
