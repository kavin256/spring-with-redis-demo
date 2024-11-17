Redis is popular as a super fast in-memory data store mainly used for caching. 
But, there are tools offered by redis to operate redis for other tasks such as the main app database.

In the world of Spring, if we are going to use Redis as the main database, we can make use of the tool named Spring Data Redis to use Redis as a key value databse.
One thing to note here is that, even though we can technically use redis with out any other additional tool in an app, it will not be useful because,
the data that redis saves is hash data, which is not very useful for general database use.
Therefore, we use a tool called Spring Data Redis to make redis save data as key value pairs instead.
