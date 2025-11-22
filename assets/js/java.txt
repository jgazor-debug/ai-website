
// Fade-in elements on DOM load
document.addEventListener("DOMContentLoaded", function() {
    const fadeElems = document.querySelectorAll('.fade-in');
    fadeElems.forEach(elem => {
        elem.style.opacity = 1;
    });
});

// Highlight active navbar item
const navLinks = document.querySelectorAll('.navbar-nav .nav-link');
navLinks.forEach(link => {
    if(link.href === window.location.href){
        link.classList.add('active');
    }
});

