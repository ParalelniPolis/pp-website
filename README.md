# pp-website

**instalalce níže**

grafické zadání lze jajít ve složce **grafické zadání**

hlavní složka pro vývoj frondendu je **htdocs/content/themes/app** a v ní se nachází:

* admin/: This folder is an extension of the classic functions.php file. You can add as many files as you want at its root. As the name suggests, this is where you'll write your code in order to shape the WordPress administration and set your data: custom post types, metaboxes, custom fields, pages,... Note: The framework will load your files in alphabetical order. An application.php file is loaded by default.
* assets/: Insert all your stylesheets, javascripts, images and other public assets inside this folder.
* config/: Contains the website/application configuration files: application, constants, images, loading, menus, sidebars, supports, templates. Read the configuration guide for more information.
* controllers/: This folder stores all your controller classes.
* models/: Stores your model classes.
* storage/: Stores all temporary views. Note: This directory must be writable.
* tests/: Stores your PHPUnit tests.
* views/: This folder allows you to organize your views - HTML. You can point to sub-directories using a dot syntax.
* widgets/: Contains your widget classes.
* routes.php: This file handles your website routes. The route system behaves like an "if" statement on steroids. Read the routing guide for more information.

hlavní readme na Themosis je na http://framework.themosis.com/docs/framework/

je založený user **guest** s heslem guest - pro login stačí zadat /login

# instalace
zatím je nakonfogurovaná jen local instalace do složky /pp-website

via composer execute: 

    composer create-project themosis/themosis my-project-name
    
pozor - composer nic nestáhne do složky která už něco obsahuje, stejně tak git - stáhněte to vedle a potom přesuňte
