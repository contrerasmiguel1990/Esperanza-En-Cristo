# Esperanza-En-Cristo


# Dev Portfolio

This is a devotional website created to encourage women in walk with Christ. Bible devotionals are posted in which We discuss scripture and God's call to love Him and Love others

## Features

* Fully responsive


## Contents

- [Structure]
    - [Header Section](#header-section)
    - [Lead Section](#lead-section)
    - [About Section](#about-section)
    - [Experience Section](#experience-section)
    - [Education Section](#education-section)
    - [Projects Section](#projects-section)
    - [Skills Section](#skills-section)
    - [Contact Section](#contact-section)
    - [Footer Section](#footer-section)



### Header Section

The header section includes a basic "Nav Bar" with navigation links to HOME, VIDEOS, RESOURCES, ABOUT AND CONTACT US.

### Hamburger button

The hamburger button uses JavaScript and opens an overlay. The overlay opens when the hamburger button is clicked and closes when the "x" button is clicked.

```JavaScript
/* Open when someone clicks on the span element */
function openNav() {
    document.getElementById("myNav").style.width = "100%";
}

/* Close when someone clicks on the "x" symbol inside the overlay */
function closeNav() {
    document.getElementById("myNav").style.width = "0%";
}
```

### Lead Section

The lead section has link titled "Siguenos" which takes you to the FACEBOOK page.

### About Section
About section is currently blank.



### Carousel

The carousel features three images and uses no JavaScript.




### VIDEOS

The Videos section includes embeded videos from Facebook that are decorated with box-shadow as all other divs. It is also responsive.

### RESOURCES
The resources page contains three sections that address three very important questions. "Who is Jesus?". "What is the Gospel?". "Who is the Church?".

### Contact Section

The contact form is very basic and includes the following form.

  ```html
  <div class="container-float">
  <form id="contact" action="" method="post">
    <h3>Contactanos</h3>
    <h4>Nos gustaria escuchar de ti!</h4>
    <fieldset>
      <input placeholder="Your name" type="text" tabindex="1" required autofocus>
    </fieldset>
    <fieldset>
      <input placeholder="Your Email Address" type="email" tabindex="2" required>
    </fieldset>
    <fieldset>
      <input placeholder="Your Phone Number (optional)" type="tel" tabindex="3" required>
    </fieldset>
    <fieldset>
      <textarea placeholder="Type your message here...." tabindex="5" required></textarea>
    </fieldset>
    <fieldset>
      <button name="submit" type="submit" id="contact-submit" data-submit="...Sending">Submit</button>
    </fieldset>
    <p class="copyright">Diseñado por <a href="" target="_blank" title="Colorlib">JM</a></p>
  </form>
</div>
```

### Footer Section
