# What is the Web?
Network of servers and services

URL (Uniform resource locator) - helps locate resources on the internet
1. Scheme - internet protocol to retrieve data over the internet
2. Domain - which server to contact
3. Location - domain with additional info 
  - port
  - username
4. Path - file on web server to fetch
5. Query - web server processes something related to the arguments here
6. Fragment - tells browser to scroll to a specific part of the web page

![Capture](https://github.com/user-attachments/assets/9dd2c0a9-24f2-4194-9817-cdcd13416dad)

### How do web browsers communicate with web servers?
Http (Hypertext transfer protocol) - protocol to request and retrieve data from a web server - request/response model
![Capture](https://github.com/user-attachments/assets/ae082824-1ee0-424b-98a3-f72ee5dc26ea)

1. GET request - fetches server side data
2. POST - updates server side data

- REQUEST - method/path/version - header and body - headers have some metadata
![Capture](https://github.com/user-attachments/assets/aa559724-c86e-4bb2-bac3-8dda03d6c662)

![Capture](https://github.com/user-attachments/assets/e32a030d-4c97-498b-bea0-72aba1a1a6dd)


- RESPONSE - status code, headers with metadata, data (in the body) - headers contain cookies (state between server and browser like login status)
            - loading resources from the server
![Capture](https://github.com/user-attachments/assets/efff4f1e-df4e-4383-b393-f3f19e7fae69)

![Capture](https://github.com/user-attachments/assets/b097cf69-021e-4f32-9b39-eee0f6138c98)


- HTTP is stateless: hence lifetime is limited and disconnects
- 
