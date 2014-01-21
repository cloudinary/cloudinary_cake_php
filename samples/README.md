Cloudinary Cake PHP Sample Project
=============================

Included in this folder is sample project for demonstrating the common Cloudinary's usage with Cake PHP.

## Photo Album

This sample demonstrate the usage of the Cloudinary CakePHP plugin. It provides very similar functionalities as the basic Photo Album.

This samples requires CakePHP to be installed. You can follow our directions in [the `README.md` file](https://github.com/cloudinary/cloudinary_cake_php/tree/master) using either the manual method or Composer for the installation.

When you finish:

* Setup database config (You can use `Config/database.php.default` as reference by copying it into `Config/database.php` and modifying the relevant fields. See the [CakePHP Cookbook](http://book.cakephp.org/2.0/en/index.html) for more information)
* Create the database table (`cake schema create`)

You can now access the sample through http://YOUR\_SERVER/PATH\_TO\_CLOUDINARY\_PHP/samples/PhotoAlbumCake

*If you use Composer - Please note:* You do not need to bake a new project if you want just to try out the sample. If you do bake one, you'll have to remove the `.htaccess` from your app root directory in order to be able to access the sample in `APP_ROOT/Vendor/cloudinary/cloudinary_php/samples/PhotoAlbumCake`.

Another option is available if you are using PHP 5.4 or higher. Go to the `samples` directory and run -

If you're using a Bourne compatibly shell (sh, bash, zsh):

    NO_REWRITE=1 php -S localhost:8001

On Windows command prompt:

    set NO_REWRITE=1
    php -S localhost:8001

Then you can simply browse to:

	http://localhost:8001/PhotoAlbumCake/index.php/

