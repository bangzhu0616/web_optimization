### Getting started

1. run a local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

2. Download and install [ngrok](https://ngrok.com/) to make your local server accessible remotely.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ngrok 8080
  ```
Then you can see the remote url to your website.


### How I optimize the website

1. I inlined all css files and javascript files.
2. I compressed all image files to smaller size.
3. I added <meta name=viewport content="width=device-width, initial-scale=1"> to pizza.html to make this page mobile friendly.
4. I duplicated a pizzeria image and resize it for main page.
5. I optimized the resizePizza function in views/js/main.js
