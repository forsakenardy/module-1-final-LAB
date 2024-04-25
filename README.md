# Module 1 ending exercises

The company you work for (CompuglobalHiperMegaNet) is developing a new website. The project manager has asked you to create a page where we display all the workers of the company.

This is the information we have about the workers:

```JSON
[
    {
        "name": "Michael Scott",
        "position": "Project Manager",
        "email": "michael.scott@compuglobalhipermeganet.com",
        "photo": "https://www.lavanguardia.com/uploads/2020/06/29/5fa91c5e49c91.jpeg",
    },
    {
        "name": "Dwight Schrute",
        "position": "Assistant to the project Manager",
        "email": "dwight.schrute@compuglobalhipermeganet.com",
        "photo": "https://s.yimg.com/ny/api/res/1.2/NSc3nWzMmEVxLXgx2N5LMA--/YXBwaWQ9aGlnaGxhbmRlcjt3PTY0MDtoPTQyNw--/https://media.zenfs.com/es/levelup_525/47b81f0779adb85592c63ebb7276c11a"
    },
    {
        "name": "Kilikolo",
        "position": "CTO",
        "email": "kilikolo@compuglobalhipermeganet.com",
        "photo": "https://m.media-amazon.com/images/I/61AwGJQu3CL._AC_UF894,1000_QL80_.jpg"
    },
    {
        "name": "Homer Simpson",
        "position": "Vice CEO",
        "email": "homer.simpson@compuglobalhipermeganet.com",
        "photo":"https://s1.eestatic.com/2018/05/02/bluper/bluper_304233574_169542942_1706x960.jpg"
    },
    {
        "name": "Morty Smith",
        "position": "Intern",
        "email": "morty.smith@compuglobalhipermeganet.com",
        "photo": "https://comicvine.gamespot.com/a/uploads/scale_medium/6/66303/4469088-tumblr_inline_n0aleph3fl1r8rr6o.jpg"
    }
]
```
Your goal is to create an html file with a script that generates a card for each worker. The card should contain the information and picture of each character. Display the cards so they fit the screen and are responsive.
The image should be displayed on top of the card, followed by the name, position and email of the worker.

## Iteration 1: Create the HTML structure
Create the HTML structure for the page. You should have a container for the cards.

## Iteration 2: Link the css
Add the css to your page and start adding some styles. The container should be perfectly centered in the middle of the screen.

## Iteration 3: Add the array of workers in your script

## Iteration 4: Create the forEach loop
Now that we have our array ready, we can start creating the cards.
The first step is to create a forEach loop that iterates over the array of workers.
Let's create that loop and console log each worker to check if everything is working correctly.


## Iteration 5: Create the cards

Create a script that generates a card for each worker.
Here's an example of how a card can look like:

```html
<div class="card">
    <img src="https://example.jpeg" alt="Michael Scott">
    <h2>Michael Scott</h2>
    <h3>Project Manager</h3>
    <p>
        <a href="mailto:michael@exampleo.com">
            mailto:michael@exampleo.com
        </a>
    </p>
    <button>See details</button>
</div>
```
But wait! Don't hardcode the information! Use the information from the array of workers to create the cards.

Do you remember the methods to create new elements in the DOM?
```javascript
const card = document.createElement("div") // creates a new div element
```
I'm not going to tell you how to add classes or ids to the elements! 🤐

Don't forget to append the cards to the container!

```javascript	
document.querySelector(".container").appendChild(card) // this is just an example, you should use your own code
```

## Iteration 6: Details button
Each card should have a button that takes us to a **new page** with only the information of that worker. 

Do you remember how to link to a new page?
```html
<a href="./new-page.html">Go to new page</a>
```

After this amazing and painfull iteration, you are ready to start working with React! 🚀