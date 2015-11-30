# My_Gravatar

The gravatar module and it provides data from Gravatar

# Installation
my_gravatar is available on PyPI:

    $ pip install my_gravatar

# Ussage
You should import the library and call the method gravatar, in this method you should put a email, and this method returns a dictionary with data(username, profile_url, img, name, city, full_name) 

    $ from my_gravatar import gravatar
    $ profile = gravatar('<email>')
    $ print(profile)

