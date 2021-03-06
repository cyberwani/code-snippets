Code Snippets
=============

**Requires at least:** WordPress 3.3   
**Tested up to:** WordPress 3.4.1   
**Current version:** 1.1   
**License:** GPLv3 or later   

Allows you to easily add code snippets through a GUI interface.

Description
-----------

**Code Snippets** is a easy, clean and simple way to add code snippets to your site. 

Use the top level menu to manage your snippets. You can activate, deactivate, edit and delete snippets using a page similar to the Plugins menu. You can add a name for your snippet through the visual editor and the code through a tab-enabled text-area.

Snippets are stored in the `wp_snippets` table in the WordPress database (the table name may differ depending on what your table prefix is set to).

Code Snippets includes an option to clean up its data when deactivated. Each screen includes a help tab just in case you get stuck.

Further information and screenshots are available on the [plugin homepage]( http://bungeshea.wordpress.com/plugins/code-snippets).

Code Snippets was featured on WPMU.org: [WordPress Code Snippets: Keep them Organized with this Plugin!](http://wpmu.org/wordpress-code-snippets/)

If you have any feedback, issues or suggestions for improvements please start a topic in the [Support Forum](http://wordpress.org/support/plugin/code-snippets) and if you like the plugin please give it a rating at [WordPress.org](http://wordpress.org/extend/plugins/code-snippets) :-)

Installation
------------

1. Download the `code-snippets.zip` file to your local machine.
2. Either use the automatic plugin installer *(Plugins > Add New)* or Unzip the file and upload the **code-snippets** folder to your `/wp-content/plugins/` directory.
3. Activate the plugin through the Plugins menu
4. Visit the Add New Snippet menu page *(Snippets > Add New)* to add or edit Snippets.
5. Activate your snippets through the Manage Snippets page *(Snippets > Manage Snippets)*

Frequently Asked Questions
--------------------------

### Do I need to include the &lt;?php, &lt;?, ?&gt; tags in my snippet?
No, just copy all the content inside those tags.

### Is there a way to add a snippet but not run it right away?
Yes. Just add it but do not activate it yet.

### What do I use to write my snippets?
The [EditArea](http://www.cdolivet.com/editarea/) source-code editor will add line numbers, syntax highlighting, search and replace, tablature and other cool features to the code editor.

### Will I lose my snippets if I change the theme or upgrade WordPress?
No, the snippets are added to the WordPress database so are independent of the theme and unaffected by WordPress upgrades.

### Can the plugin be completely uninstalled?
Yes, when you delete Code Snippets using the 'Plugins' menu in WordPress it will clean up the database table and a few other bits of data. Be careful not to remove Code Snippets using the Plugins menu unless you want this to happen.

### Can I copy any snippets I've created to another WordPress site?
The import/export feature is currently in development. You can however, use the export feature of phpMyAdmin to copy the `wp_snippets` table to another WordPress database.

### Can I run network-wide snippets on a multisite installation?
No, this feature is currently not avalible and will be coming in a future release. In the mean time activate Code Snippets individualy on the desired sites.

Screenshots
-----------

![The Manage Snippets page](code-snippets/raw/master/screenshot-1.jpg)   
The Manage Snippets page   

![The Add New Snippet page](code-snippets/raw/master/screenshot-2.jpg)   
The Add New Snippet page   

![Editing a snippet](code-snippets/raw/master/screenshot-3.jpg)   
Editing a snippet   

![Each screen includes a help tab just in case you get stuck.](code-snippets/raw/master/screenshot-4.jpg)   
Each screen includes a help tab just in case you get stuck.   

Changelog
---------

### 1.2
* Minor improvements
* Added code highlighting
* Removed 'Uninstall Plugin' page. Data will now be cleaned up when plugin is deleted through WordPress admin.

### 1.1
* Fixed a permissions bug with `DISALLOW_FILE_EDIT` being set to true
* Fixed a bug with the page title reading 'Add New Snippet' on the 'Edit Snippets' page

### 1.0
* Stable version released.