# gradient-xscape
This project allows users to select a color from a gradient background, and based on the chosen color, it displays a collection of movies whose posters share similar colors. The aim is to provide an interactive experience that connects visual aesthetics with movie recommendations.

**HOW IT WORKS** ❓

**Color Selection:** 

Users choose a color from the dynamic gradient background on the website. Once the color is selected, it is "locked in" by the user.


**Hex Code Recording:** 

The hex code of the selected color is recorded and sent to the back end of the website.


**Color Extraction:** 

Using the Color Thief library, the system extracts the dominant color from movie posters fetched from the TMDb API.


**Colour Matching:**

The selected color's hex code is compared with the dominant colors from the movie posters. Even if there's no exact match, movies with similar colors are displayed based on a color similarity calculation.


**Movie Display:**  

Films/Anime with matching or closely related colors are shown to the user, providing a unique movie browsing experience based on color preferences.


**TECHNOLOGIES USED** 🔋 

HTML/CSS: For the structure and styling of the website.      

JavaScript: To handle user interaction, color selection, and dynamic content.  

TMDb API: To fetch movie posters and related data.  

Color Thief: To extract the dominant color from images.
Learning Goals  



**This project allowed me to practice key web development skills such as:**

Working with APIs (TMDb API for movie data).
Handling dynamic user input and interacting with the DOM (Document Object Model).
Implementing color manipulation techniques (hex to RGB conversion, color similarity algorithms).
Integrating third-party libraries to enhance functionality (Color Thief for color extraction).
By building this project, I gained valuable experience in front-end development, API integration, and problem-solving, while creating an engaging and visually-driven web experience for users.

