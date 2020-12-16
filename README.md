# Responsive Design

This site is an example of a responsive design that ensures compatibility with large and small devices alike.  The structure and them is of a basic portfoio site intended to display a bio and multiple images, as well as provide contact abilities all in a responsive grid layout.

Using a combination Html, CSS, and Bootstrap 5.0, I was able to quickly create a rich responsive site with the built-in break points, forms, navbar, footer, and card Bootstrap elements. Minor styling and layout elements were specified in the external stylesheet but Bootstrap did much of the heavy lifting in this particular area.

---------
## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [Bootstrap 5.0](https://getbootstrap.com/)
* [Git](https://git-scm.com/)
* [GitHub](https://github.com/)

-----
## Code Snippets

**Portfolio Page Bootstrap Usage:**
```html
<main class="row">
        <!-- Gettn busy with the grids and subgrids -->
        <div class="col-md-8">
        <div class="card mt-5 mb-5">
            <div class="card-body">
            <h1 class="card-title border-bottom py-5 mb-5">Portfolio</h1>
            <!-- Gutter added -->
            <div class="row row-md-1 row-lg-2 g-4 py-5">
                <div class="col-md-11 col-lg-6">
                <section class="card mb-5">
                    <img src="https://via.placeholder.com/350x350" class="card-img-top" alt="Portfolio-Element-1">
                        
```

**Bootstrap Code Proving Flexible on Contact Page:**
```html
        <form>
            <!-- Customized email and name forms to allow for title to appear above fields -->
            <div class="form-group row px-4">
            <label for="inputName3">Name</label>
                <input type="name" class="form-control" id="inputname" placeholder="Name">
            </div>
            <div class="form-group row px-4">
            <label for="inputEmail3">Email</label>
                <input type="email" class="form-control" id="inputEmail3" placeholder="Email">
```

### Deployed Link

* [See Live Site](#)

### On GitHub

* [Repository Link](https://github.com/rbrtpublic1/Responsive-design)

### Author: *Robert Schramm*
- [LinkedIn](https://www.linkedin.com/in/robertwschramm/)
- [Link to Github](https://github.com/rbrtpublic1)

#
### About Page 400px
![400px](Screenshots/about-400px.png)
### About Page 768px
![768px](Screenshots/about-768px.png)
### About Page 992px
![992px](Screenshots/about-992px.png)

#
### Portfolio Page 400px
![400px](Screenshots/portfolio-400px.png)
### Portfolio Page 768px
![768px](Screenshots/portfolio-768px.png)
### Portfolio Page 992px
![992px](Screenshots/portfolio-992px.png)

#
### Contact Page400px
![400px](Screenshots/contact-400px.png)
### Contact Page768px
![768px](Screenshots/contact-768px.png)
### Contact Page992px
![992px](Screenshots/contact-992px.png)

## License

This project is licensed under the MIT License 

## Acknowledgments

* Thank you to [Hipster Ipsum](https://hipsum.co/)
