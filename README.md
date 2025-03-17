# laravel-prune
This repository contains an implementation of Laravel Model Pruning based on a tutorial from Parsinta

# Laravel Model Pruning (Laravel 12 Version)

This repository provides an implementation of **Laravel Model Pruning**, based on a tutorial from [Parsinta](https://parsinta.com/articles/tutorial-laravel-pruning-menjaga-database-anda-tetap-ringan-dan-efisien-sengk).  
The original tutorial was written for **Laravel 10**, but this implementation adapts it for **Laravel 12**, where **Console Commands** are now defined in `routes/console.php`.

## 📌 Features  
- Automatically deletes unused models based on specific conditions  
- Uses the `prunable()` method inside the model  
- Leverages Laravel Scheduler for automated pruning commands  
- Fully compatible with Laravel 12  

## 🛠 Installation  
1. Clone this repository:  
   ```sh
   git clone https://github.com/khoirulyahya/laravel-prune.git
   cd laravel-prune

## 📖 References  
This project is based on a tutorial by Parsinta:  
🔗 [Laravel Pruning: Keeping Your Database Lightweight and Efficient](https://parsinta.com/articles/tutorial-laravel-pruning-menjaga-database-anda-tetap-ringan-dan-efisien-sengk).  

I have adapted the implementation for **Laravel 12**, adjusting the command registration to follow the new structure in `routes/console.php`.
