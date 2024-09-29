# Composer Is A Laravel Dependencies Like Npm

Composer ek dependency manager hai jo PHP projects ke liye use hota hai. Yeh libraries aur packages ko manage karne mein madad karta hai taake aapko apne project ke liye required dependencies ko aasani se handle kar sakein.

## Key Concepts

- **composer.json**: Yeh file aapke project ki dependencies aur unki versions ko define karti hai. Isme aapko libraries ka naam aur required version specify karna hota hai.

- **vendor directory**: Jab aap `composer install` command run karte hain, toh Composer required packages ko download karke `vendor` directory mein store karta hai.

- **Autoloading**: Composer autoloading feature provide karta hai jo classes ko automatically load karne mein madad karta hai. Isse aapko `require` statements likhne ki zaroorat nahi hoti.

## Basic Commands

- **Install Dependencies**: 
  ```bash
  composer install
- **Dependencies to update in latest versions**: 
```bash
composer update
```
Yeh command installed packages ko latest versions mein update karta hai.