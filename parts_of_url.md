## URL (Uniform Resource Locator)

1. ## Part of URL
Scheme/Protocol(https://)
 - what it does: this specifies the method used to access the resource. Common examples are `http`, `https`, `ftp` and `mailto`.

 - analogy: like a mode of transport-are you flying,driving, or taking a train?
 think of `http` as a fast jet that is used to fetch resources from the web.

2. ## Subdomain (optional)
 - what it does: identifies a subdivision of the main domain, often used for specific like `www`, `blog` or `mail`.

 - analogy: like a specific department in a building (eg. "Customer service department")

 - example: `www` in `https://www.example.com`

3. ## Domain (example.com)
 - what it does: the main name of the website, this points to a specific web server.

 - analogy: the building's address. where it is located

 - example: google.com

4. ## Top-Level Domain (TLD) (.com)
 - what it does: indicates the domain's category or country code (.com,.org,.edu,.ke,.gov)
 - analogy: like the zip code or country code in the address

5. ## Port (:443) (optional)
 - what it does: specifies the port number used for communication between the browser and server.
 - default port is 80 for http and 443 for https
 - analogy: like a specific door number or entrance to the building

6. ## Path:
 - what it does: specifies the specific resource or page on the server
 - analogy: the room or office number in the building

7. ## Query
 - What it does: contains parameters that provide additional data to the server, often used in search queries or filtering.

 - example: `?search=example`

8. ## fragment/anchor (#section1)
 - what it does: points to a specific part of a webpage,like a section or an element
 - example: `#section1`

```jsx
Complete Example
Here’s a fully annotated URL:
https://www.example.com:443/about?search=example#section1

https:// → Protocol
www. → Subdomain
example.com → Domain name
.com → Top-level domain
:443 → Port
/about → Path
?search=example → Query
#section1 → Fragment/Anchor
```