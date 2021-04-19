# Example-Requests-Method-Post-To-Wordpress-Login

This is only for education, so it's best not to abuse it.

## Installing Module Requests

You can install module requests first, if you haven't installed them

```bash
pip install requests
```

## Example Code

I tried it in the interpreter

```python
Python 3.8.5 (default, Jan 27 2021, 15:41:15) 
[GCC 9.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import requests
>>> url = "https://example.com/wp-login.php"
>>> data_payload = {'log':'USERNAME','pwd':'PASSWORD'}
>>> req = requests.post(url, data=data_payload)
```

If the Requests Post is successful, it will lead to the dashboard, you can try it using the url method

```python
>>> print(req.url)
```

#### Thanks :)

