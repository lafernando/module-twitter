# Ballerina Twitter Connector Test

The Twitter connector allows you to tweet, retweet, untweet, and search for tweets through the Twitter REST API.
It handles OAuth 2.0 authentication. You can also retrieve and destroy a status, retrieve closest trend locations,
and top trends using the connector.

## Compatibility
| Ballerina Language Version | Twitter API version  |
| -------------------------- | -------------------- |
| Swan Lake                  | 1.1                  |


###### Running tests

1. Set the following environment variables in relation to the Twitter account:
    
    ```.conf
    CLIENT_ID
    CLIENT_SECRET
    ACCESS_TOKEN
    ACCESS_TOKEN_SECRET
    ```
2. Navigate to the folder module-twitter

3. Run tests :

    ```ballerina
    bal test 
    ```
