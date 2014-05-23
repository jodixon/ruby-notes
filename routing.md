#Routing

The routing system does two things: it maps requests to controller action methods,
and it enables the dynamic generation of URLs that can be used as arguments to methods
like *link_to* and *redirect_to*.

Each route specifies a pattern, which will be used both as a template for matching URLs
and as a template for generating them (REST).
