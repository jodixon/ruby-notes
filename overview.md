# A Brief Overview...

## Controllers and Views

To get a Rails app to do anything, you need to create at minimum a **controller** and a **view**. 
A *controller*'s purpose is to receive specific requests for the application. **Routing** decides
which controller receives which request. Often, there is more than one route for a controller, and
different routes can be served by different **actions**. Each action's purpose is to collect information
to provide it to a view.

A *view*'s purpose is to display this information in a human-readable format. It is important to understand that
it is the controller that retrieves the information, while the view is only responsible for displaying it.
