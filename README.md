# STEPER.CSS
This is a little "framework" I made for myself for my future work. 

Who knows maybe something will be out of this. 🤩

This framework is written with SASS.

# How to install?

You install this framework by simply importing **'steper.scss'** into your main style.cs

```@import "steper";```

# Current work

## Until now you have: 

- buttons
- nav-bar
- cards
- text-styles

#

### Buttons:

* ```btn```  - creates a default light colored button
* ```btn-primary``` - creates a primary colored button
* ```btn-danger``` - creates a danger colored button
* ```btn-success``` - creates a success colored button
* ```round``` - rounds out your button

#

  #### Buttons are used like this:
  
  
  ```
    <div class="btn">
      <a href="#">Default</a>
    </div>
  
    <div class="btn btn-primary">
      <a href="#">Primary</a>
    </div>
    
    <div class="btn btn-light">
      <a href="#">Light</a>
    </div>
    
    <div class="btn btn-success">
      <a href="#">Success</a>
    </div>
    
    <div class="btn btn-danger">
      <a href="#">Danger</a>
    </div>
    
    <div class="btn round">
      <a href="#">Default rounded</a>
    </div>
    
     <div class="btn round btn-primary">
      <a href="#">Primary rounded</a>
    </div>
    
    <div class="btn round btn-light">
      <a href="#">Light rounded</a>
    </div>
    
    <div class="btn round btn-success">
      <a href="#">Success rounded</a>
    </div>
    
    <div class="btn round btn-danger">
      <a href="#">Danger rounded</a>
    </div>
   ```
   #
   
   ### Nav-bar:
   
   * ```nav``` - adds the default colored navbar feature
   * ```nav-primary``` - adds the primary colored navbar feature
   * ```nav-success``` - adds the success colored navbar feature
   * ```nav-danger``` - adds the danger colored navbar feature
   * ```nav-light``` - adds the light colored navbar feature
   * ```nav-sm``` - adds the small size to the navbar
   * ```nav-m``` - adds the medium size to the navbar
   * ```nav-l``` - adds the large size to the navbar
   * ```nav-xl``` - adds the extra large size to the navbar
   * ```logo``` - adds  the Header text and puts it into place (doesn't need to be text)
   
   #
   
   #### Default navbar is used like this:
   
   ```
   <header class="nav">
      <div class="logo">
        <h1>Logo</h1>
      </div>

      <ul>
        <li><a href="#">Item #1</a></li>
        <li><a href="#">Item #2</a></li>
        <li><a href="#">Item #3</a></li>
      </ul>
    </header>
   ```
   
   #
   
   ### Cards:
   
   * ```card-body``` - adds the card body with default width and height
   * ```card-title``` - adds the cards title
   * ```card-content``` - adds the cards content section for text, etc..
   * ```card-primary``` - colors the card to primary color 
   * ```card-light``` - colors the card to light color
   * ```card-danger``` - colors the card to danger color
   * ```card-success``` - colors the card to success color 
   
   #
   
   #### Card example: 
   
   ```
   <div class="card-body card-danger">
      <div class="card-title">
        I am a title text
      </div>
      <div class="card-content">
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quibusdam,
          fugiat. Praesentium neque eius doloremque cum debitis dolore vitae,
          iusto tenetur laborum labore pariatur ipsam, sed iste officiis, omnis
          voluptate numquam. Lorem ipsum dolor sit amet consectetur adipisicing
        </p>

        <br />

        <div class="btn btn-light">
          <a href="#">Button</a>
        </div>
        <div class="btn btn-light">
          <a href="#">Button</a>
        </div>
      </div>
    </div>
    
    <div class="card-body card-success">
      <div class="card-title">
        I am a title text
      </div>
      <div class="card-content">
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quibusdam,
          fugiat. Praesentium neque eius doloremque cum debitis dolore vitae,
          iusto tenetur laborum labore pariatur ipsam, sed iste officiis, omnis
          voluptate numquam. Lorem ipsum dolor sit amet consectetur adipisicing
        </p>

        <br />

        <div class="btn btn-light">
          <a href="#">Button</a>
        </div>
      </div>
    </div>
    
    <div class="card-body card-primary">
      <div class="card-title">
        I am a title text
      </div>
      <div class="card-content">
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quibusdam,
          fugiat. Praesentium neque eius doloremque cum debitis dolore vitae,
          iusto tenetur laborum labore pariatur ipsam, sed iste officiis, omnis
          voluptate numquam. Lorem ipsum dolor sit amet consectetur adipisicing
        </p>

        <br />

        <div class="btn btn-light">
          <a href="#">Button</a>
        </div>
      </div>
    </div>
    
    <div class="card-body card-light">
      <div class="card-title">
        I am a title text
      </div>
      <div class="card-content">
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quibusdam,
          fugiat. Praesentium neque eius doloremque cum debitis dolore vitae,
          iusto tenetur laborum labore pariatur ipsam, sed iste officiis, omnis
          voluptate numquam. Lorem ipsum dolor sit amet consectetur adipisicing
        </p>

        <br />

        <div class="btn btn-primary">
          <a href="#">Button</a>
        </div>
      </div>
    </div>
   
   ```
   
   #
   
   ### Text-styles:
   
   * ```xl``` - adds the extra large size to the text
   * ```l``` - adds the large size to the text
   * ```m``` - adds the medium size to the text
   * ```sm``` - adds the small size to the text
   
   #
   
   #### Text-styles are used like this:

  ```
    <h1 class="xl">I am dummy text</h1>
    <h1 class="l">I am dummy text</h1>
    <h1 class="m">I am dummy text</h1>
    <h1 class="sm">I am dummy text</h1>
   
   ```
