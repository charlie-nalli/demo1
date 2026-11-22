nav {
    height: 70px;
    display: flex;
    align-items: center;
}

section {
    height: inherit;
    display: flex;
    align-items: center;
    justify-content: center;
}

nav section:first-child {
    flex-basis: 10%;
}

nav section:nth-child(2) {
    flex-basis: 70%;
}

nav section:nth-child(3) {
    flex-basis: 20%;
}

ul {
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    width: 90%;
    list-style: none;
}


body {
    background-color: black;
    color: white;
}

a {
    color: white;
    text-decoration: none;
}
 
a:hover {
    color: gray;
}
h1{
    
}
