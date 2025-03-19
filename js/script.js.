/* 🌟 Download Press Kit Function */
function downloadPressKit() {
    alert('Your press kit is downloading...');
    window.location.href = 'assets/press_kit.zip';
}

/* 🌟 Toggle Mobile Menu */
function toggleMenu() {
    const menu = document.querySelector('nav ul');
    menu.classList.toggle('show');
}

/* 🌟 Show/Hide Media Gallery */
function toggleMediaGallery() {
    const gallery = document.getElementById('mediaGallery');
    gallery.style.display = gallery.style.display === 'none' ? 'flex' : 'none';
}

/* 🌟 Smooth Scroll for Navigation */
document.querySelectorAll('nav a').forEach(anchor => {
    anchor.addEventListener('click', function(event) {
        event.preventDefault();
        const targetId = this.getAttribute('href').substring(1);
        document.getElementById(targetId).scrollIntoView({ behavior: 'smooth' });
    });
});
