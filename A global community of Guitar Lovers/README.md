# A Global Community of Guitar Lovers
A Drupal-based project showcasing forum functionality and custom user roles.

## Features
- Forum module enabled and configured
- Two custom roles with specific permissions:
  - **Forum Moderator**: Can moderate discussions, edit/delete inappropriate posts, and manage reported content
  - **Forum Admin**: Has full administrative control over forums, categories, and user management
- Basic responsive design

## Pages
- Forum index
- Topic view
- User profiles
## Screenshots
### Home 
<img width="1910" height="1825" alt="Home" src="https://github.com/user-attachments/assets/be80e5c7-4949-40bd-a3e4-2b29b65c5464" />

### Forum/Topic
<img width="1910" height="1443" alt="Topic" src="https://github.com/user-attachments/assets/44348e3a-ffb7-4705-bc5e-76252da693a9" />


## Configuration
The `config/sync` folder contains the exported Drupal configuration for this project.  
To import it on a fresh Drupal installation:

1. Place the `config/sync` directory inside your Drupal project  
2. Set the correct path in `settings.php`:  
   ```php
   $settings['config_sync_directory'] = '../config/sync';
3.Run:drush cim -y
