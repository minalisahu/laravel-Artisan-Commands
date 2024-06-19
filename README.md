# laravel-Artisan-Commands


Here's a comprehensive list of  the artisan commands available in Laravel. Here are the commands categorized by their purpose:

Route Commands,

    php artisan route:cache Create a route cache file for faster route registration
    php artisan route:clear Remove the route cache file
    php artisan route:list List all registered routes

Optimize Commands,

    php artisan optimize:clear Remove the cached bootstrap files

Make command,


    php artisan make:controller Create a new controller class
    php artisan make:event Create a new event class
    php artisan make:factory Create a new model factory
    php artisan make:job Create a new job class
    php artisan make:listener Create a new event listener class
    php artisan make:mail Create a new email class
    php artisan make:middleware Create a new middleware class
    php artisan make:migration Create a new migration file
    php artisan make:model Create a new Eloquent model class
    php artisan make:notification Create a new notification class
    php artisan make:observer Create a new observer class
    php artisan make:policy Create a new policy class
    php artisan make:provider Create a new service provider class
    php artisan make:request Create a new form request class
    php artisan make:resource Create a new resource
    php artisan make:rule Create a new validation rule
    php artisan make:scope Create a new scope class
    php artisan make:seeder Create a new seeder class
    php artisan make:test Create a new test class
    php artisan make:notification InvoicePaid --markdown=mail.invoice.paid
    php artisan make:model User -mcr
    php artisan make:cast Create a new custom Eloquent cast class
    php artisan make:channel Create a new channel class
    php artisan make:command Create a new Artisan command
    php artisan make:component Create a new view component class


Migrate Commands,

    php artisan migrate:fresh Drop all tables and re-run all migrations
    php artisan migrate:install Create the migration repository
    php artisan migrate:refresh Reset and re-run all migrations
    php artisan migrate:reset Rollback all database migrations
    php artisan migrate:rollback Rollback the last database migration
    php artisan migrate:status Show the status of each migration

Storage Commands,

    php artisan storage:link Create the symbolic links configured for the application


















Key Commands
key:generate Set the application key

Cache Commands
cache:clear Flush the application cache
cache:forget Remove an item from the cache
cache:table Create a migration for the cache database table

Config Commands
config:cache Create a cache file for faster configuration loading
config:clear Remove the configuration cache file

Database Commands
db:seed Seed the database with records
db:wipe Drop all tables, views, and types


Event Commands
event:cache Discover and cache the application's events and listeners
event:clear Clear all cached events and listeners
event:generate Generate the missing events and listeners based on registration
event:list List the application's events and listeners

Queue Commands
queue:clear Delete all of the jobs from the specified queue
queue:failed List all of the failed queue jobs
queue:failed-table Create a migration for the failed queue jobs database table
queue:flush Flush all of the failed queue jobs
queue:forget Delete a failed queue job
queue:listen Listen to a given queue
queue:monitor Monitor the size of the specified queues
queue:prune-batches Prune stale entries from the batch database
queue:prune-failed Prune stale failed jobs from the database
queue:restart Restart queue worker daemons after their current job
queue:retry Retry a failed queue job
queue:retry-batch Retry the failed jobs for a batch
queue:table Create a migration for the queue jobs database table
queue:work Start processing jobs on the queue as a daemon

Schedule Commands
schedule:clear-cache Delete the cached mutex files created by scheduler
schedule:list List the scheduled commands
schedule:run Run the scheduled commands
schedule:test Run a scheduled command
schedule:work Start the schedule worker

View Commands
view:cache Compile all of the application's Blade templates
view:clear Clear all compiled view files


