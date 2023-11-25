 Puplove
 Puppies can find love


The Project:
Every dog owner knows the struggle of moving to a new place and not knowing anyone else with a dog. However, dogs need to socialize too! This is why I want to create Puplove.

Here is a simple flow for the user experience on Puplove:


Puplove is a dating site for dogs! Dog owners can create a profile for their pup, and start swiping through other dogs in their area. If they want to meet a dog, they can "like" their profile, and if that dog likes them back, it's a match! From there, the two users can decide to contact each other and organize a playdate for their dogs. If they don't like that dog, they can just "pass" it.

Other features include: editing the dog's profile, modifying the user settings, and a "previous" button to see the previous profile again.

The Team:
I am a dog enthusiast  who is passionate about coding but also like to keep it fun!

Ramy Mostafa - a Software Engineer.

Challenges:
Some transitions are not as fluid as expected, and due to API calls lag can be a bit off.
Issue when viewing on mobile.

List of components:
These components make up what a user experiences when they check out puplove. Each component contains the code for a specific page of the app. These components can be located in src/components.


Component
Description
Landing.vue
The landing page a user sees when they navigate to Puplove.
Login.vue
The login page. There's a link to go to the Signup page if a user hasn't signed up.
Matches.vue
Page where users can see the other users they've matched with. A match occurs when two users have liked each other.
Navbar.vue
The navigation bar that appears at the top of most every other component.
Settings.vue
Users can change their email address, display name, city, and zip code on this page.
Signup.vue
Signup page for users who do not have an account. It asks for a valid email address and for them to make and confirm a password.
Swiping.vue
The main page of Puplove where users can see another user's profile and choose whether to 'like' or 'pass.'
UserProfile.vue
Similar to Settings.vue, on this page the user can change their dog's information including likes, dislikes, and fun facts.




Technologies:

Architecture:

My web application is a single-page application, coded principally in Javascript. Puplove is front-end heavy, implying that I zeroed in my significant investment on fostering a basic yet simple to-utilize, and fun application. I planned the majority of the UI, utilizing plain CSS and some local Vue changes and animations.

Vue.js:
For this project, I decided to use Vue.js as it is simple to integrate and user-friendly, Vue is also designed to be very much adaptable to the project needs. Vue.js makes use of virtual DOM, a copy of the website’s original DOM is created so that an adequate amount of changes can be made without rendering the entire DOM and this minimizes the number of DOM manipulations needed to be handled by Vue.

Firebase:
I decided to go with Firebase for our backend/database as it provides all the functionality I need to develop this project such as authentication, database storage, and cloud storage. 
Firebase's quick database calls populate this information and help keep this functionality snappy.

Firestore:
Firestore provides a reliable and responsive solution to achieve a seamless experience. 

Images will be kept in the Firestore as a link to where they're held in cloud storage.
Cloud Firestore:
It provides straightforward implementation for users to upload their photo and a relatively quick way to call and display these images for users to sift through.

Related projects:

AirBnB Clone: a simple web app made in Python.

Simple Shell: a command line interpreter that replicates the sh program.
