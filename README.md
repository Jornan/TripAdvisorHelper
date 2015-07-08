#TripAdvisorHelper
This project is in a very early stage, just testing at the moment ...

Documentation and proper code will be uploaded soon.

#Example

Import framework
```
import TripAdvisor
```

Create a helper object with an API key

```
let helper = TripAdvisorHelper(APIKey: "yourKey")
```

Call functions with completion handler to receive objects 

```
helper.locationForID(1164225, completion: { (location, error) -> Void in
    println("ID: \(location?.name)")
})
```