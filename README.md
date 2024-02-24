# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Links

- Solution URL: (https://github.com/mujtabahassan1995/Main-Page-of-Recipe-in-Responsiveness)
- Live Site URL: (https://mujtabahassan1995.github.io/Main-Page-of-Recipe-in-Responsiveness/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Box Model
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library

### What I learned

I actually work on react in order to enhance my skills on a new and in demand technology. I provide some of the areas which help me to boost my skills and knowledge. In the future, better help me to create my porfile and portfolio. I learn how to install react and how to return html codes from a javasscript funtion which is a core concept of a react and how to upload a local font in a CSS. 

To see how you can add code snippets, see below:

```html
<body>
  <div id="root">

  </div>
</body>
```
```css
@font-face {
    font-family: 'young_serifregular';
    src: url('/public/assets/fonts/young-serif/youngserif-regular-webfont.woff2') format('woff2'),
         url('/public/assets/fonts/young-serif/youngserif-regular-webfont.woff') format('woff'),
         url('/public/assets/fonts/young-serif/YoungSerif-Regular.ttf') format('truetype');
    font-weight: normal;
    font-style: normal;

}```
```js
function App() {
  return (
    <><div className="main">
      <div className="recipe-image">
        <img src='./assets/images/image-omelette.jpeg' alt='Omelette Recipe'/> 
      </div>
      <div className='recipe-descriptions'>
      <h1>
        Simple Omelette Recipe
      </h1>
      <p className='desciption-same-color'>
        An easy and quick dish, perfect for any meal. This classic omelette combines beaten eggs cooked
        to perfection, optionally filled with your choice of cheese, vegetables, or meats.
      </p>
      <div className='prepare-options'>
          <h3>
            Preparation time
          </h3>
      <div className='options'>
        <ul>
          <li>
            <span className='list'>Total: <span className='desciption-same-color'>Approximately 10 minutes</span></span>
          </li>
          <li>
            <span className='list'>Preparation: <span className='desciption-same-color'>5 minutes</span></span>
          </li>
          <li>
            <span className='list'>Cooking: <span className='desciption-same-color'>5 minutes</span></span>
          </li>
        </ul>
      </div>
        
      </div>
      <div className='ingredients'>
          <h2>
            Ingredients
          </h2>
          <ul>
            <li>
            <span className='list'>2-3 large eggs</span>
            </li>
            <li>
            <span className='list'>Salt, to taste</span>
            </li>
            <li>
            <span className='list'>Pepper, to taste</span>
            </li>
            <li>
            <span className='list'>1 tablespoon of butter or oil</span>
            </li>
            <li>
            <span className='list'>Optional fillings: cheese, diced vegetables, cooked meats, herbs</span>
            </li>

          </ul>
      </div>
      <hr className='solid'></hr>
      <div className='instructions'>
          <h2>
            Instructions
          </h2>
          <ol>
            <li>
            <div className='list'>Beat the eggs: <span className='desciption-same-color'>In a bowl, beat the eggs with a pinch of salt and pepper until they are well mixed. You can add a tablespoon of water or milk for a fluffier texture.</span></div>
            </li>
            <li>
            <div className='list'>Heat the pan: <span className='desciption-same-color'>Place a non-stick frying pan over medium heat and add butter or oil.</span></div>
            </li>
            <li>
            <div className='list'>Cook the omelette: <span className='desciption-same-color'>Once the butter is melted and bubbling, pour in the eggs. Tilt the pan to ensure the eggs evenly coat the surface.</span></div>
            </li>
            <li>
            <div className='list'>Add fillings (optional): <span className='desciption-same-color'>When the eggs begin to set at the edges but are still slightly runny in the middle, sprinkle your chosen fillings over one half of the omelette.</span></div>
            </li>
            <li>
            <div className='list'>Fold and serve: <span className='desciption-same-color'>As the omelette continues to cook, carefully lift one edge and fold it over the fillings. Let it cook for another minute, then slide it onto a plate.</span></div>
            </li>
            <li>
            <div className='list'>Enjoy: <span className='desciption-same-color'>Serve hot, with additional salt and pepper if needed.</span></div>
            </li>
          </ol>
        
      </div>
      <hr className='solid'></hr>
      </div>

      <div className='nutrition'>
          <h2>
            Nutrition
          </h2>

          <p className='desciption-same-color'>
            The table below shows nutritional values per serving without the additional fillings.
          </p>
          <table className='table'>
            <tr className='border-bottom'>
              <td>
                Calories
              </td>
              <td className='values'>
                277kcal
              </td>
            </tr>
            <tr className='border-bottom'>
              <td>
                Carbs
              </td>
              <td className='values'>
                0g
              </td>
            </tr>
            <tr className='border-bottom'>
              <td>
                Protein
              </td>
              <td className='values'>
                20g
              </td>
            </tr>
            <tr>
              <td>
                Fat
              </td>
              <td className='values'>
                22g
              </td>
            </tr>
            </table> 
      </div>
    </div></>
  );
}}
```

### Continued development

I highlight the react javascript sections. In the future projects i want to refine these section because in a react we develop each section as a component individually. In this project i develop all the components in a single javascript funtions simultaneously.


## Author

- Frontend Mentor - [@mujtabahassan1995](https://www.frontendmentor.io/profile/mujtabahassan1995)


## Acknowledgments

Please provide your feedback regarding my projects in order to enhance my skills efficiently.
