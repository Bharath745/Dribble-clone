# Dribble-clone

## Description:
This project is a recreation of a Dribbble-like layout using HTML and CSS. It features a responsive grid layout displaying design shots with images, titles, and metadata such as views, comments, and likes. The page includes a header with navigation links, a search bar, and filter options. FontAwesome is used for icons. This project provides a clean and organized way to present design work, emulating the visual style of Dribbble.

### Program:
### HTML:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Layout</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">Dribbble</div>
            <ul>
                <li><a href="#">Shots</a></li>
                <li><a href="#">Designers</a></li>
                <li><a href="#">Teams</a></li>
                <li><a href="#">Community</a></li>
                <li><a href="#">Jobs</a></li>
            </ul>
            <div class="auth-buttons">
                <p>Sign up</p>
                <p>Sign in</p>
                <input type="text" placeholder="Search">
            </div>
        </nav>

    </header>
    <main>
        <div class="title-bar">
            <h1><span>What are you working on?</span> Dribbble is show and tell for designers.</h1>
            <button>Learn more</button>
            
        </div>
        <div class="filter-bar">
            <ul>
                <li><a href="#">Popular</a></li>
                <li><a href="#">Shots</a></li>
                <li><a href="#">Now</a></li>
            </ul>
        </div>
        <div class="grid-container">
            <!-- Grid Items -->
            <div class="grid-item">
                <img src="https://cdn.dribbble.com/userupload/15335495/file/original-def6377680e7a05cbce5920b2755c231.png?crop=43x76-1579x1228&resize=450x338&vertical=center" alt="Item 1">
                <div class="info">
                    <span>Famous</span>
                    <div class="stats">
                        
                        <i class="fa fa-eye"></i> <span>4,044</span> 
                        <i class="fa fa-comment"></i> <span>14</span> 
                        <i class="fa fa-heart"></i> <span>290</span> 
                    </div>
                </div>   
            </div>

            <div class="grid-item">
                <img src="https://cdn.dribbble.com/userupload/15337098/file/original-74a7449abc4cce331c6a84e383c889d4.png?resize=450x338&vertical=center" alt="Item 2">
                <div class="info">
                    <span>Webflow</span>
                    <div class="stats">
                        <i class="fa fa-eye"></i><span>2,404</span>
                        <i class="fa fa-comment"></i> <span>13</span>
                        <i class="fa fa-heart"></i><span>236</span>
                    </div>
                </div>
                
            </div>
            <div class="grid-item">
                <img src="https://cdn.dribbble.com/userupload/15265336/file/original-c27f3f00a6d34ad52dc982823844783d.jpg?resize=400x300&vertical=center" alt="Item 1">
                <div class="info">
                    <span>MUTI</span>
                    <div class="stats">
                         <i class="fa fa-eye"></i> <span>4,044</span>
                         <i class="fa fa-comment"></i> <span>14</span>
                         <i class="fa fa-heart"></i> <span>290</span>
                    </div>
                </div>
            </div>
            <div class="grid-item">
                <img src="https://cdn.dribbble.com/userupload/15370344/file/original-fbe2599e970ece6e96fc79fcfe8cdc28.jpg?resize=450x338&vertical=center" alt="Item 2">
                <div class="info">
                    <span>Ben Didier</span>
                    <div class="stats">
                        <i class="fa fa-eye"></i> <span>2,404</span>
                        <i class="fa fa-comment"></i> <span>13</span>
                        <i class="fa fa-heart"></i> <span>236</span> 
                    </div>
                </div>
            </div>
            <div class="grid-item">
                <img src="https://cdn.dribbble.com/userupload/15325615/file/original-d3f5d6e5abb6ca89db0b1b627e249ddf.png?resize=450x338&vertical=center" alt="Item 1">
                <div class="info">
                    <span>Geek Arts</span>
                    <div class="stats">
                        <i class="fa fa-eye"></i> <span>4,044</span> 
                        <i class="fa fa-comment"></i> <span>14</span>
                        <i class="fa fa-heart"></i> <span>290</span>
                    </div>
                </div>
            </div>
            <div class="grid-item">
                <img src="https://cdn.dribbble.com/userupload/15378478/file/original-a0a606d3852598f9700ae9f3eb3a77f1.jpg?resize=400x300&vertical=center" alt="Item 2">
                <div class="info">
                    <span>Balkan Brothers</span>
                    <div class="stats">
                        <i class="fa fa-eye"></i> <span>2,404</span> 
                        <i class="fa fa-comment"></i> <span>13</span> 
                        <i class="fa fa-heart"></i> <span>236</span> 
                    </div>
                </div>
            </div>
            <div class="grid-item">
                <img src="https://cdn.dribbble.com/userupload/15320424/file/original-4113b0acd56020c583ce32f0a00652ca.jpg?crop=221x463-2079x1857&resize=400x300&vertical=center" alt="Item 1">
                <div class="info">
                    <span>Famous</span>
                    <div class="stats">
                        <i class="fa fa-eye"></i> <span>4,044</span> 
                        <i class="fa fa-comment"></i> <span>14</span> 
                        <i class="fa fa-heart"></i> <span>290</span> 
                    </div>
                </div>
            </div>
            <div class="grid-item">
                <img src="https://cdn.dribbble.com/userupload/15335470/file/original-ae1d0c718e3bce525f98e323441474d7.jpg?resize=400x300&vertical=center" alt="Item 2">
                <div class="info">
                    <span>Balkan Brothers</span>
                    <div class="stats">
                        <i class="fa fa-eye"></i> <span>2,404</span> 
                        <i class="fa fa-comment"></i> <span>13</span> 
                        <i class="fa fa-heart"></i> <span>236</span>
                    </div>
                </div>
            </div>
            <div class="grid-item">
                <img src="https://cdn.dribbble.com/userupload/15276180/file/original-9c6822b6c20c06a586a0072d56ba4ed1.jpg?crop=0x137-1889x1554&resize=400x300&vertical=center" alt="Item 1">
                <div class="info">
                    <span>Famous</span>
                    <div class="stats">
                        <i class="fa fa-eye"></i> <span>4,044</span> 
                        <i class="fa fa-comment"></i> <span>14</span> 
                        <i class="fa fa-heart"></i> <span>290</span> 
                    </div>
                </div>
            </div>
            <div class="grid-item">
                <img src="https://cdn.dribbble.com/userupload/15319114/file/original-570ff1cd44ef1451e66e377fa52aab66.jpg?resize=450x338&vertical=center" alt="Item 2">
                <div class="info">
                    <span>Balkan Brothers</span>
                    <div class="stats">
                        <i class="fa fa-eye"></i> <span>2,404</span> 
                        <i class="fa fa-comment"></i> <span>13</span> 
                        <i class="fa fa-heart"></i> <span>236</span>
                    </div>
                </div>
            </div>
            <div class="grid-item">
                <img src="https://cdn.dribbble.com/userupload/15318577/file/original-61d9475c209eabb84c581e1934879cf2.jpg?resize=400x300&vertical=center" alt="Item 1">
                <div class="info">
                    <span>Famous</span>
                    <div class="stats">
                        <i class="fa fa-eye"></i> <span>4,044</span> 
                        <i class="fa fa-comment"></i> <span>14</span> 
                        <i class="fa fa-heart"></i> <span>290</span> 
                    </div>
                </div>
            </div>
            <div class="grid-item">
                <img src="https://cdn.dribbble.com/userupload/15292209/file/still-6273f93ed581484d34fec1a438671c9c.png?resize=400x300&vertical=center" alt="Item 2">
                <div class="info">
                    <span>Balkan Brothers</span>
                    <div class="stats">
                        <i class="fa fa-eye"></i> <span>2,404</span> 
                        <i class="fa fa-comment"></i> <span>13</span> 
                        <i class="fa fa-heart"></i> <span>236</span>
                    </div>
                </div>
            </div>
            <div class="grid-item">
                <img src="https://cdn.dribbble.com/userupload/15347993/file/original-fbdb2345c706a6e30d97e66853bde721.png?resize=400x300&vertical=center" alt="Item 1">
                <div class="info">
                    <span>Famous</span>
                    <div class="stats">
                        <i class="fa fa-eye"></i> <span>4,044</span> 
                        <i class="fa fa-comment"></i> <span>14</span> 
                        <i class="fa fa-heart"></i> <span>290</span> 
                    </div>
                </div>
            </div>
            <div class="grid-item">
                <img src="https://cdn.dribbble.com/userupload/15274150/file/original-e7465f315905dce71bda50342d1885d0.jpg?resize=400x300&vertical=center" alt="Item 2">
                <div class="info">
                    <span>Balkan Brothers</span>
                    <div class="stats">
                        <i class="fa fa-eye"></i> <span>2,404</span> 
                        <i class="fa fa-comment"></i> <span>13</span> 
                        <i class="fa fa-heart"></i> <span>236</span>
                    </div>
                </div>
            </div>
            <div class="grid-item">
                <img src="https://cdn.dribbble.com/userupload/15322610/file/original-988c074c1ad4120a9c50a5b8f82d9043.jpg?resize=400x300&vertical=center" alt="Item 1">
                <div class="info">
                    <span>Famous</span>
                    <div class="stats">
                        <i class="fa fa-eye"></i> <span>4,044</span> 
                        <i class="fa fa-comment"></i> <span>14</span> 
                        <i class="fa fa-heart"></i> <span>290</span> 
                    </div>
                </div>
            </div>
            <div class="grid-item">
                <img src="https://cdn.dribbble.com/userupload/15321451/file/original-7c57148c4ebe9f3a4f629082c4a1a380.jpg?resize=400x300&vertical=center" alt="Item 2">
                <div class="info">
                    <span>Balkan Brothers</span>
                    <div class="stats">
                        <i class="fa fa-eye"></i> <span>2,404</span> 
                        <i class="fa fa-comment"></i> <span>13</span> 
                        <i class="fa fa-heart"></i> <span>236</span>
                    </div>
                </div>
            </div>
            <!-- Repeat for other items -->
        </div>
    </main>
</body>
</html>

```

### CSS:

```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 10px;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul {
    list-style-type: none;
    display: flex;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin-right: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.auth-buttons p {
    color: grey;
    padding: 5px 10px;
    display: inline;
    margin-left: 10px;
    cursor: pointer;
}
.auth-buttons input {
 border-radius: 5px;
 border: none;
 font-size: 16px;
 padding: 5px;
}

.search-bar {
    margin-top: 10px;
    display: flex;
    justify-content: right;
}


.title-bar {
    text-align: center;
    padding-top: 10px;
    background-color: #555;
    padding-bottom: 10px;
}

.title-bar h1 span {
    color: #f8f6f6;
}

.title-bar button {
    text-align: center;
    padding: 10px;
    border: none;
    border-radius: 5px;
    background-color: #848282;
}

.filter-bar {
    text-align: center;
    margin-bottom: 20px;
}

.filter-bar ul {
    list-style-type: none;
    padding: 0;
}

.filter-bar ul li {
    display: inline;
    margin-right: 20px;
}

.filter-bar ul li a {
    text-decoration: none;
    color: #333;
}

.grid-container {
    display: grid;
    grid-template-columns: repeat(6, 1fr);
    gap: 20px;
    padding: 20px;
}

.grid-item {
    background-color: #f4f4f4;
    border: 1px solid #ddd;
    padding: 10px;
    text-align: center;
}

.grid-item img {
    max-width: 100%;
    height: auto;
}

.grid-item .info {
    margin-top: 10px;
    text-align: left;
}

.grid-item .info span {
    display: block;
    font-weight: bold;
}

.grid-item .stats {
    display: flex;
    justify-content: space-between;
    margin-top: 5px;
}

.grid-item .stats span {
    display: flex;
    align-items: center;
}

.grid-item .stats i {
    margin-left: 5px;
    color: #555;
}
```

## Output:
![image](https://github.com/Bharath745/Dribble-clone/assets/94508354/cb1862bc-bafd-4e30-94db-e0bcf9d18520)

