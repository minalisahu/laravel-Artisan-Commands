# laravel-Artisan-Commands


Here's a comprehensive list of all the artisan commands available in Laravel. You can get this list by running php artisan in your terminal within your Laravel project directory. Here are the commands categorized by their purpose:

Route Commands
route:cache Create a route cache file for faster route registration
route:clear Remove the route cache file
route:list List all registered routes


Optimize Commands
optimize:clear Remove the cached bootstrap files

Make Commands
make:cast Create a new custom Eloquent cast class
make:channel Create a new channel class
make:command Create a new Artisan command
make:component Create a new view component class
make:controller Create a new controller class
make:event Create a new event class
make:exception Create a new custom exception class
make:factory Create a new model factory
make:job Create a new job class
make:listener Create a new event listener class
make:mail Create a new email class
make:middleware Create a new middleware class
make:migration Create a new migration file
make:model Create a new Eloquent model class
make:notification Create a new notification class
make:observer Create a new observer class
make:policy Create a new policy class
make:provider Create a new service provider class
make:request Create a new form request class
make:resource Create a new resource
make:rule Create a new validation rule
make:scope Create a new scope class
make:seeder Create a new seeder class
make:test Create a new test class
php artisan make:notification InvoicePaid --markdown=mail.invoice.paid


Migrate Commands
migrate:fresh Drop all tables and re-run all migrations
migrate:install Create the migration repository
migrate:refresh Reset and re-run all migrations
migrate:reset Rollback all database migrations
migrate:rollback Rollback the last database migration
migrate:status Show the status of each migration

Storage Commands
storage:link Create the symbolic links configured for the application

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


