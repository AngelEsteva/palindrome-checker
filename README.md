# palindrome-checker
This project is a simple Palindrome Checker built with Spring Boot. It exposes a RESTful endpoint that allows you to check if a given phrase is a palindrome or not.

Features

    REST API: A simple API that receives a phrase via a URL parameter and checks whether the phrase is a palindrome.
    Case and Space Insensitive: The checker removes spaces and ignores letter casing to make the palindrome check more robust.
    Custom Message: The response includes a message indicating whether the input phrase is a palindrome or not.

# How It Works

The API has the following endpoint:

    GET /check-palindrome/{phrase}

Where {phrase} is the phrase you want to check. The API returns a message indicating whether the phrase is a palindrome or not.
