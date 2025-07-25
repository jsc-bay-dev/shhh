Purpose: an application that allows hosts and customers to navigate a secret network of restaurants, bars and cafes. 

features:
- we want the application to be as discreet as possible. so we'll make it a cli tool.
- hosts : 
    - will need an admin's approval to share their space with our clients
    - space: { type, name, hosts, description, general location, hours (tentative), menu (tentative), rsvp }
    - directions will be provided upon request using nearby landmarks.
    - option of having clients fill out questionairres prior to  
- clients
    - { username, password, dob}
    - requires personal invite to create an account
    - may request reservations
    - once reservation has been made, they may answer the questionairre if provided

technologies: 
- rust
- sql?
- mysql?


Steps
1. Scaffold Rust CLI project
2. Set up database (SQLite)
3. Define data models for hosts, clients and spaces
4. Authentication and invitation logic
5. Adjust CLI commands