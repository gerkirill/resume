# Kirill Herasimenko

E-mail: k.gerasimenko@gmail.com  
Skype: goooooooooogler  
Mobile: +3 8063 771 61 32  
Age: 29  

## Desired position

### Senior php developer

## I can

 - design software architecture
 - code web and cli applications
 - teach, share my experience
 - perform task breakdown and delegation
 - control code and product quality

## Few facts about me

 - Started php coding in 2002 (php v.4)
 - Deep knowledge of OOP, OO-Design, patterns (also patterns specific to web-development)
 - Have an experience of code review and refactoring work, performance optimization
 - Like modular, reusable, SOLID and DRY code
 - Have some highload projects experience

## Frameworks used

 - symfony2
 - typo3flow ( http://flow.typo3.org/ )
 - icms (proprietary)
 - kohana (long ago)
 - yii (long ago)
 - once written my own MVC framework

## Php cms I have experience with

 - icms (icms.ch - insign CMS, member of core team)
 - wordpress
 - typo3
 - pimcore

## Web technologies besides php I have knowledge of

 - mysql, apache
 - plain js, jQuery, prototype, knockout.js, node (a bit)
 - less, twitter bootstrap
 - HTML, ajax, CSS

## Other technologies used

 - wkhtml2pdf to generate pdf from html pages
 - search indexing with solr, lucene, zend-lucene
 - using redis as fast key-value storage
 - using apache lucene as no-sql storage
 - varhish for cache

## Good habits

 - PSR-2 coding standards where applicable
 - reusable composer-compatible libraries
 - automated testing
 - version control with git or svn
 - vagrant with virtualbox for development environments
 - write code clean, SOLID, DRY and well-commented, document design decisions
 - use xdebug for debug and profiling

## Companies I worked for

 - 2001-2002 - AMICO - desktop applications with Delphi, customization of dotproject appication (php + mysql)
 - 2003 - GFL - tech. support specialist
 - 2004 - GFL, afternic.com - LAMP programming

since 2005 till now - Insign gmbh. - Senior programmer, member of the core team, team-lead at SML (scrum) and DCD projects.


## Some of the projects I worked on

### social media laucher

http://sml.insign.ch/

Web service for posting into multiple social networks and Mailchimp from one place. Capable of integration into wordpress with a plugin.

#### Technologies and tools

PHP, MySQL, JavaScript, symfony2, doctrine, twig, composer, HMVC, REST, jQuery, twitter bootstrap, balsamiq mockups, visual paradigm UML, TinyMce

#### Role

Team lead

#### Responsibilities

Architecure, development, technical assistance and code reviews, working process optimization, communication with product owner

  - active participant of hangouts with product owner (this project was kind of scrum)
  - defined proper workflow for this project in jira, git workflow
  - implemented interaction with posting and auth. API of facebook, xing, twitter, google plus, tumblr, mailchimp
  - composed technical requirements, broke project down into tasks, performed code quality control
  - application architecture design
  - database design
  - application front-end mockups ( created with http://balsamiq.com/ mockup tool )


### device comparison database 

http://www.handy-check.ch/

Online-database with mobile devices, advanced search and comparison functions. Written with typo3flow (mvc framework).

#### Technologies and tools

PHP, MySQL, JavaScript, typo3flow, HMVC, doctrine, fluid, jQuery, balsamiq mockups, visual paradigm UML

#### Role

Team lead

#### Responsibilities

Architecure, development, technical assistance and code reviews

  - composed technical requirements, broke project down into tasks, performed code quality control
  - it is first time I suggested and implemented an approach when regular user and administrator share the same UI. The difference is an additional controls shown only to administrator.
  - implemented "faceted" search ( http://www.handy-check.ch/#extended/ ) width denormalization to the "flat" table from EAV
  - added HMVC capability to typo3flow framework
  - application architecture design
  - database design
  - application front-end mockups ( created with http://balsamiq.com/ mockup tool )


### ICMS

http://www.icms.ch/

In-house framework of Insign gmbh., **icms-cms** - content-management system based on it. 

#### Technologies and tools

PHP, MySQL, JavaScript, XML/XHTML parser, regexp, XPATH, prototype.js, jQuery, swish-e, zend-lucene

#### Role

Core developer, 560 commits into the core since 2007 (we had no VCS before that)

#### Responsibilities

Modules development, security reviews, code optimization. Technical interviews during hire campaigns. Team trainings. Technical assistance and code reviews for team members.  

#### Most notable features I've implemented

  - added multi-language support for navigation and content modules of cms
  - icms::forms (like google forms, but better and integrated into icms)
  - integration of oauth login into personalizer (auth. module)
  - developed and implemented subsites feature for cms and shop
  - security improvements (migration to encrypted passwords storage, secure sessions for super-admins, few security bugfixes)
  - refactored personalizer module (module for handling users and authorization) admin panel  from iframes to cross-browser XHTML and ajax (with jQuery), wrote jQery plugin to seamlesly replace standard confirmation popup with one based on fancybox.
  - cache system adjustments and improvement (e.g. proper cache invalidation for timed CMS blocks, client-side caching with e-tag)
  - server-side form-setter (set form field values according to defaults or previously submitted data)
  - icms template engine improvements (e.g. "components" - embeddable sub-templates, etc)
  - "articles with attributes" concept implementation for icms-shop module (attributes which may affect product price, images, availability in stock, etc)
  - complete redesign of debug system (both php and UI part)


### app-localizer

http://icms.insign.ch/icms/android/app-localizer/

Online service for localizing android applications written with icms. Entirely designed and implemented by me (architecture and database design, UI).

#### Technologies and tools

PHP, MySQL, JavaScript, icsm, XML parser, git, svn, jenkins CI, android i18n system

#### Role

Web developer

  - implemented support for multiple translators working at the same time
  - added support of 2 VCS systems (git, svn) - allows translators to commit their changes right fom the web application
  - integrated with automatic build system (jenkins)


### News is free

http://newsisfree.com/

Online news aggregator.

#### Technologies and tools

PHP, MySQL, JavaScript, Smarty, SOAP, REST, prototype.js, ajax, XML parser (for rss), regexp

#### Role

Web developer

#### Responsibilities

 - Web spider maintenance
 - AJAX news reader development
 - Developed news alerts system, which notifies users about the news they interested in over jabber (XMPP), sms and e-mail.


### Newskowledge

http://newsknowledge.com/

News syndication service.

#### Technologies and tools

PHP, MySQL, JavaScript, prototype.js, script.aculo.us, SOAP, REST, XML, Siets (proprietary fulltext document storage), Lucene

#### Responsibilities

migration from Siets to Lucene, "Newsfeed wizard", code optimizations


### Piazza

http://piazza.ch/

Swiss bulletin board

#### Technologies and tools

PHP, MySQL, memcache, smarty

#### Responsibilities

Performance optimization, caching improvements, migration to amazon cloud.


### CRM data export

js bookmark for http://jira.insign.ch

Exports contact information stored into jira custom fields and adds a link to the page which allows to download it in v-card (.vcf) format. Also adds a QR-code image to the page which allows easily grab contact with mobile device.

#### Technologies and tools

PHP, MySQL, JavaScript, REST, cross-domain ajax, jQuery, v-card

#### Role

Web developer

#### Responsibilities

 - the idea and implementation
 - developed special template format to map jira fields to vcf
 - made .vcf file compatible with mac address book, windows and android.