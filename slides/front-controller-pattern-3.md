###  Front Controller Pattern

4. A combination of the URI path and Request Method (and possibly other criteria) is used to locate an Action on a Command object, this is known as Routing.

    1. If the path encodes a valid route then the Handler creates (or retrieves from cache) the Command object and invokes the Action.

    2. If the Action cannot be located the Handler returns a 404, "Not Found" error.

