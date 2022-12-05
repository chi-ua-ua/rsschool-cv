# Dmitry Kuzmin
## Contacts:
* __Discord:__ Heptor3223
* __email:__ chi-ua-ua_74@mail.ru
## About myself:
I'm beginner front-end developer from Russia, South Ural, Chelyabinsk. 
I'm got some basic skills HTML, CSS and JS and wanna continue my education in RS-School.
## Skills:
* __HTML__
* __CSS__
* __JS__ (basic)
* __Figma__
* __VSCode__
* __Git__
## Code example:
```const burgerIcon = document.querySelector('.burger-icon');
const burger = document.querySelector('.burger');
const burgerClose = document.querySelector('.burger_close');

burgerClose.addEventListener('click', function(e) {
  if (e.target.closest('.burger_close')) {
    burger.classList.toggle('burger-show');
  }
});

page.addEventListener('click', function(e) {
  if (e.target.closest('.burger-icon')) {
    burger.classList.toggle('burger-show');
  } else if (e.target != burger && !e.target.closest('.burger-list li')) {
    burger.classList.remove('burger-show');
  } 
  });```
