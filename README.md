<h1 align="center"> Codsoft </h1> 
<hr>

<h3 align="center">Web Development </h3>
### Task no.01
# Landing page
## Code

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing for programmers</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <div class="container">
        <img align="right" src="comp.gif" class="image" height="700px">
        <div class="top-left">
            <div class="site-name">Lets Land here!</div>
            <p>Welcome to the Landing page for web developers</p>
        </div>
        <div class="t">
            <nav>
                <a href="#">Home</a>
                
                <a href="#">About</a>
                
                <a href="#">Contact Us</a>
                
                <a href="#">Support</a>
            </nav>
        </div>
        <div class="bottom-left">
            <h1>Level Up with Codsoft</h1>
            <a href="#" class="join-button">Join Now</a>
        </div>
        <div class="bottom-right">
            <p class="mail">Mail us at : contact@codsoft.in</p>
            <p>Don't miss out new offers!!</p>
        </div>
    </div>

    
</body>
</html>

```

```css
body{
    
    background-color: rgb(0, 0, 0);
    margin: 0;
    padding: 0;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
.container{
    position: relative;
    width: 100%;
    height: 100vh;
}
.container img{
    object-fit: cover;
    height: 100%;
}
.top-left,
.t,
.bottom-left,
.bottom-right {
    position: absolute;
    padding: 2rem;
    color: white;
}
.top-left{
    top:2rem;
    left:2rem;
}
.t{
    transition: transform 10s;
    top: 1.25rem;
    right:15rem;
   
    
}
.top-right a{
    display: inline;
    margin-left: 0.5rem;
    font-size: 1.125rem;
    text-decoration: none;
}

.top-right a:hover{
    transform: scale(1.5);
    color: #e357ff;
}
.bottom-left{
    bottom: 3rem;
    left: 2rem;
}

.bottom-right{
    color: #e357ff;
    bottom: 2rem;
    left: 13.5rem;
}

.site-name{
    font-size: 2.5rem;
    font-weight: bold;
    margin-bottom: 0.725rem;
}

nav a{
    color:white;
    text-decoration: none;
    margin-right: 0.725rem;
    font-size: 1.5rem;
}
.join-button{
    display: inline-block;
    background-color: #c621db;
    color: #fff;
    padding: 0.625rem 1.25rem ;
    font-size: 1.875rem;
    font-weight: bold;
    border-radius: 10px;
    text-decoration: none;
    transition: transform 10s;
    transition: background-color 0.3s ease;

}

.join-button:hover{
    cursor: pointer;
    transform: scale(0.95);
    background-color: #71077a;
}
.bottom-left h1{
    font-size: 3rem;
    font-weight: bold;
    margin-bottom: 2.5rem;

}

.bottom-left p {
    font-size: 1rem;
    margin-bottom: 3rem;
}

.bottom-right h2{
    font-size: 2.25rem;
    font-weight: bold;
    margin-bottom: 0.525rem;
}

.bottom-right .mail{
    font-size: 1.5rem;
    font-weight: bold;
    margin-bottom: 0.025rem;
}
```

### Output

![image](https://github.com/PSriVarshan/Codsoft_taskno1/assets/114944059/156b7fe6-78a5-4cee-99b4-a2c5febbbab7)




