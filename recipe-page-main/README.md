# Frontend Mentor - Recipe page

## Table of contents

  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



### Links

- Solution URL: [Github](https://your-solution-url.com)
- Live Site URL: [Vercel](https://your-live-site-url.com)

## My process

### Built with

- HTML5 
- CSS
- Dekstop-first workflow

### What I learned

In this challenge I overcame the obstacle of learning how to adjust the tr and td tags inside a table to have them spread apart. I accomplished this by giving the td class names and adjusting their paddings accordingly to fit the finished design.


```html
 <table>
            <!-- calories -->
            <tr>
              <td class="nutri-category">Calories</td>
              <td class="nutri-value">277kcal</td>
            </tr>
            <!-- calories -->
            <!-- carbs -->
            <tr>
              <td class="nutri-category">Carbs</td>
              <td class="nutri-value">0g</td>
            </tr>
            <!-- carbs -->
            <!-- protein -->
            <tr>
              <td class="nutri-category">Protein</td>
              <td class="nutri-value">20g</td>
            </tr>
            <!-- protein -->
            <!-- fat -->
            <tr>
              <td class="ft-value">Fat</td>
              <td class="grams-value">22g</td>
            </tr>
            <!-- fat -->
          </table>
```
```css
main {
    display: grid;
    height: 240vh;
    place-content: center;
}
```

### Continued development

Coming from being an email developer, I'd like to dive in more to understanding table adjustments in regular built websites with html, css, and css frameworks in the future.



### Useful resources

- [Developer Mozilla](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol) - This helped me for figuring out how to create both the structure of my ordered and unordered list.


## Author

- Website - [Eric Aguayo](https://www.ericaguayo.com)
- Frontend Mentor - [@EAguayodev](https://www.frontendmentor.io/profile/EAguayodev)
- Twitter - [@yeric_emaildev](https://www.twitter.com/eric_emaildev)
