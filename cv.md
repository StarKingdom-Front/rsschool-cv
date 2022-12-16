## [rsschool-cv](https://github.com/StarKingdom-Front)

** 

# Gladushuk Aleksey

** 

## Contacts

* Location: Gomel, Belarus;
* Phone: +375 44 531-48-29;
* Email: glinkirk@gmail.com;
* GitHub: StarKingdom-Front.

** 

## About Me

I work in the SEO team. I am looking for a new way to gain knowledge, experience and earnings. For this purpose, I learned HTML, CSS & JS to try something new.

** 

## Skills

* HTML
* CSS/SASS;
* JavaScript;
* Figma
* jQuery
* Bootstrap
* Git

** 

## Code Example

function hideTabContent() {
    
    tabsContent.forEach(item => {
        item.classList.add('hide');
        item.classList.remove('show', 'fade');
    });

    tabs.forEach(item => {
        item.classList.remove('tabheader__item_active');
    });
}

function showTabContent(i = 0) {
    tabsContent[i].classList.add('show', 'fade');
    tabsContent[i].classList.remove('hide');
    tabs[i].classList.add('tabheader__item_active');
}

hideTabContent();
showTabContent();

tabsParent.addEventListener('click', function(event) {
    const target = event.target;
    if(target && target.classList.contains('tabheader__item')) {
        tabs.forEach((item, i) => {
            if (target == item) {
                hideTabContent();
                showTabContent(i);
            }
        });
    }
});
** 
## Experience

Education
University: Belarusian State University of Transport;
Courses:
IT ACADEMY: HTML, CSS & JS.

* 

## English
A2