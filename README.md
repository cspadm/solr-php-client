## Solr PHP Client
A PHP library for indexing and searching documents within an Apache Solr installation. Supports both Solr 3 and 4. — Fork of the solr-php-client project on Google Code. https://github.com/PTCInc/solr-php-client

## What is Apache Solr?
=> Solr is an open source enterprise search server based on the Lucene Java search library, with XML/HTTP
  and JSON APIs, hit highlighting, faceted search, caching, replication, a web administration interface
  and many more features. It runs in a Java servlet container such as Tomcat.
=> For more information about Solr, please see the [Solr Web Page](http://lucene.apache.org/solr/). The
  project's [Wiki](http://wiki.apache.org/solr/) is the de facto starting point for information on how
  to install and configure Solr for your individual needs.

## Features
 * Quering, deleting, optimizing.
 * Support for both Solr 3 and Solr 4 through compatibility layers.
 * Support for soft commit with Solr 4.

## Installation

Install Composer In Your Project

$ curl -sS https://getcomposer.org/installer | php

Install Solr PHP Client Library In Your Project

$ vim composer.json

  {
    "require": {
        "dsasikumar08/solr-php-client": "1.0.4"
    }
  }

$ php composer.phar install

## Disclaimer
This PHP library is not part of the Apache Solr project, nor is it maintained by the Apache Software Foundation.
All linked Apache Solr documentation or logos remain the sole property of the Apache Solr project, its authors,
and the Apache Software Foundation.
