# Amanda Folson - APIs With Lumen

## Zero to API with Lumen

@AmbassadorAwsum

Developer Advocate at GitLab

### Why Lumen?

Useful for microservices
 * app responsible for one specific function
     - email, data processing, etc

Lumen still uses:
 * homestead
 * .env

Artisan exists with a limited feature set
 * No serve, key:generate, tinker, env, down, vendor:publish
 * make ONLY has make:migration

Facades and Eloquent disabled by default. AuthServiceProvider as well. (No sessions in RESTful APIs)

Routing is very similar.  Tests are as well.

Still has migrations, seeders, middleware.

Views no longer in Lumen 5.2 - not super difficult to add them back in


### Fractal

Consistent interface for output

Transforms object into JSON structure for output

#### more

Slides will be posted later, look for it.

lumen.laravel.com/docs
