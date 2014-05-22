# Drupal Global Training Day - Demo Site

[Drupal Global Training Days](https://drupal.org/node/1600942) is an initiative by the [Drupal Association](https://drupal.org/node/1600942) to introduce new and beginning users to Drupal. The Drupal Association is partnering with training companies to make this happen. Once a quarter, free or low cost training events will take place around the world with one of two curriculums:

* "Introduction to Drupal," a full day training on the basics of Drupal. Attendees will leave having successfully built a Drupal site. It is ideal for those interested in exploring Drupal as a career path.
* "What is Drupal?" This half-day workshop will address the basics of Drupal, and will give an overview to those interested in evaluating or implementing Drupal.
Each training company can make it their own event and provide more detail on their web pages.

We invite you to come Learn Drupal!

## Installation & Usage instructions

+ Move contents of document_root folder to your websites root folder
+ Create an empty MySQL database and import there the “database/example_dev.sql” file.
+ open settings.php file in your favioute editor, navigate to line #213 where you will see a variable $databases. Change 'database', 'username', 'password' & 'host'
+ Now fire your favourite browser & visit http://localhost (or) the name you have give for your site

Login to this site by using the following credentials:
- u: admin
- p: admin

Demo of this can be found in [acquia cloud](http://globaltrainingdaydev.devcloud.acquia-sites.com/).

    Developed & Maintained by [Gobinath](http://gobinath.com/).

#### This demo is created with Drupal 7.28 and its out of the box components. 
A theme which was not part of core is used [corporateclean](drupal.org/project/corporateclean)
