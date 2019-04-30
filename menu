document.getElementById("sidebar-burger-menu").addEventListener("click", toggleFunction);
document.getElementById("sidebar-menu-close").addEventListener("click", toggleFunction);

let menu = document.getElementById("menu");

function toggleFunction() {
    menu.classList.toggle('show-nav');
}

document.addEventListener("click", hideSideMenu);


function hideSideMenu(event) {
    let target = event.target;
    if (target.closest('#sidebar-burger-menu') !== null){
    } else if (target.closest('#menu') === null){
        menu.classList.remove('show-nav');
    } else{
        return;
    }
}

//Need to change the names of the buttons and menus/side menus etc so that they make sense. Calling a button "sidebar-burger-menu" is a kind of madness
