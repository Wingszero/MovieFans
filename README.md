Description:
A movie & social website based on TMDB data. 
Used Oracle DB on AWS RDS for managing movie data, Berkeley DB for user data and EC2 for running web server. 
Features: search, movie/user info page, follow, group, hashtag(“#”), tag(“@”), activities timeline, notification, etc. 
Added DB indexing and query caching for optimization.
Be awarded the Most Technically Challenging Project in course CIS 550 (Database and Information Systems, 15 Fall).

Roadmap:
Local testing:
1 cd server/
2 sh build.sh
3 sh run.sh
4 it will build servlet.war and use jetty-runner to setup the localhost server
5 goto http://localhost:8080/
