# WebDev_Notes  
This repository serves as notes for Web Development to do and a must to take note.  

## Laravel Framework  
  #### Query Speeds and Storage.
- $contacts = Contact::all(); `Eloquent` `4mb - 13ms`
- $contacts = DB::table('contacts')->get(); `Query Builder` `4mb - 10.45ms`
- $contacts = DB::select('SELECT * FROM contacts');  `Query Builder Select` `4mb - 9.99ms`  
#### To install - Laravel Debugbar
- `composer require barryvdh/laravel-debugbar --dev`  
- `php artisan vendor:publish --provider="Barryvdh\Debugbar\ServiceProvider"`
