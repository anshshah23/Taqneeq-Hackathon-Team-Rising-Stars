* {
    margin: 0;
    padding: 0;
}

.logo {
    width: 15%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.logo img {
    width: 46%;
    border: 3px solid white;
    border-radius: 70px;
}

.navbar {
    display: flex;
    align-items: center;
    justify-content: center;
    position: sticky;
    top: 0;
    /* cursor: pointer; */
}

.nav-list {
    width: 100%;
    /* background-color: black; */
    display: flex;
    align-items: center;
}

.nav-list li {
    padding: 43px 97px;
    list-style: none;
    text-align: center;
    font-size: larger;
}

.nav-list li a {
    text-decoration: none;
    color: rgb(255, 255, 255);
}

.nav-list li a:hover {
    text-decoration: none;
    color: rgb(255, 0, 0);
}



#search {
    padding: 5px;
    font-size: 18px;
    border: 2px solid rgb(255, 255, 255);
    border-radius: 9px;
}


.background {
    background: rgba(0, 0, 0, 0.7)url('new background.jpg');
    background-size: cover;
    background-blend-mode: darken;

}

.firstsection {
    height: 100vh;
}

.box-main {
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    max-width: 50%;
    margin: auto;
    height: 36%;
}

.firsthalf {
    width: 80%;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.secondhalf {
    width: 30%;
    height: 57%;
}

.secondhalf img {
    width: 81%;
    border: 3px solid;
    display: block;
    border-radius: 30px;
    margin: auto;
}

.text-big {
    font-size: 39px;
}

.text-small {
    font-size: 17px;
}

.btn {
    font-size: 17px;
    border: 2px solid rgb(255, 255, 255);
    border-radius: 7px;
    margin: 11px 1px;
    padding: 3px 6px;
    background: none;
    color: white;
    cursor: pointer;
}

.btn-sm {
    padding: 5px 9px;
}
