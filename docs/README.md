#### BootstrapX = Bootstrap Examples

Testing components from Bootstrap in order to use them in current or future projects. Below are the ones that I used. For all the components below, there is code that would be in the '<body>' tag of the Set-Up code below. In addition, there is a picture detailing the result of each component. Tell me what you think and in addition, if i'm doing anything wrong.

### Setting Up

Below is everything needed, that I used, in my Bootstrap HTML documents. 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    	<meta charset="utf-8">
    	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.3/css/bootstrap.min.css" integrity="sha384-Zug+QiDoJOrZ5t4lssLdxGhVrurbmBWopoEl+M6BdEfwnCJZtKxi1KgxUyJq13dy" crossorigin="anonymous">
    
    	<title>
		Bootstrap Set-Up
    	</title>
</head>
<body>
	<h1>
      		Test
    	</h1>
    
	<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.3/js/bootstrap.min.js" integrity="sha384-a5N7Y/aK3qNeh15eJKGWxsqtnX/wWdSZSKp+81YjTmS15nvnvxKHuzaWwXHDli+4" crossorigin="anonymous"></script>
    
</body>
</html>
```



## Navbar
See the navbar in action at [https://bootstrapx.surge.sh/navbar](https://bootstrapx.surge.sh/navbar).

```html
<!-- Image and text -->
    <nav class="navbar navbar-light bg-light">
      <a class="navbar-brand" href="#">
        <img src="/Assets/max-logo.png" width="30" height="30" class="d-inline-block align-top" alt="">
        Max Shalom
      </a>
    </nav>
```

![](https://github.com/MaxShalom/BootstrapX/blob/master/docs/Component%20Example%20Pictures/navbar.png?raw=true)


## Jumbotron
See the jumbotron in action at [https://bootstrapx.surge.sh/jumbotron](https://bootstrapx.surge.sh/jumbotron).
```html
<div class="jumbotron">
      <h1 class="display-4">Hello, world!</h1>
      <p class="lead">Beer. Now there's a temporary solution. Duffman can't breathe! OH NO! Son, when you participate in sporting events, it's not whether you win or lose:
         it's how drunk you get. Homer no function beer well without.</p>
      <hr class="my-4">
      <p>Remember the time he ate my goldfish? And you lied and said I never had goldfish. 
        Then why did I have the bowl, Bart? *Why did I have the bowl?* 
        Donuts. Is there anything they can't do? Yes! I am a citizen! 
        Now which way to the welfare office? I'm kidding, I'm kidding. I work, I work.</p>
      <p class="lead">
        <a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a>
      </p>
    </div>
```

{% gist e57726dff969dab9eb866f5f179f9518 jumbotron.html %}

![](https://github.com/MaxShalom/BootstrapX/blob/master/docs/Component%20Example%20Pictures/jumbotron.png?raw=true)

## Cards
See the cards in action at [http://bootstrapx.surge.sh/cards](http://bootstrapx.surge.sh/cards) (with working buttons!).


### Card with Picture
```html
<div class="card" style="width: 18rem;">
	<img class="card-img-top" src="https://2.bp.blogspot.com/-HDAZ3X-b0r0/V3Wh6pCV-WI/AAAAAAAA57o/hI1KVFR2wYELGnlscZV4pbdaWsbV2U1igCLcB/s1600/Banff-National-Park-14.jpg" alt="Card image cap">
	<div class="card-body">
		<h5 class="card-title">Banff National Park</h5>
		<p class="card-text">Banff National Park is a beautiful place in Alberta, Canada.</p>
		<a href="https://www.banfflakelouise.com/" class="btn btn-primary">Go somewhere</a>
	</div>
</div>
```

![](https://github.com/MaxShalom/BootstrapX/blob/master/docs/Component%20Example%20Pictures/card-pictures.png?raw=true)

### Card with Links
```html
<div class="card" style="width: 18rem;">
	<div class="card-body">
		<h5 class="card-title">New York City</h5>
		<h6 class="card-subtitle mb-2 text-muted">NY, United States of America</h6>
		<p class="card-text">New York City is the most populous city in the United States, with an estimated 2016 population of 8,537,673 people.</p>
		<a href="https://www.nycgo.com/" class="card-link">Visit NYC</a>
		<a href="https://goo.gl/maps/2wv6gSUC3p72" class="card-link">Directions</a>
	</div>
</div>
```

![](https://github.com/MaxShalom/BootstrapX/blob/master/docs/Component%20Example%20Pictures/card-links.png?raw=true)

### Image as Card Background
```html
<div class="card bg-dark text-white">
	<img class="card-img" src="https://raw.githubusercontent.com/MaxShalom/BootstrapX/master/Components/assets/gradient.png" alt="Card image">
	<div class="card-img-overlay">
		<h5 class="card-title">Portland, OR</h5>
		<p class="card-text">Portland is the largest city in the U.S. state of Oregon and the seat of Multnomah County. The population is 639,863 people.</p>
		<p class="card-text">Last updated January 1, 2018</p>
	</div>
</div>
```

![](https://github.com/MaxShalom/BootstrapX/blob/master/docs/Component%20Example%20Pictures/card-img-back.png?raw=true)

### Colored Cards
```html
<div class="card text-white bg-warning mb-3" style="max-width: 18rem;">
	<div class="card-header">Colors</div>
      	<div class="card-body">
		<h5 class="card-title">Yellow</h5>
		<p class="card-text">Yellow is a color made from a mixture of green and blue.</p>
	</div>
</div>
```

![](https://github.com/MaxShalom/BootstrapX/blob/master/docs/Component%20Example%20Pictures/colored-cards.png?raw=true)

### Colored Outline Cards
```html
<div class="card border-primary mb-3" style="max-width: 18rem;">
	<div class="card-header">Star Wars</div>
    	<div class="card-body text-primary">
      		<h5 class="card-title">Jedi</h5>
      		<p class="card-text">A tremor in the Force. The last time I felt it was in the presence of my old master. </p>
    	</div>
</div>
```

![](https://github.com/MaxShalom/BootstrapX/blob/master/docs/Component%20Example%20Pictures/outline-colored-cards.png?raw=true)


![](https://raw.githubusercontent.com/MaxShalom/BootstrapX/master/docs/Component%20Example%20Pictures/Logos/word-logo.png)

