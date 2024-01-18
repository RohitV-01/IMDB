Movie World Website:-
Welcome to the Movie World website! This simple web application allows users to search for movies and TV shows using the IMDb database. The website provides an easy-to-use interface for users to discover information about their favorite titles.

Features:-
1) Search Functionality: Users can enter the name of a movie or TV show in the search bar and click the "Search" button to retrieve relevant information.
2) Dynamic Display: The website dynamically displays information about the searched titles, including posters, release years, types, and top credits.
3) Responsive Design: The website is designed to be responsive, ensuring a seamless experience across different devices.

Technologies Used:-
1) Frontend Frameworks: Bootstrap 4.4.1 and Bootstrap 5.3.2
2) JavaScript Library: jQuery 3.7.1
3) Web Development: HTML5 and CSS3
4)API Integration: IMDb API (RapidAPI)

Getting Started:-
 To run the Movie World website locally, follow these steps:

1) Clone the repository: git clone [repository_url]
2) Open the index.html file in a web browser.
   
Usage:-
1) Open the Movie World website in your preferred web browser.
2) Enter the name of a movie or TV show in the search input.
3) Click the "Search" button to retrieve information.
4) Explore the displayed results, including posters and details about the titles.
   
API Integration:-
This website utilizes the IMDb API (RapidAPI) to fetch information about movies and TV shows. To modify the API request or integrate additional features, refer to the JavaScript code in the <script> tags in the HTML file.

    javascript
    Copy code
    // Modify the API request URL and headers as needed
    const xhr = new XMLHttpRequest();
    xhr.open('GET', 'https://imdb146.p.rapidapi.com/v1/find/?query=harry%20potter');
    xhr.setRequestHeader('X-RapidAPI-Key', 'YOUR_RAPIDAPI_KEY');
    xhr.setRequestHeader('X-RapidAPI-Host', 'imdb146.p.rapidapi.com');
    xhr.send(data);
    Replace 'YOUR_RAPIDAPI_KEY' with your actual RapidAPI key.


Credits
* Bootstrap: Link to Bootstrap
* jQuery: Link to jQuery
* RapidAPI: Link to RapidAPI IMDb API
  
License
This project is licensed under the MIT License.

Feel free to contribute, provide feedback, or report issues! Enjoy exploring the Movie World.
