# MotoMenus-SaaS-API-Cron
A cron ECS task definition for running ECS Scheduled Tasks. Used for making calls to Laravel scheduling.

 Note: The only thing the cron repository is responsible for is running the Laravel schedule which should only be QUEUED JOBS or QUEUED CONSOLE COMMANDS.
 The schedule is triggered with the `php artisan schedule:run` command from the `MotoMenus-SaaS-API-Cron` scheduled task.
