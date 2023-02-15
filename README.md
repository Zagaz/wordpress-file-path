### Wordpress file path
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FZagaz%2Fwordpress-file-path&count_bg=%23066C2A&title_bg=%23555555&icon=wordpress.svg&icon_color=%23E7E7E7&title=Visits&edge_flat=false)](https://hits.seeyoufarm.com)

`plugin_basename( __FILE__ )`
This method extracts the name of a plugin from its filename.
Example: *myplugin/myplugin.php*
Font: https://developer.wordpress.org/reference/functions/plugin_basename/

`plugin_dir_path( __FILE__ )`
Get the filesystem directory path (with trailing slash) for the plugin __FILE__ passed in.
Example: *app/public/wp-content/plugins/myplugin/*
Font: https://developer.wordpress.org/reference/functions/plugin_dir_path/

`plugins_url()`
Retrieves a URL within the plugins or mu-plugins directory.
Example: https://myblog/wp-content/plugins
Font: https://developer.wordpress.org/reference/functions/plugins_url/

`plugins_url( 'includes', __FILE__ );`
Retrieves a URL within the plugins or mu-plugins directory appends and extra path to the end of the URL,  including the relative directory if $plugin is supplied.
Example: *https://myblog/wp-content/plugins/myplugin/includes*

`plugin_dir_url( __FILE__ )`
Get the URL directory path (with trailing slash) for the plugin __FILE__ passed in.
Example: *https://myblog/wp-content/plugins/myplugin*

Font: https://developer.wordpress.org/reference/functions/plugin_dir_url/









