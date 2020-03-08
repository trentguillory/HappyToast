# HappyToast

A very simple way to show toast messages.

Part of **HappyPath**: opinionated components for building apps really fast.

# HappyPath key tenants:
1. Prioritize Speed of development & stability
2. Are not flexible by design.  Get it up and running fast. Fork to customize. 
3. Opinionated to get the job done in its most common use case.  
4. Work in as little lines as possible and are easy to read.

# How to use
```
let viewController = UIViewController() 
viewController.showToast(message: "Hi there!")
```

**Or on Views or Windows:**
``` 
view.showToast(message: "Works on views!")
window.showToast(message: "Works on windows!")
```

**Change the style:**

``` 
view.showToast(message: "Works on views!", type: .success)

window.showToast(message: "No Internet connection", type: .warning)

viewController.showToast(message: "Server failed to connect", type: .failure)
```
