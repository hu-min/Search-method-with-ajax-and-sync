# Search-method-with-ajax-and-sync
When you use search bars in any website let's say Google each character you type at google makes an XML HTTP Request to fetch data from API or any JSON file either external or inside the server.    If you used Asynchronous in this situation and you used the search bar before data is completely fetched, It won't output anything because the data is not fetched yet coz it works Asynchronously the two parts work independently, and it will cause errors in the console if you tried to type.    Hence search bar depends on the data fetched from the API or JSON. So the data should be completely fetched first then you can use search bar. In this case Synchronous technique would be the best solution, the data will be fetched first synchronously with using search bar

## live porject
- https://ahmedazzam-web.github.io/Search-method-with-ajax-and-sync/
