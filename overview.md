# A Brief Overview...

## Controllers and Views

To get a Rails app to do anything, you need to create at minimum a **controller** and a **view**. 
A *controller*'s purpose is to receive specific requests for the application. **Routing** decides
which controller receives which request. Often, there is more than one route for a controller, and
different routes can be served by different **actions**. Each action's purpose is to collect information
to provide it to a **view**. Conncecting controllers and actions to incoming requests is achieved using the *routing file*.

A *view*'s purpose is to display this information in a human-readable format. It is important to understand that
it is the controller that retrieves the information, while the view is only responsible for displaying it. 

A **resource** is a collection of similar objects. You can create, read, update, and destroy items for a resource, and these
operations are referred to as *CRUD* operations. Rails provides a ```resources``` method which can be used to declare a 
standard REST resource. The actions of our controllers perform CRUD operations on elements of our resource. These actions collect information from the resource and populate *templates* to generate views.
 
## Models

Models in Rails use a singular name, and their corresponding database tables use a plural name. 

