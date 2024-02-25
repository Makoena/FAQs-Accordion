## Welcome! 👋
Frontend Mentor - FAQ accordion solution

# Overview

Thanks for checking out this front-end coding challenge.

[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.

# The challenge 
Users should be able to:

- Hide/Show the answer to a question when the question is clicked
- Navigate the questions and hide/show answers using keyboard navigation alone
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

# Screenshot
- https://github.com/Makoena/FAQs-Accordion/blob/main/Design%20Outcome/active-state.PNG
- https://github.com/Makoena/FAQs-Accordion/blob/main/Design%20Outcome/desktop-view.png

# Links
https://github.com/Makoena/FAQs-Accordion.git 

# Built with
- HTML5
- CSS
- JavaScript


# What I learned
- i have learned how to use div class to add icon that are align to text
- i have learnt that you can justify content to space it in between. 
- most lesson i learned was using javascript to add event to my icons 

.proud-of-this-javascript - .


 const accordionBtns =document.querySelectorAll('.accordion-btn')
accordionBtns.forEach(btn => {
    btn.addEventListener('click', function() {
        this.classList.toggle('active')
        const accordionDescription = this.nextElementSibling
        const plusIcon = this.querySelector('.plus-icon')
        const minusIcon = this.querySelector('.minus-icon')

if(accordionDescription.style.maxHeight){
            accordionDescription.style.maxHeight=null
            plusIcon.style.display='block'
            minusIcon.style.display ='none'
        }
        else {
            accordionDescription.style.maxHeight= accordionDescription.scrollHeight +
            'px'
            plusIcon.style.display='none'
            minusIcon.style.block
        }
    })
})
# Continue Development
- Javascript -  i need a thourough understand on javascript concepts and also learn more on events.
- CSS - need to learn to you different styling patterns and designs.

# Useful resources
- [WAI Accordion Example](https://www.w3.org/WAI/ARIA/apg/patterns/accordion/examples/accordion/) - I used this accordion pattern in this project.
https://www.youtube.com/watch?v=AxD9slgNDJI



#  Acknowledgments
https://www.youtube.com/watch?v=AxD9slgNDJI
https://www.youtube.com/watch?v=XgxeUCMflV4