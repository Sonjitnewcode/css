.menu {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 15px;
    list-style: none;
}
a {
    text-decoration: none;
    color: wheat;
    font-size: larger;
    padding: 20px;
    transition: background-color 0.5s ease, font-size 0.5s ease, border-radius 0.5s ease;
}
.a1:hover {
    border: 5px;
    background-color: rgb(192, 167, 120);
    border-radius: 15px;
    font-size: 24px;
}
.a2:hover {
    border: 5px;
    background-color: rgb(192, 167, 120);
    border-radius: 15px;
    font-size: 24px;

    
}
.a3:hover {
    border: 5px;
    background-color: rgb(192, 167, 120);
    border-radius: 15px;
    font-size: 24px;
}
body {
    background: linear-gradient(-90deg, #5c594c, #807a5c, #dcd6c1)
}

/* cssของgoogle */

.Ai {
    display: flex;
    padding-left: 150px;
    align-items: center;
}
.textgg {
    font-size: 26px;
    color: white;
    padding: 15px;
    transition: background-color 0.5s ease, font-size 0.5s ease, border-radius 0.5s ease;
}
.textgg:hover {
    font-size: 32px;
    border: 1px;
    border-radius: 15px;
    padding: 15px;
    color: transparent;
    
}
.textgg:hover::after {
    content: attr(data-hover);
    color: white;
    size: 32px;
    border: 1px solid white;
    border-radius: 15px;
    padding: 15px;
    background-color: #5c594c;
    left: 50%;
}
