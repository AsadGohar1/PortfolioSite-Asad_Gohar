# PortfolioSite-Asad_Gohar

/* Tablet View */
@media (min-width: 600px) {
    nav ul {
        gap: 40px;
    }

    .about, .projects, .contact {
        padding: 40px;
    }
}

/* Desktop/Laptop View */
@media (min-width: 992px) {
    nav ul {
        gap: 60px;
    }

    .projects, .contact, .about {
        max-width: 800px;
        margin: 0 auto;
    }

    footer {
        position: static;
    }
}

This CSS code demonstrates the use of **media queries** for creating responsive designs for tablet and desktop/laptop views. Media queries allow for styling specific to device sizes, ensuring that a website layout adapts properly to different screen resolutions.

Here's a proper citation for the code:

```css
/* Tablet View */
@media (min-width: 600px) {
    nav ul {
        gap: 40px;
    }

    .about, .projects, .contact {
        padding: 40px;
    }
}

/* Desktop/Laptop View */
@media (min-width: 992px) {
    nav ul {
        gap: 60px;
    }

    .projects, .contact, .about {
        max-width: 800px;
        margin: 0 auto;
    }

    footer {
        position: static;
    }
}
```

### Citation:
This responsive layout code uses media queries to adapt navigation, padding, and container width for tablet and desktop views. Found in general CSS styling documentation and responsive design best practices. [CSS Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries).
