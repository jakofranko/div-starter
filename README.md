# [Div Starter Beta 1.0](http://starter.divtruth.com/) (Coming soon -will provide documentation)

Div Starter is a development platform for [Wordpress Sites](http://wordpress.org/), a framework that aims to be powerful yet simple. Some of the greatness of frameworks like [Genesis](http://my.studiopress.com/themes/genesis/) *(made for super users)*, but without the bulk and clutter; much like [Bones](http://themble.com/bones/) (actually based on bones with some powerful tools - *meant for developers*). 

Created and maintained by [Nick Worth](http://twitter.com/xtremefaith), forked from [Betsy Cohen's](https://twitter.com/betsela) [Plus1 Starter Theme](https://bitbucket.org/betsela/plus1-starter-theme).

## Requirements
+ **Requires**: 3.6.1 (WordPress)
+ **Tested up to**: 3.8
+ **License**: GPLv2 or later
+ **License URI**: http://www.gnu.org/licenses/gpl-2.0.html
+ **Tags**: custom post type, modules, features, bones, mobile first sass
+ **Features**: 
    + [SASS](http://sass-lang.com/)
	+ [ACF](http://www.advancedcustomfields.com/) (child-level developed ACF fields and options)
        + Take CPTs (Custom Post Types) to a whole new level
        + Custom Theme Option Pages
            +  Company Setting  (*All company details used throughout the theme development*)
            +  Theme Options (Filters to enable/disable
        		+ Dev Mode
        		+ Filter search results by Relevance (imported from [Relevanssi](http://wordpress.org/plugins/relevanssi/))
        		+ Execute Shortcodes in widgets
        		+ Convert Twitter handlers to links
        		+ Media Options *(Change the default WP JPG compression for uploaded images)*
    + Google Analytics (for implementing GA code) - *Why use a plugin for something so simple?*
    + Sitemap
        +  Simple sitemap solution (more options to come)
    + Internal Documentation page
    + Custom Theme Branding
    + Social Media Sharing/Following options (Coming soon)
	+ [Widgets](https://bitbucket.org/nworth/div-starter/src/dev/library/features/widgets?at=master)
		+ [Social Profile Widget](https://bitbucket.org/nworth/div-starter/src/dev/library/features/widgets/social-widget?at=master)
		+ [Content Widget](https://bitbucket.org/nworth/div-starter/src/dev/library/features/widgets/content-widget?at=master)
	+ [Shortcodes](https://bitbucket.org/nworth/div-starter/src/dev/library/features/shortcodes?at=master)
		+ [Content Feed](https://bitbucket.org/nworth/div-starter/src/dev/library/features/shortcodes/content_feed.php?at=master)
		+ [Twitter Feed](https://bitbucket.org/nworth/div-starter/src/dev/library/features/shortcodes/twitter_feed.php?at=master)
			+ Twitter Authentication

## Quick start

Developers simply setup your [typical wordpress site](http://teamtreehouse.com/library/websites/how-to-make-a-blog/getting-started-with-wordpress/the-famous-5minute-wordpress-install) (locally or on your server):

* **Clone the starter repo**: `git clone https://github.com/Xtremefaith/div-starter`.
* **Clone a child repo**:
    * `git clone https://github.com/Xtremefaith/div-basic`.
    * `git clone https://github.com/Xtremefaith/div-wiki`.
    * *...more to come*

* **Activate the your Child Theme**
	+ You can change the folder name to anything, suggested format: `div-project-slug`
	+ Update the child `style.css`
        + * **always make sure the template matches the folder name of the starter theme `div-starter`** *.
	+ Update the logo-login.png and any of the login.scss styles you want to customize the login page for your client/project
+ Check out the documentation page: **Div Truth Options->Documentation** (more documentation to come)
+ Be sure to setup the **Dev Tools Page**
	+ Brand your child theme
	+ Add contributor details
    + Google Analytics
    + Sitemap
    + Social Media APIs

#####A more details tutorial and full documentation will be provided on the [Div Starter Page](http://starter.divtruth.com)

## To Do List

* Full Social Media API integration with theme options for implementation throughout the site
* More SEO options
* More helpful filters/shortcode for developers
* Cleaner built-in gallery and slideshow options
* Code cleanup / internal documentation

## Bug tracker / Request

Have a bug or a feature request? [Please open a new issue](https://github.com/Xtremefaith/div-starter/issues). Before opening any issue, please search for existing issues.

## Contributors

**Nick Worth**

+ [@Xtremefaith](http://twitter.com/Xtremefaith)
+ GitHub: [Xtremefaith](https://github.com/Xtremefaith)
+ BitBucket: [nworth](https://bitbucket.org/nworth)

**Leigh Grainer**

+ BitBucket: [lawgrainge](https://bitbucket.org/lawgrainge)

**Betsy Cohen**

+ [@Betsela](http://twitter.com/betsela)
+ BitBucket: [Betsela](https://bitbucket.org/betsela)