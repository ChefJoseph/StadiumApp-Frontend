<h1>Primetime Stadium Delivery App</h1>
<p float="center">
  <img src="https://github.com/ChefJoseph/StadiumApp-Frontend/blob/main/assets/Simulator%20Screen%20Shot%20-%20iPhone%2013%20-%202022-10-23%20at%2013.58.25.png" width="200" />
  <img src="https://github.com/ChefJoseph/StadiumApp-Frontend/blob/main/assets/Simulator%20Screen%20Shot%20-%20iPhone%2013%20-%202022-10-23%20at%2013.59.09.png" width="200" /> 
  <img src="https://github.com/ChefJoseph/StadiumApp-Frontend/blob/main/assets/Simulator%20Screen%20Shot%20-%20iPhone%2013%20-%202022-10-23%20at%2013.59.13.png" width="200" />
</p>
<p float="center">
  <img src="https://github.com/ChefJoseph/StadiumApp-Frontend/blob/main/assets/Simulator%20Screen%20Shot%20-%20iPhone%2013%20-%202022-10-23%20at%2014.00.38.png" width="180" />
  <img src="https://github.com/ChefJoseph/StadiumApp-Frontend/blob/main/assets/Simulator%20Screen%20Shot%20-%20iPhone%2013%20-%202022-10-23%20at%2014.01.03.png" width="180" />
  <img src="https://github.com/ChefJoseph/StadiumApp-Frontend/blob/main/assets/Simulator%20Screen%20Shot%20-%20iPhone%2013%20-%202022-10-23%20at%2014.01.33.png" width="180" />
  <img src="https://github.com/ChefJoseph/StadiumApp-Frontend/blob/main/assets/Simulator%20Screen%20Shot%20-%20iPhone%2013%20-%202022-10-23%20at%2014.00.51.png" width="180" />
</p>
<br>
<h3>Purpose:</h3> Food and merchandise delivery app for Dodgers Stadium (sporting event).
<br>
<h3>Technologies:</h3> React Native, Redux, Rails, Expo, Axios, Async Storage, devise-token-auth.
<br>
<h3>User Stories:</h3>
a) A Spectator that doesn’t want to miss the action, or is buying for the group.
<br>b) A Parent with toddlers or children who will pay for the convenience of having food delivered. 
<br>c) An Elderly or Disabled spectator that struggles with access (e.g. stadium stairs).
<br>
<h3>MVP goals:</h3> Login Auth, Create profile, Model/validations, CRUD, Database, Shopping cart, Separate Client and Restaurant Views/Authorization, Camera access for avatar and ID, Pop-out Menu: Referral page, Help page
<br>
<h3>Figma:</h3>
https://www.figma.com/file/CpSa8Ov4jd6rZ1nlc9UwjU/GOOGLE-UX--STADIUM-DELIVERY-APP?node-id=145%3A422
<h3>Wireframe:</h3>
<image src="https://github.com/ChefJoseph/StadiumApp-Frontend/blob/main/assets/Stadium-Wireframe.png"/>
<h3>Mockup:</h3>
<image src="https://github.com/ChefJoseph/StadiumApp-Frontend/blob/main/assets/Stadium-%20Mockup.png"/>
<br>
<h3>Stretch goals:</h3> QR code scanning for ticket confirmation, Photo Storage, Checking if ticket is valid, Push notification, E-mail or text confirmation for signup/receipt, Payment type input, Mock Payment processing(Stripe?), Icon animations, Multiple vendors, Multiple stadiums, Analytics for Vendor UI, Google maps library for location/delivery rendering.
<br>
Implementing a camera for ticket scanning. I used a react-vision-camera library. It crashed my app and luckily I was able to roll back saved data on github. After completing the food delivery app portion, I want to include the camera so that the user can quickly provide information to their seat. 
<br>
Further development: I am working on DRYing the code. The bulk of React and Native was similar enough like using reusable declarative components. However there were many differences including syntax, react-router vs react native naivation, local storage vs async storage, and CSS formatting. Native doesn’t leverage CSS and HTML so I learned to utilize Stylesheet. Some element tags were also different &lt;p&gt as &lt;text&gt, and &lt;div&gt as &lt;view&gt
