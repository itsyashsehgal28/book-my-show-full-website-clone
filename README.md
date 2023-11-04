### book-my-show-full-website-clone

### How To Start The Project 
>>      npm i -g create-react-app (install create react app and make it global so that its not only for the C drive)
>>      npx create-react-app .    (. means take the name of the folder , if you want a different name you can type instead of .)
                                    if . doesnt work because of uppercase make a new repository with name in small case 
>>      npm start

### Technologies Used : 
# 1.        FRONTEND : Html5 , Css3 , JavaScript , React.js , TailWind 
                        >> React-slicks for carousel (instead of bootstrap)
                        >> React-icons for icons (alternative for google font icons)
                        >> React-context-api for state management (instead of redux , both do the same thing)

# 2.        BACKEND :  Node.Js , Express.Js
# 3.        DATABASE : Movie Database 


# Pages are the different webPages needed in the Website , each page can have 1 or more components in it

# Layouts / HOCs are the redundant code (repetitive code) present in every page which is stored at 1 place and can be called out at    any time , there can be more than 1 HOC in a page (Eg: Navbar , Footer)


###     Pages:
>>          Home.Page.jsx (Default.Hoc.jsx)
>>          Movie.Page.jsx (Movie. Hoc. jsx)
>>          Play.Page.jsx (Default.Hoc.jsx)


###     HOCs/Layouts:
>>          Default.Hoc.jsx
>>          Movie.Hoc.jsx


###     Components:
>>          Cast                    Cast.Component.jsx                  (getting all the movie cards)

>>          Entertainment           EntertainmentCard.Component.jsx     (Entertainment section)

>>          HeroCarousel            HeroCarousel.Component.jsx          (main carousel or hero banner)
                                    Arrows.Component.jsx                (arrows to go left or right)

>>          MovieHero               MovieHero.Component.jsx             (info about the actors in the movie)
                                    MovieInfo.Component.jsx             (description of the movie)

>>          Navbar                  Navbar.Componenet.jsx               (navbar default)
                                    MovieNavbar.Component.jsx           (navbar for movie page)

>>          PaymenModal             Payment.Component.jsx               (payment gateway , razorpay)

>>          PlayFilters             Filters.Componenet.jsx              (Filters for search window)
    
>>          Poster                  Poster.Componenet.jsx               (Posters for the movie)

>>          PosterSlider            PosterSliderComponenet.jsx          (Poster Slider Carousel)















































































### THIS CAME PRE WRITTEN AFTER CREATING REACT APP


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
