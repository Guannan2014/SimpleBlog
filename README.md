Deployment URL: http://elite-impact-718.appspot.com/blog

This application is a web blog, and it is deployed on Google App Engine, based on webapp2 framework Features:
•Anyone can view a list of blogs, and can register for an account
•only registered users are allowed to post to the blog after sign in
•memcache is used so that DB is only accessed on writes
•The app has a simple JSON api. Add ".json" will return JSON object of the blog
