# Plus 1 Labs iOS Senior Engineer Technical Interview #

## Architecture ##
Our product team has tasked us with creating an app that functions similar to Tinder.  A user may create a profile, grant location access, and search for other users within their area and search parameters.  If both users approve of each other's profiles then they are entered into a private chat with one another.  The backend teams have committed to creating any API endpoints that may be needed and our first step is to submit the preliminary designs for the iOS application.  Create a design document that outlines major sections of the application, what architecture you feel would serve this project best, and an example diagram of the objects needed to make the swiper function.

## Coding ##
The backend teams have provided us with two endpoints.  The first fetches a user's profile that has been previously saved by another area of the application and the second provides a selection of other users to appear in search.  Using the provided endpoints, create a class that can fetch a user's profile, use that profile to acquire a set of other users from search, and arrange the results into an array that is based on proximity and shared interests.