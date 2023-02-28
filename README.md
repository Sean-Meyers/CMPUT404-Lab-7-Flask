# CMPUT404-Lab-7-Flask

**Question 0:** What is the URL of your python flask_restfull code on github???
- https://github.com/Sean-Meyers/CMPUT404-Lab-7-Flask/blob/main/hello.py

**Question 1:** How are Flask and Django different? What does Django provide for you that Flask does not?
- Django is bigger, heavier, more complete web framework... Better for big web apps/pages. Flask is lighter weight, simpler, micro-framework better for simpler things idk.

**Question 2:** What does REST stand for? When I say something is RESTful, what does that mean?
- Representational State Transfer.
- Something that is RESTful conforms to the REST architectural style, so that means resources are transfered as representations, communication is stateless, and all that other stuff too or something.

**Question 3:** What does CRUD stand for? For each letter in CRUD, give the associated HTTP method.
- Create: PUT (?)
- Retrieve: GET
- Update: POST
- Delete: DELETE

**Question 4:** What do HTTP 1XX Status Codes mean? HTTP 2xx? HTTP 3xx? HTTP 4xx? HTTP 5xx?
- 1xx: Info
- 2xx: Success
- 3xx: Redirects
- 4xx: Client side errors
- 5xx: Server side errors

**Question 5:** What is an XSS attack? Provide one way a site can be vulneratble to an XSS attack.
- Cross Site Scripting Attack
- An attack targeting an end user where arbritry code is injected into a the user's browser when they access vulnerable sites.
- Way: HTML code that doesn't sanitize inputs, so malicious actors can just yeet malicious code into your HTML which then gets executed when the site is opened by a user.

**Question 6:** What does CORS stand for? What situation in web application development will you need to implement CORS protection?
- Cross Origin Resource Sharing or something.
- Sharing resources between different hosts.
- Analogy: "Don't share your wallet with strangers": Don't share your resources with hosts you don't know.
