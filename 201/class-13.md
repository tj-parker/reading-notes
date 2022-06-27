# Class 13 Reading Notes

## Local Storage

HTTP is stateless, meaning that when you use an application and then close it, its state will be reset the next time you open it. Local storage is a workaround, storing data on the users computer to be accessed when they re-open the application

loacl storage is quite insecure so it should not be used to store sensitive user information

local storage can only store strings in the different keys, so they woun't be stored correctly with objects. This can be worked around using the `JSON.stringify()` and `JSON.parse()` methods
