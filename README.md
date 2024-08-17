body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    background-color: #005CA6;
    color: white;
}

.container {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 10px;
}

.header {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.header p {
    margin: 0;
    font-size: 20px;
}

.level {
    background-color: rgba(0, 0, 0, 0.6);
    padding: 5px 10px;
    border-radius: 5px;
}

.menu-icon {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    height: 24px;
}

.menu-icon .bar {
    width: 24px;
    height: 3px;
    background-color: white;
    margin: 2px 0;
}

.main-content {
    text-align: center;
    margin-top: 20px;
}

.flag-container {
    background-color: orange;
    padding: 10px;
}

.flag {
    width: 150px;
    height: auto;
}

.buttons {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 20px;
}

.button {
    background-color: white;
    color: black;
    padding: 10px;
    margin: 5px 0;
    border: 2px solid black;
    width: 100px;
    text-align: center;
}

.switch-button {
    display: flex;
    align-items: center;
    margin: 5px 0;
}

.switch-button img {
    width: 30px;
    height: auto;
    margin-right: 5px;
}

.footer {
    display: flex;
    justify-content: space-around;
    margin-top: 20px;
    width: 100%;
    background-color: #333333;
}

.footer-icon {
    padding: 10px;
    text-align: center;
    font-size: 14px;
}

.footer-icon p {
    margin: 0;
}
