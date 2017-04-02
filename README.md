# CssSelectors
Little email submission form that has examples of basic CSS Selectors
/* Attribute Selectors ------------- */

.form-contact{
    padding: 20px 24px;
    background: #f4f7f8;
}

#container{
    max-width: 500px;
    margin: auto;
}

input[type="email"]{
    background: #fdfee6;
}



a[target="_blank"]{
    color: #39add1;
    text-decoration: none;
    border-bottom: 1px dotted;
}

/* DRY Classes ------------- */

.br{
    border-radius: .5em;
}

.avatar{
    display: block;
    margin: 0 auto 2em;
}

.rounded{
    border-radius: 50%;
}

.btn{
    cursor: pointer;
    font-size: .875em;
    font-weight: 400;
    color: #fff;
    padding-left: 20px;
    padding-right: 20px;
    text-transform: uppercase;
}

.btn:hover{
    opacity: .75
}

.default{
    background-color: #52bab3;
}

.error{
    background-color: #ff784f;
}

@media (min-width: 769px) {
        .inln {
            width: auto;
            display: inline-block;
        }

        .btn + .btn {
            margin-left: 20px;
        }
}

/* Combinators ------------- */

form > a{
    font-size: .75em;
}

h1 ~ label{
    background: tomato;
    color: white;
    padding: 5px;
}
