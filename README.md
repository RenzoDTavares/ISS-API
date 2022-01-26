# API-ISS 🌎

  The International Space Station (ISS) is a large spacecraft in orbit around Earth. It serves as a home where crews of astronauts and cosmonauts live. The space station is also a unique science laboratory. Several nations worked together to build and use the space station. The space station is made of parts that were assembled in space by astronauts. It orbits Earth at an average altitude of approximately 250 miles. It travels at 17,500 mph. This means it orbits Earth every 90 minutes. NASA is using the space station to learn more about living and working in space. These lessons will make it possible to send humans farther into space than ever before.

  So, we use the API of ISS to get his position, using 
  
  ```
  response = requests.get(url="http://api.open-notify.org/iss-now.json")
  ```
  
  After that we get our position using the API from Sunrise Sunset to get the time of our location, so we compare the time of the ISS and our location and get our position with a marge of five ranges. Finishing, we check if the result is True for all conditions and if it is True, we sent an e-mail for another one to look up.
