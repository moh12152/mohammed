# mohammed
modulacs3-solution
module2-solution
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    margin: 20px;
    padding: 0;
}

h1 {
    text-align: center;
    font-size: 2em;
    margin-bottom: 20px;
}

.container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}

.section {
    border: 1px solid black;
    padding: 20px;
    margin: 10px;
    position: relative;
}

.section-title {
    position: absolute;
    top: 10px;
    right: 10px;
    background-color: yellow;
    padding: 5px;
    border: 1px solid black;
}

.chicken {
    background-color: #f8d7da;
}

.beef {
    background-color: #d1ecf1;
}

.sushi {
    background-color: #d4edda;
}
