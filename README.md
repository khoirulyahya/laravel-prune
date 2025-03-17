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
   git clone https://github.com/username/repo-name.git
   cd repo-name
