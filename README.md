# vertx-web-pipeline
Provide the pipeline functionality (building resources at startup or runtime) on top of vertx-web


See : https://grails.org/plugin/asset-pipeline , http://guides.rubyonrails.org/asset_pipeline.html


The goal is to provide an interface for 3rd party developers to create front-end oriented plugins (Compass, JS minification, image sprites, ...) that transform static resources.

With the ability to re-transform the resources everytime a request is made if in a development environment.
Also the ability to transform missing resources at startup.
But also rely on existing transformed resources if they have been built manually by an external build tool (Maven, Gradle, Grunt, Gulp, ...).
