# Frontend for SPA «ПомойАвто»

It is a frontend for single page application. It's the example using [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS).
The logic assumes the following:
1. User types email and password.
2, The server sends the AJAX request.
3. The server registers the user and take cookies.
4. The frontend redirects to a page with a list of car users.
5. The frontend requests data from the server.


# Deploy on localhost

Example of frontend launch on Linux, Python 3.5:

```bash

cd static/
python3 -m http.server 8000

```

Open page [127.0.0.1:8000](http://127.0.0.1:8000) in browser.


# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
