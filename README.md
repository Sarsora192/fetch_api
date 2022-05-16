# fetch_api
A simple project showing the content of JSON files on an an HTML page using javascript's `Fetch` api.


## Description 
The HTML page has 3 main sections: `users.json`, `companies.json` and `books.json`. each JSON file was created using [fakerAPI](https://fakerapi.it/en), file description are as follows:

* **Users**: contains mock-user data which are: `id - frst_name - last_name - email`.
* **Companies**: contains mock-companies data which are: `id - company_name - city - email`.
* **Books**: contains mock-books data which are: `id - book_name`.

## The Fetch API
Javascript's fetch API allows us to handle files using http requests such as `GET`/`POST` using its methods and functions without middling with the complexities of these requests.
In this program, we use the fetch API to get the locally stored JSON files and load them on the HTML page by the following procedures, these procedures are repeated for each JSON file:
* Get the content of the JSON file by aggregating `fetch` with `then`.
* Creating an HTML element using js's `document` methods to create the proper containers for the data fetched by the API.
* Assigning the data to its proper location within the HTML elements.
* Appending the container HTML element to the main section element.

The HTML file also has a search bar for each section to search for any of the mentiooned data above.

Checkpoints drive folder [here](https://drive.google.com/drive/folders/1ojO0r-izaRFOH6Y2T_SoAd_sfZ6L7i71?usp=sharing_eip_m&ts=621c95b5).
