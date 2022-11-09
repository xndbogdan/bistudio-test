# Important Considerations
- Use Migration and Seed to create database and records. 
- Database should contain at least 50k users, 1000 blogposts and every blogpost have at least 50 comments.
- When deleting the comment or blog post it should be soft-deleted and moved to the trash bin from which can be deleted permanently.
	- The comment or blog post older than 3 hours should be deleted automatically and put into trash bin. 
	- Admin can restore comment or blog post
# Guests can
- Register via an endpoint with the following parameters
	- Name 
	- Surname 
	- Nickname 
	- Phone 
	- Email 
	- Address 
	- City 
	- State 
	- ZIP
	- Generate the Username from full surname and 3 letter from first name o Example: Johnny Depp will have username “deppjoh”
# Logged user can 
- Add new comment o Maximum length for comment is 255 characters o Provide login and password for example user
- View individual blog posts in a separate page
- View comments for a blog post
# Logged moderator can
- Create a blogposts (Maximum length for subject on the new blog post is 64 characters)
- Provide login and password for example user
# Logged admin can
- Provide login and password for example user