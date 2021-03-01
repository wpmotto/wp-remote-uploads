# WP Remote Uploads

WordPress plugin to hotlink your uploads to a remote URL. 

This plugin is useful for developers if they want to avoid downloading their entire uploads directory. When setting up a site locally, the WordPress uploads directory containing images and other assets usually needs to be downloaded so as not to break the paths on the site. Instead, this plugin will allow you to ignore the local uploads directory completely and simply point it to production or stage site that already has these assets hosted. 

## TODO

- Settings Page:
  - Remote URL
  - Basic Auth login for stages?
  - Date range
  - regex on filenames
- CORS header
- Filter for uploads path
