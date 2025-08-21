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


### Single Post

### Tag OR Genre


## Configuration  
The `config/sync` folder contains the exported Drupal configuration for this project.  
To import it into a fresh Drupal installation:  

1. Place the `config/sync` directory inside your Drupal project  
2. Add the correct path in `settings.php`:  
   ```php
   $settings['config_sync_directory'] = '../config/sync';
3.Run: drush cim -y
