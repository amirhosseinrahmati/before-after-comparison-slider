![before and after comparison slider](https://raw.githubusercontent.com/amirhosseinrahmati/before-after-comparison-slider/master/images/repo-intro-img.png "before and after comparison slider")

### Initializing
Import JavaScript code in your html:
`<script src="js/script.js"></script>`

Then give an id for each **div** element which has **bal-container** class:
```
<div id="one" class="bal-container">
...
<div id="two" class="bal-container">
...
```
At the end, initialize every element with the given id:
```
    <script>
        new BeforeAfter({
            id: '#one'
        });
        new BeforeAfter({
            id: '#two'
        });
		...
    </script>
```