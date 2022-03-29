# Raspberry Pi-based Canvas-API consuming machine
I do not really have a name for this machine just yet, but it is just a small project. Here are the functional requirements:
1. Communicate with the Instructure Canvas through the available RESTful API. 
    1. Authenticate and Authorization with personal account.
    2. Perform GET request to get upcoming assignments, events.
    3. Get a list of subjects that are currently enrolled to the account.
2. Display results from the Instructure Canvas RESTful API in an LCD module connected to the Raspberry Pi.
3. Allow navigation through different menus implemented through the concept of finite state machines. 