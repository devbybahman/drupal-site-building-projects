# Mov.ie | Unbiased Movie Review  

A Drupal-based project for movie reviews, built with custom content types, taxonomies, and a clean UI.  

## Features  
- **Custom Content Type**: A fully tailored "Movie Review" type  
- **Custom Rating System**: Implemented without additional modules, using a list field with star ratings:  
  - 5 | ★★★★★  
  - 4 | ★★★★☆  
  - 3 | ★★★☆☆  
  - 2 | ★★☆☆☆  
  - 1 | ★☆☆☆☆  
- **User Interaction**: Registration and commenting enabled  
- **Menus & Categories**:  
  - Structured navigation menus  
  - Taxonomy vocabularies for *Genre* and *Awards*  
  - Movie reviews can be browsed and filtered by these categories  
- **Theming**: Built with `classy` and `showcase_lite` themes  
- **Manage Display**: Carefully customized teaser and full views to precisely match the intended design  

## Pages  
- Review Teasers (Listing)  
- Full Review with Rating and Comments  
- Genre-based and Award-based listings  
- User Registration & Login  
## Screenshots
### Home 
<img width="1910" height="8000" alt="HOME" src="https://github.com/user-attachments/assets/f3ad4c59-19ba-4e93-947d-00288214f2fc" />

### Single Post
<img width="1910" height="8000" alt="SINGLEPOST" src="https://github.com/user-attachments/assets/6aaa0e01-c089-48df-8424-23cc61cabcb8" />


### Tag OR Genre
<img width="1910" height="2991" alt="Action" src="https://github.com/user-attachments/assets/c62d7e18-a434-4bf1-b372-57ee4642199c" />


## Configuration  
The `config/sync` folder contains the exported Drupal configuration for this project.  
To import it into a fresh Drupal installation:  

1. Place the `config/sync` directory inside your Drupal project  
2. Add the correct path in `settings.php`:  
   ```php
   $settings['config_sync_directory'] = '../config/sync';
3.Run: drush cim -y
