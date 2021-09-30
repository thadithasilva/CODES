<!DOCTYPE html>

<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/png" href="Images/Yoshitha Rathnayake 11.jpg" />
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@5.15.4/css/fontawesome.min.css" integrity="sha384-jLKHWM3JRmfMU0A5x5AkjWkw/EYfGUAGagvnfryNV3F9VqM98XiIH7VBGVoxVSc7" crossorigin="anonymous">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">
    <link rel="stylesheet" type="text/CSS" href="Assets/Style.css">
    <title>YOSHITHA RATHNAYAKE</title>
</head>

<style>
    /*Background Image */
    
    #bg {
        background-image: url("https://www.ms3-inc.com/wp-content/uploads/2019/08/clement-h-95YRwf6CNw8-unsplash_Blue-1024x683.jpg");
        background-attachment: fixed;
        background-size: 100%;
        font-family: Verdana, sans-serif;
        margin: 0;
        color: white;
        -webkit-animation-name: ScreenFade;
        -webkit-animation-duration: 4s;
        animation-name: ScreenFade;
        animation-duration: 4s;
    }
    
    @-webkit-keyframes ScreenFade {
        from {
            opacity: 0
        }
        to {
            opacity: 1
        }
    }
    
    @keyframes ScreenFade {
        from {
            opacity: 0
        }
        to {
            opacity: 1
        }
    }
    
    #TargetLinks {
        color: blue;
        text-decoration: none;
        transition: 2s;
    }
    
    #TargetLinks:hover {
        color: red;
    }
    
    #AboutLink {
        color: #00FF04;
        text-decoration: none;
        border: 1px solid #00FF04;
        display: inline-block;
        letter-spacing: 2px;
        text-transform: uppercase;
        overflow: hidden;
        transition: 1s;
    }
    
    #AboutLink:hover {
        color: #111;
        background-color: #39ff14;
        box-shadow: 0 0 100px #39ff14;
        transition-delay: 0.2s;
    }
    
    #CardsSection1 {
        display: none;
        position: relative;
        right: 15%;
    }
    
    #CardsSection2 {
        display: block;
        position: relative;
        right: 15%;
    }
    
    #Cards1:hover {
        box-shadow: 0 0 50px black;
        cursor: pointer;
        transition-delay: 0.2s;
        -webkit-animation-name: ShaddowFade;
        -webkit-animation-duration: 1s;
        animation-name: ShaddowFade;
        animation-duration: 1s;
    }
    
    #Cards2:hover {
        box-shadow: 0 0 50px white;
        cursor: pointer;
        transition-delay: 0.2s;
        -webkit-animation-name: ShaddowFade1;
        -webkit-animation-duration: 1s;
        animation-name: ShaddowFade1;
        animation-duration: 1s;
    }
    
    @-webkit-keyframes ShaddowFade {
        from {
            box-shadow: 0 0 0px black;
        }
        to {
            box-shadow: 0 0 50px black;
        }
    }
    
    @keyframes ShaddowFade {
        from {
            box-shadow: 0 0 0px black;
        }
        to {
            box-shadow: 0 0 50px black;
        }
    }
    
    @-webkit-keyframes ShaddowFade1 {
        from {
            box-shadow: 0 0 0px white;
        }
        to {
            box-shadow: 0 0 50px white;
        }
    }
    
    @keyframes ShaddowFade1 {
        from {
            box-shadow: 0 0 0px white;
        }
        to {
            box-shadow: 0 0 50px white;
        }
    }
    /*Main Heading (Animation)*/
    
    .class {
        text-align: center;
        color: #34FF00;
        animation: rainbow 5s infinite;
        margin: 50px;
    }
    
    @keyframes rainbow {
        40% {
            color: #00FFE7;
        }
        50% {
            color: #00FFC6;
        }
        60% {
            color: #00FF74;
        }
        70% {
            color: #00FF04;
        }
        80% {
            color: #FBFF00;
        }
        90% {
            color: #FF0000;
        }
        100% {
            color: #FF00ED;
        }
    }
    
    .class:hover {
        text-shadow: 0 0 20px black, 0 0 22px black;
        cursor: pointer;
    }
    
    .NavigationBar {
        overflow: hidden;
        background-color: black;
        font-family: Verdana, sans-serif;
        position: fixed;
        top: 0;
        width: 100%;
        z-index: 99;
        box-shadow: 0 0 50px black;
    }
    
    .NavigationBar a {
        margin: 0;
        float: right;
        display: block;
        color: #f2f2f2;
        text-align: center;
        padding: 24px;
        text-decoration: none;
        font-size: 17px;
    }
    
    .NavigationBar a:hover {
        background-color: #737373;
        color: white;
    }
    
    .button {
        border-radius: 4px;
        border: none;
        color: #FFFFFF;
        text-align: center;
        font-size: 23px;
        padding: 16px;
        width: 350px;
        transition: all 0.5s;
        cursor: pointer;
    }
    
    .button span {
        cursor: pointer;
        display: inline-block;
        position: relative;
        transition: 0.5s;
    }
    
    .button span:after {
        content: '\00bb';
        position: absolute;
        opacity: 0;
        top: 0;
        right: -20px;
        transition: 0.5s;
    }
    
    .button:hover span {
        padding-right: 25px;
    }
    
    .button:hover span:after {
        opacity: 1;
        right: 0;
    }
    
    #yr {
        font-size: 20px;
        padding: 10px;
        margin: 5px;
    }
    
    .span2 {
        color: black;
    }
    
    html {
        scroll-behavior: smooth;
    }
    
    .Home {
        background-attachment: fixed;
    }
    
    body {
        font-family: "Lato", sans-serif;
        transition: background-color .5s;
    }
    
    .sidenav {
        height: 100%;
        width: 0;
        position: fixed;
        z-index: 99;
        top: 0;
        left: 0;
        background-color: #111;
        overflow-x: hidden;
        transition: 1s;
        padding-top: 60px;
    }
    
    .sidenav a {
        padding: 8px 8px 8px 32px;
        text-decoration: none;
        font-size: 20px;
        color: white;
        display: block;
        transition: 1s;
    }
    
    .sidenav a:hover {
        color: #686868;
    }
    
    .sidenav .closeBtn {
        position: absolute;
        top: 0;
        right: 15px;
        font-size: 36px;
        margin-left: 50px;
    }
    
    #closebutton:hover {
        color: red;
    }
    
    #main {
        transition: margin-left .5s;
        padding: 16px;
    }
    
    .sideNavSettings {
        height: 100%;
        width: 0;
        position: fixed;
        z-index: 99;
        top: 0;
        left: 0;
        background-color: #111;
        overflow-x: hidden;
        transition: 0.5s;
        padding-top: 60px;
    }
    
    .sideNavSettings a {
        text-decoration: none;
        font-size: 25px;
        color: white;
        display: block;
        transition: 0.3s;
    }
    
    .sideNavSettings .closeBtnSettings {
        position: absolute;
        top: 0;
        right: 2%;
        font-size: 40px;
        margin-left: 50px;
        color: red;
    }
    
    h3 {
        margin: 20px;
    }
    
    form {
        margin: 50px;
    }
    
    .container {
        display: block;
        position: relative;
        padding-left: 35px;
        margin-bottom: 0;
        cursor: pointer;
        font-size: 22px;
        -webkit-user-select: none;
        -moz-user-select: none;
        -ms-user-select: none;
        user-select: none;
    }
    
    .container input {
        position: absolute;
        opacity: 0;
        cursor: pointer;
    }
    
    .checkmark {
        position: absolute;
        top: 0;
        left: 0;
        height: 25px;
        width: 25px;
        background-color: #eee;
        border-radius: 50%;
    }
    
    .container:hover input~.checkmark {
        background-color: #ccc;
    }
    
    .container input:checked~.checkmark {
        background-color: #2196F3;
    }
    
    .checkmark:after {
        content: "";
        position: absolute;
        display: none;
    }
    
    .container input:checked~.checkmark:after {
        display: block;
    }
    
    .container .checkmark:after {
        top: 9px;
        left: 9px;
        width: 8px;
        height: 8px;
        border-radius: 50%;
        background: white;
    }
    
    #Setting {
        margin: 20px;
    }
    
    #ParentSection {
        background-color: black;
        width: 500%;
    }
    /*Search Button*/
    
    #search {
        background-color: green;
        padding: 6px;
        border-radius: 3px;
        margin: 18px;
    }
    
    #search:hover {
        background-color: darkgreen;
    }
    /*Neon Button*/
    
    #UpArrow1 {
        display: none;
        background-color: white;
        color: black;
        margin: 10px;
        padding: 5px;
        float: right;
        border-radius: 1px;
        z-index: 90;
        border: none;
        outline: none;
        cursor: pointer;
    }
    
    #UpArrow1:hover {
        background-color: #818181;
        color: white;
    }
    
    #UpArrow2 {
        display: none;
        background-color: black;
        color: white;
        margin: 10px;
        padding: 5px;
        float: right;
        border-radius: 2px;
        z-index: 90;
        border: none;
        outline: none;
        cursor: pointer;
    }
    
    #UpArrow2:hover {
        background-color: #3e3e3e;
        color: white;
    }
    
    .YOSHITHA {
        font-size: 25px;
        margin: 30px;
        color: blue;
    }
    
    .Big_Letters1 {
        font-size: 70px;
    }
    
    .Big_Letters2 {
        font-size: 50px;
    }
    
    #CardsCenter {
        position: relative;
        left: 29%;
    }
    
    .Btns {
        color: red;
        border: 1px solid red;
        text-decoration: none;
        padding: 10px;
        font-size: 20px;
        margin: 5px;
        transition: 1s;
        position: inherit;
        right: 10%;
    }
    
    .Btns:hover {
        color: black;
        background-color: red;
    }
    
    .Btn {
        color: red;
        border: 1px solid red;
        text-decoration: none;
        padding: 10px;
        font-size: 20px;
        margin: 5px;
        transition: 1s;
    }
    
    .Btn:hover {
        color: white;
        background-color: red;
    }
    
    #DarkThemeBtns {
        text-align: center;
    }
    
    #LightThemeBtns {
        text-align: center;
    }
    /*Mobile Responsives*/
    
    @media screen and (min-width: 1145px) {
        .mobileNavBar {
            display: inline-block;
            float: right;
        }
        .HamburgerIcon {
            display: none;
        }
    }
    
    @media screen and (max-width: 1145px) {
        .HamburgerIcon {
            font-size: 30px;
            cursor: pointer;
            display: block;
            float: right;
            margin: 8px;
        }
        .mobileNavBar {
            display: none;
        }
    }
    
    @media screen and (min-width: 1100px) {
        /*MRHead = Main Mobile Responsive*/
        .MRHead {
            display: flex;
        }
    }
    
    @media screen and (max-width: 1100px) {
        .MRHead {
            display: block;
            position: inherit;
        }
    }
    
    @media screen and (min-width: 900px) {
        /*MR1 = Mobile Responsive 1*/
        .MR1 {
            display: flex;
        }
        #ParentSection {
            width: 100%;
        }
    }
    
    @media screen and (max-width: 900px) {
        .MR1 {
            display: block;
        }
        #ParentSection {
            width: 100%;
        }
    }
    
    @media screen and (min-width: 720px) {
        #Cards1 {
            width: 200px;
            height: 100%;
        }
        #Cards2 {
            width: 200px;
            height: 100%;
        }
        #mySidenav {
            display: block;
        }
        #title1 {
            display: block;
            font-size: 40px;
            margin: 100px;
        }
        #title2 {
            display: none;
        }
        .hi {
            border-radius: 50%;
            height: 300px;
            width: 300px;
            margin: 50px;
            box-shadow: 0 0 50px black;
            cursor: pointer;
            transition: 0.3s;
        }
        .hi:hover {
            opacity: 0.8;
        }
        .iconss {
            display: block;
            margin: 100px;
        }
        .icons {
            display: none;
        }
        .marquee {
            font-size: 25px;
            margin: 30px;
        }
        #yr {
            display: none;
        }
        .button {
            display: inline-block;
        }
        #AboutLink {
            font-size: 20px;
            margin: 25px;
            padding: 20px 20px;
        }
        #Sections {
            font-size: 50px;
        }
        #Paragraphs {
            font-size: 20px;
        }
        .mySkills {
            display: block;
            font-size: 30px;
            margin: 20px;
        }
    }
    
    @media screen and (max-width: 720px) {
        #Cards1 {
            width: 150px;
            height: 300px;
        }
        #Cards2 {
            width: 150px;
            height: 300px;
        }
        #mySidenav {
            display: block;
        }
        #title1 {
            display: none;
        }
        #title2 {
            display: block;
            font-size: 30px;
            margin: 70px;
        }
        .hi {
            border-radius: 50%;
            height: 200px;
            width: 200px;
            margin: 25px;
            cursor: pointer;
            transition: 0.3s;
            box-shadow: 0 0 50px black;
        }
        .hi:hover {
            opacity: 0.8;
        }
        .iconss {
            display: none;
        }
        .icons {
            display: block;
            margin: 50px;
        }
        .marquee {
            font-size: 15px;
            margin: 15px;
        }
        #yr {
            display: inline-block;
        }
        .button {
            display: none;
        }
        #AboutLink {
            font-size: 10px;
            margin: 12.5px;
            padding: 10px 10px;
        }
        #Sections {
            font-size: 30px;
        }
        #Paragraphs {
            font-size: 15px;
        }
        .mySkills {
            display: block;
            font-size: 15px;
            margin: 10px;
        }
    }
    
    @media screen and (min-width: 800px) {
        #img {
            display: block;
        }
    }
    
    @media screen and (max-width: 800px) {
        #img {
            height: 250px;
            position: relative;
            bottom: 100%;
            left: 0%;
        }
    }
    
    @media screen and (min-width: 400px) {
        #Cards1 {
            position: inherit;
            right: 0;
        }
        #Cards2 {
            position: inherit;
            right: 0;
        }
    }
    
    @media screen and (max-width: 400px) {
        #Cards1 {
            position: inherit;
            right: 70px;
        }
        #Cards2 {
            position: inherit;
            right: 50px;
        }
    }
    
    @media screen and (min-width: 960px) {
        #UpArrow1 {
            position: fixed;
            right: 0%;
            top: 91%;
        }
        #UpArrow2 {
            position: fixed;
            right: 0%;
            top: 91%;
        }
    }
    
    @media screen and (max-width: 960px) {
        #UpArrow1 {
            position: fixed;
            right: 1%;
            top: 90%;
        }
        #UpArrow2 {
            position: fixed;
            right: 1%;
            top: 90%;
        }
        #ParentSection {
            width: 100%;
        }
    }
    
    #me {
        transition: 0.3s;
    }
    
    .modal {
        display: none;
        position: fixed;
        z-index: 1;
        padding-top: 100px;
        left: 0;
        top: 0;
        width: 100%;
        height: 100%;
        overflow: auto;
        background-color: rgb(0, 0, 0);
        background-color: rgba(0, 0, 0, 0.9);
    }
    
    .modal-content {
        display: block;
        width: 35%;
        max-width: 700px;
    }
    
    .modal-content {
        -webkit-animation-name: zoom;
        -webkit-animation-duration: 0.6s;
        animation-name: zoom;
        animation-duration: 0.6s;
    }
    
    @-webkit-keyframes zoom {
        from {
            -webkit-transform: scale(0)
        }
        to {
            -webkit-transform: scale(1)
        }
    }
    
    @keyframes zoom {
        from {
            transform: scale(0)
        }
        to {
            transform: scale(1)
        }
    }
    /* The Close Button */
    
    .close {
        position: absolute;
        top: 70px;
        right: 35px;
        color: #f1f1f1;
        font-size: 40px;
        font-weight: bold;
        transition: 0.3s;
    }
    
    .close:hover,
    .close:focus {
        color: red;
        text-decoration: none;
        cursor: pointer;
    }
    
    @media only screen and (max-width: 700px) {
        .modal-content {
            width: 50%;
            position: inherit;
            top: 35%;
            right: 25%;
        }
    }
    
    @media only screen and (min-width: 700px) {
        .modal-content {
            width: 35%;
            position: inherit;
            top: 20%;
            right: 32.5%;
        }
    }
    
    .slideUp {
        position: inherit;
        animation-name: slideUp;
        -webkit-animation-name: slideUp;
        animation-duration: 2s;
        -webkit-animation-duration: 2s;
        visibility: visible;
    }
    
    @keyframes slideUp {
        0% {
            opacity: 0;
            -webkit-transform: translateY(70%);
        }
        100% {
            opacity: 1;
            -webkit-transform: translateY(0%);
        }
    }
    
    @-webkit-keyframes slideUp {
        0% {
            opacity: 0;
            -webkit-transform: translateY(70%);
        }
        100% {
            opacity: 1;
            -webkit-transform: translateY(0%);
        }
    }
</style>
<script>
    document.getElementById("Home").style.color = "blue";
    document.getElementById("LightThemeBtns").style.display = "none";


    function openNav() {
        document.getElementById("mySidenav").style.width = "250px";
        document.body.style.backgroundColor = "rgba(0,0,0,0.4)";
        backgroundColor = "rgb(0, 0, 0)";
        backgroundColor = "rgba(0, 0, 0, 0.9)";
        document.getElementById("Navbar").style.display = "none";

    }

    function closeNav() {
        document.getElementById("mySidenav").style.width = "0";
        document.body.style.backgroundColor = "white";
        document.getElementById("Navbar").style.display = "block";
    }


    function Settings() {
        document.getElementById("mySideNavBarSettings").style.width = "100%";
        document.getElementById("Settings").style.color = "blue";
        document.getElementById("Home").style.color = "white";
        document.getElementById("AboutMe").style.color = "white";
        document.getElementById("Education").style.color = "white";
        document.getElementById("Skills").style.color = "white";
        document.getElementById("Contact").style.color = "white";
        document.getElementById("Navbar").style.display = "none";
        document.getElementById("mySidenav").style.width = "0";
        document.getElementById("Navbar").style.display = "block";
    }

    function Settings2() {
        document.getElementById("mySideNavBarSettings").style.width = "100%";
        document.getElementById("Navbar").style.display = "none";
        document.getElementById("mySidenav").style.width = "0";
        document.getElementById("Navbar").style.display = "block";
    }


    function closeNavBar() {
        document.getElementById("mySideNavBarSettings").style.width = "0";
        document.getElementById("Settings").style.color = "white";
        document.getElementById("Home").style.color = "blue";
        document.getElementById("Navbar").style.display = "block";
    }

    function Home() {
        document.getElementById("Home").style.color = "blue";
        document.getElementById("AboutMe").style.color = "white";
        document.getElementById("Education").style.color = "white";
        document.getElementById("Skills").style.color = "white";
        document.getElementById("Contact").style.color = "white";
        document.getElementById("Settings").style.color = "white";
    }



    function AboutMe() {
        document.getElementById("AboutMe").style.color = "blue";
        document.getElementById("Home").style.color = "white";
        document.getElementById("Education").style.color = "white";
        document.getElementById("Skills").style.color = "white";
        document.getElementById("Contact").style.color = "white";
        document.getElementById("Settings").style.color = "white";

    }

    function Education() {
        document.getElementById("Education").style.color = "blue";
        document.getElementById("Home").style.color = "white";
        document.getElementById("AboutMe").style.color = "white";
        document.getElementById("Skills").style.color = "white";
        document.getElementById("Contact").style.color = "white";
        document.getElementById("Settings").style.color = "white";

    }

    function Skills() {
        document.getElementById("Skills").style.color = "blue";
        document.getElementById("Home").style.color = "white";
        document.getElementById("AboutMe").style.color = "white";
        document.getElementById("Education").style.color = "white";
        document.getElementById("Contact").style.color = "white";
        document.getElementById("Settings").style.color = "white";

    }

    function Contact() {
        document.getElementById("Contact").style.color = "blue";
        document.getElementById("Home").style.color = "white";
        document.getElementById("AboutMe").style.color = "white";
        document.getElementById("Education").style.color = "white";
        document.getElementById("Skills").style.color = "white";
        document.getElementById("Settings").style.color = "white";

    }

    function Home2() {
        document.getElementById("mySidenav").style.width = "0";
        document.body.style.backgroundColor = "white";
        document.getElementById("Navbar").style.display = "block";
    }

    function AboutMe2() {
        document.getElementById("mySidenav").style.width = "0";
        document.body.style.backgroundColor = "white";
        document.getElementById("Navbar").style.display = "block";

    }

    function Education2() {
        document.getElementById("mySidenav").style.width = "0";
        document.body.style.backgroundColor = "white";
        document.getElementById("Navbar").style.display = "block";
    }

    function Skills2() {
        document.getElementById("mySidenav").style.width = "0";
        document.body.style.backgroundColor = "white";
        document.getElementById("Navbar").style.display = "block";
    }

    function Contact2() {
        document.getElementById("mySidenav").style.width = "0";
        document.body.style.backgroundColor = "white";
        document.getElementById("Navbar").style.display = "block";
    }



    function Submit() {
        alert("Your Name Submitted successfully!");
    }

    function DarkTheme() {
        document.getElementById("mySideNavBarSettings").style.backgroundColor = "black";
        document.getElementById("mySideNavBarSettings").style.color = "white";
        document.getElementById("ParentSection").style.backgroundColor = "black";
        document.getElementById("ParentSection").style.color = "white";
        document.getElementById("UpArrow1").style.display = "block";
        document.getElementById("UpArrow2").style.display = "none";
        document.getElementById("CardsSection2").style.display = "block";
        document.getElementById("CardsSection1").style.display = "none";
        document.getElementById("LightThemeBtns").style.display = "none";
        document.getElementById("DarkThemeBtns").style.display = "block";
        let UpArrow1 = document.getElementById("UpArrow1");

        window.onscroll = function() {
            scrollFunction()
        };

        function scrollFunction() {
            if (document.body.scrollTop > 425 || document.documentElement.scrollTop > 425) {
                UpArrow1.style.display = "block";
            } else {
                UpArrow1.style.display = "none";
            }
        }


        function topFunction() {
            document.body.scrollTop = 0;
            document.documentElement.scrollTop = 0;
        }
    }

    function LightTheme() {
        document.getElementById("mySideNavBarSettings").style.backgroundColor = "white";
        document.getElementById("mySideNavBarSettings").style.color = "black";
        document.getElementById("ParentSection").style.backgroundColor = "white";
        document.getElementById("ParentSection").style.color = "black";
        document.getElementById("UpArrow1").style.display = "none";
        document.getElementById("UpArrow2").style.display = "block";
        document.getElementById("CardsSection2").style.display = "none";
        document.getElementById("CardsSection1").style.display = "block";
        document.getElementById("LightThemeBtns").style.display = "block";
        document.getElementById("DarkThemeBtns").style.display = "none";
        let UpArrow2 = document.getElementById("UpArrow2");

        window.onscroll = function() {
            scrollFunction()
        };

        function scrollFunction() {
            if (document.body.scrollTop > 425 || document.documentElement.scrollTop > 425) {
                UpArrow2.style.display = "block";
            } else {
                UpArrow2.style.display = "none";
            }
        }


        function topFunction() {
            document.body.scrollTop = 0;
            document.documentElement.scrollTop = 0;
        }
    }

    let UpArrow1 = document.getElementById("UpArrow1");


    window.onscroll = function() {
        scrollFunction()
    };

    function scrollFunction() {
        if (document.body.scrollTop > 425 || document.documentElement.scrollTop > 425) {
            UpArrow1.style.display = "block";
        } else {
            UpArrow1.style.display = "none";
        }
        if (document.body.scrollTop > 450 || document.documentElement.scrollTop > 450) {
            document.getElementById("About Section").className = "slideUp";
        }

        if (document.body.scrollTop > 950 || document.documentElement.scrollTop > 950) {
            document.getElementById("Education Section").className = "slideUp";
        }
        if (document.body.scrollTop > 1350 || document.documentElement.scrollTop > 1350) {
            document.getElementById("Skills Section").className = "slideUp";
        }
        if (document.body.scrollTop > 2250 || document.documentElement.scrollTop > 2250) {
            document.getElementById("Contact Section").className = "slideUp";
        }
    }


    function topFunction() {
        document.body.scrollTop = 0;
        document.documentElement.scrollTop = 0;
    }


    function Search() {
        let Search = prompt("Enter the Name of the page you are searching.");

        if (Search == "Home") {
            alert("Opening Home Page...");
            window.open("#");
            window.close("YOSHITHA_RATHNAYAKE.html");
        } else if (Search == "About") {
            alert("Opening About Page...");
            window.open("#About Section");
            window.close("YOSHITHA_RATHNAYAKE.html");
        } else if (Search == "Education") {
            alert("Opening Education Page...");
            window.open("#Education Section");
            window.close("YOSHITHA_RATHNAYAKE.html");
        } else if (Search == "Skills") {
            alert("Opening Skills Page...");
            window.open("#Skills Section");
            window.close("YOSHITHA_RATHNAYAKE.html");
        } else if (Search == "Contact") {
            alert("Opening Contact Page...");
            window.open("#Contact Section");
            window.close("YOSHITHA_RATHNAYAKE.html");
        } else if (Search == "Settings") {
            alert("Opening Settings Page...");
            document.getElementById("mySideNavBar").style.width = "100%";
        } else {
            alert("Page not found as " + Search)
        }

    }

    function Exit() {
        alert("Thank you for watch my website. Have a nice day!");
        window.close("YOSHITHA_RATHNAYAKE.html");
    }

    function Print() {
        alert("Well done! You are printing my website");
        print();
    }


    var modal = document.getElementById("myModal");


    var img = document.getElementById("me");
    var modalImg = document.getElementById("img01");
    var captionText = document.getElementById("caption");
    img.onclick = function() {
        modal.style.display = "block";
        modalImg.src = this.src;
        captionText.innerHTML = this.alt;
    }


    var span = document.getElementsByClassName("close")[0];


    span.onclick = function() {
        modal.style.display = "none";
    }

    function myImage() {
        document.getElementsByClassName("NavigationBar").style.display = "none";
    }

    function myImageClose() {
        document.getElementsByClassName("NavigationBar").style.display = "block";
    }
</script>


<body id="bg" class="image-fluid">

    <!--First Main Section-->
    <!--Home Section-->
    <section id="Home Section">
        <!--Navigation Bar-->
        <div class="NavigationBar">
            <div class="bg-black">
                <nav class="container-fluid" id="Navbar">
                    <label class="button" id="label"><span><b><i>Yoshitha Rathnayake</i></b></span></label>
                    <label id="yr"><span><b><i><span class="span2">...</span>YOSHITHA BR</i></b></span></label>
                    <span class="HamburgerIcon" onclick="openNav()" id="HamburgerIcon">&#9776;</span>
                    <div class="mobileNavBar">
                        <a href="#" onclick="Search()" id="search">Search</a>
                        <a href="#" onclick="Settings()" id="Settings">Settings</a>
                        <a href="#Contact Section" id="Contact" onclick="Contact()">Contact</a>
                        <a href="#Skills Section" id="Skills" onclick="Skills()">Skills</a>
                        <a href="#Education Section" id="Education" onclick="Education()">Education</a>
                        <a href="#About Section" id="AboutMe" onclick="AboutMe()">About</a>
                        <a href="#" id="Home" onclick="Home()"><span class="active ">Home</span></a>
                    </div>
                </nav>
            </div>
        </div>
        <div id="mySidenav" class="sidenav">
            <a href="javascript:void(0)" class="closeBtn" id="closebutton" onclick="closeNav()">&times;</a>
            <center><label class="YOSHITHA">YOSHITHA</label></center>
            <a href="#" onclick="Home2()" id="Home">Home</a>
            <a href="#About Section" onclick="AboutMe2()" id="AboutMe">About</a>
            <a href="#Education Section" onclick="Education2()" id="Education">Education</a>
            <a href="#Skills Section" onclick="Skills2()" id="Skills">Skills</a>
            <a href="#Contact Section" onclick="Contact2()" id="Contact">Contact</a>
            <a href="#" onclick="Settings2()" id="Settings">Settings</a>
            <a href="#" onclick="Search()" id="search">Search</a>
        </div>
        <div id="mySideNavBarSettings" class="sideNavSettings">
            <a href="javascript:void(0)" class="closeBtnSettings" onclick="closeNavBar()">&times;</a>
            <center class="Setting">
                <h1>Settings</h1>
            </center>
            <h3>1. User Name</h3>
            <p id="Setting">Enter your Name here.</p>
            <form>
                <label>First name:</label>
                <input type="text" placeholder="First Name..."><br><br>
                <label>Last name:</label>
                <input type="text" placeholder="Last Name..."><br><br>
                <input type="submit" value="Submit" onclick="Submit()">
            </form>
            <div style="margin: 50px;"></div>
            <h3 id="Setting">2. Themes</h3>
            <p id="Setting">Select a color theme for my website.</p>
            <label class="container" id="Setting" onclick="DarkTheme()">Dark Theme (Default)
  <input type="radio" checked="checked" name="radio">
  <span class="checkmark"></span>
</label>
            <label class="container" id="Setting" onclick="LightTheme()">Light Theme
  <input type="radio" name="radio">
  <span class="checkmark"></span>
</label>

        </div>

        <!--Heading-->
        <div>
            <h1 class="class" id="title1">
                <center><b><i><span class="Big_Letters1">Y</span></i>OSHITHA <i><span class="Big_Letters1">B</span></i>ANDARA <i><span class="Big_Letters1">R</span></i>ATHNAYAKE</b></center>
            </h1>
            <h1 class="class" id="title2">
                <center><b><i><span class="Big_Letters2">Y</span></i>oshitha <i><span class="Big_Letters2">R</span></i>athnayake</b></center>
            </h1>
        </div>

        <!--Image-->
        <center>
            <img src="Images/YOSHITHA RATHNAYAKE 1.jpg" alt="Yoshitha Rathnayake" id="me" class="hi" onclick="myImage()">


            <!-- The Modal -->
            <div id="myModal" class="modal">
                <span class="close" onclick="myImageClose()">&times;</span>
                <img class="modal-content" id="img01">
            </div>
        </center>
        <center>
            <a href="#About Section" id="AboutLink">About Me</a>
        </center>

        <div id="myModal" class="modal">
            <span class="close">&times;</span>
            <img class="modal-content" id="img01">
        </div>

        <!--Follow Us-->
        <center class="iconss">
            <a href=" https://chat.whatsapp.com/KRqihLP7J7HEpM2dL6Zwt9 " target="_blank "><img src="https://img.icons8.com/color/48/000000/whatsapp--v1.png " alt="Whatsapp Icon " /></a>
            <a href="https://t.me/joinchat/hP-WbTXCf185YTg1 " target="_blank "><img src="https://img.icons8.com/color/48/000000/telegram-app--v1.png " alt="Telegram Icon " /></a>
            <a href="https://github.com/YoshithaRathnayake " target="_blank "><img src="https://img.icons8.com/fluency/48/000000/github.png " alt="GitHub Icon " /></a>
            <a href="https://twitter.com/YoshithaSenesh " target="_blank "> <img src="https://img.icons8.com/color/48/000000/twitter-circled--v1.png " alt="Twitter Icon " /></a>
            <a href="https://www.instagram.com/yoshitha_rathnayake/ " target="_blank "><img src="https://img.icons8.com/color/48/000000/instagram-new.png " alt="Instagram Icon " /></a>
            <a href="https://mail.google.com/mail/u/0/?fs=1&to=rmysbrathnayake@gmail.com&tf=cm " target="_blank "><img src="https://img.icons8.com/color/48/fa314a/gmail-new.png " alt="Gmail Icon " /></a>
        </center>
        <center class="icons">
            <a href=" https://chat.whatsapp.com/KRqihLP7J7HEpM2dL6Zwt9 " target="_blank "><img src="https://img.icons8.com/color/23/000000/whatsapp--v1.png " alt="Whatsapp Icon " /></a>
            <a href="https://t.me/joinchat/hP-WbTXCf185YTg1 " target="_blank "><img src="https://img.icons8.com/color/23/000000/telegram-app--v1.png " alt="Telegram Icon " /></a>
            <a href="https://github.com/YoshithaRathnayake " target="_blank "><img src="https://img.icons8.com/fluency/23/000000/github.png " alt="GitHub Icon " /></a>
            <a href="https://twitter.com/YoshithaSenesh " target="_blank "> <img src="https://img.icons8.com/color/23/000000/twitter-circled--v1.png " alt="Twitter Icon " /></a>
            <a href="https://www.instagram.com/yoshitha_rathnayake/ " target="_blank "><img src="https://img.icons8.com/color/23/000000/instagram-new.png " alt="Instagram Icon " /></a>
            <a href="https://mail.google.com/mail/u/0/?fs=1&to=rmysbrathnayake@gmail.com&tf=cm " target="_blank "><img src="https://img.icons8.com/color/23/fa314a/gmail-new.png " alt="Gmail Icon " /></a>
        </center>
    </section>



    <a href="#" id="UpArrow1" onclick="UpArrow1()" class="image-fluid"><b><svg xmlns="http://www.w3.org/2000/svg " x="0px " y="0px "
width="30 " height="30 "
viewBox="0 0 172 172 "
><g fill="none " fill-rule="nonzero " stroke="none " stroke-width="1 " stroke-linecap="butt " stroke-linejoin="miter " stroke-miterlimit="10 " stroke-dasharray=" " stroke-dashoffset="0 " font-family="none " font-weight="none " font-size="none
                " text-anchor="none " style="mix-blend-mode: normal "><path d="M0,172v-172h172v172z " ></path><g fill="black "><path d="M154.8,103.2v11.46667c0,2.21307 -1.27853,4.2312 -3.27947,5.18293c-2.00093,0.95173 -4.3688,0.65933 -6.0888,-0.74533l-59.43173,-48.63013l-59.43747,48.63013c-1.71427,1.40467
                -4.08213,1.69133 -6.0888,0.74533c-2.00667,-0.946 -3.27373,-2.96987 -3.27373,-5.18293v-11.46667c0,-1.72 0.774,-3.34827 2.10413,-4.4376l63.06667,-51.6c2.1156,-1.72573 5.14853,-1.72573 7.26413,0l63.06667,51.6c1.3244,1.08933 2.0984,2.7176 2.0984,4.4376z "></path></g></g></svg></a>

    <a href="# " id="UpArrow2" onclick="UpArrow2()" class="image-fluid"><b><svg xmlns="http://www.w3.org/2000/svg " x="0px " y="0px "
width="30 " height="30 "
viewBox="0 0 172 172 "
><g fill="none " fill-rule="nonzero " stroke="none " stroke-width="1 " stroke-linecap="butt " stroke-linejoin="miter " stroke-miterlimit="10 " stroke-dasharray=" " stroke-dashoffset="0 " font-family="none " font-weight="none " font-size="none
                " text-anchor="none " style="mix-blend-mode: normal "><path d="M0,172v-172h172v172z "></path><g fill="white "><path d="M154.8,103.2v11.46667c0,2.21307 -1.27853,4.2312 -3.27947,5.18293c-2.00093,0.95173 -4.3688,0.65933 -6.0888,-0.74533l-59.43173,-48.63013l-59.43747,48.63013c-1.71427,1.40467
                -4.08213,1.69133 -6.0888,0.74533c-2.00667,-0.946 -3.27373,-2.96987 -3.27373,-5.18293v-11.46667c0,-1.72 0.774,-3.34827 2.10413,-4.4376l63.06667,-51.6c2.1156,-1.72573 5.14853,-1.72573 7.26413,0l63.06667,51.6c1.3244,1.08933 2.0984,2.7176 2.0984,4.4376z "></path></g></g></svg></a>




    <!--Second Main Section-->
    <section id="ParentSection">
        <!--About Section-->
        <section id="About Section" style="margin: 100px;">
            <section class="container p-4">
                <section class="d-sm-block">
                    <h1 class="p-4 text-center" id="Sections">About Me</h1>
                    <section class="d-sm-block">
                        <p class="lead p-5" id="Paragraphs">
                            Hi, I am <a href="http://yoshitha.com/ " target="_blank " id="TargetLinks"><b><i>Yoshitha Rathnayake.</i></b></a> I am a student and I am 13 years old. I live in Kandy in Sri Lanka. I am studing in <b><i><a href="https://www.sack.edu.lk/about_us.html
                " target="_blank " id="TargetLinks">St.Anthony's College Kandy.</a></i></b>Now, I am in Grade 8-D in my school. This is my First Web Site. My favourite subject is ICT. I like to eat Rice and Curry and I like to drink Milk. My mother's
                            name is Sudeshika Manthilake and my father's name is Athula Rathnayake. I hope to be a Computer Engineer in the future.
                        </p>
                    </section>
                </section>
            </section>
        </section>

        <!--Education Section-->
        <section id="Education Section" style="margin: 100px;">
            <div class="d-sm-block">
                <h1 class="p-4 text-center" id="Sections">Education</h1>
                <div class="d-sm-block">
                    <p class="lead p-5" id="Paragraphs">
                        Grade 5 Scholarship Exam - 170 marks (Pass).<br><br>G.C.E. Ordinary Level Exam - Not done yet.<br><br>G.C.E Advance Level Exam - Not done yet.
                    </p>
                </div>
            </div>
        </section>



        <!--Skills Section-->
        <section id="Skills Section" style="margin: 100px;">
            <div class="p-4">
                <h1 class="text-center" id="Sections">Skills</h1>
                <p class="lead p-5" id="Paragraphs">
                    Certificates - 20 certificates.<br><br>Medals - 1 Gold Medal.<br><br>My Other Creations -
                    <center>
                        <a href="Quiz.html" id="TargetLinks" target="_blank " class="mySkills"><b><i>Quiz</i></b></a>
                        <a href="Calculator.html" id="TargetLinks" target="_blank" class="mySkills"><b><i>Calculator</i></b></a>
                        <a href="Buttons.html" id="TargetLinks" target="_blank " class="mySkills"><b><i>Buttons</i></b></a>
                        <a href="Video.html" id="TargetLinks" target="_blank " class="mySkills"><b><i>Video</i></b></a>
                    </center>
                </p>
                <!--Card Section-->
                <center id="CardsSection1" id="Animate">
                    <div class="MRHead">
                        <div class="MR1">
                            <div class="p-5 " id="CardsCenter">
                                <div class="card text-black " id="Cards1">
                                    <img src="https://th.bing.com/th/id/OIP.Cd6bd9SgH9SkUIDV-EJGbgHaHa?w=170&h=180&c=7&r=0&o=5&pid=1.7 " alt="Card Image" class="card-img-top" style="width: 100%; ">
                                    <div class="card-body">
                                        <h4 class="card-title text-uppercase "><i>Web Designing</i>
                                        </h4>
                                        <p class="card-text " style="font-size: 15px; ">HTML</p>
                                    </div>
                                </div>
                            </div>
                            <div class="p-5" id="CardsCenter">
                                <div class="card text-black " id="Cards1">
                                    <img src="https://th.bing.com/th/id/OIP.fsUMeu3ObGHhO-KK5AwrCgAAAA?w=164&h=180&c=7&r=0&o=5&pid=1.7 " alt="Card Image " class="card-img-top " style="width: 100%; ">
                                    <div class="card-body ">
                                        <h4 class="card-title text-uppercase "><i>Web Designing</i>
                                        </h4>
                                        <p class="card-text " style="font-size: 15px; ">CSS</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="MR1">
                            <div class="p-5 " id="CardsCenter">
                                <div class="card text-black " id="Cards1">
                                    <img src="https://www.bigdatacloud.com/pub/media/wysiwyg/code_languages/js_1.png " alt="Card Image " class="card-img-top " style="width: 100%; ">
                                    <div class="card-body ">
                                        <h4 class="card-title text-uppercase "><i>Web Designing</i>
                                        </h4>
                                        <p class="card-text " style="font-size: 15px; ">JavaScript</p>
                                    </div>
                                </div>
                            </div>
                            <div class="p-5 " id="CardsCenter">
                                <div class="card text-black " id="Cards1">
                                    <img src="https://www.mirdafox.cz/img/bootstrap-web.png " alt="Card Image " class="card-img-top " style="width: 100%; ">
                                    <div class="card-body ">
                                        <h4 class="card-title text-uppercase "><i>Web Designing</i>
                                        </h4>
                                        <p class="card-text " style="font-size: 15px; ">Bootstrap</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
            </div>
            </div>
            </center>
            <center id="CardsSection2" id="Animate">
                <div class="MRHead">
                    <div class="MR1">
                        <div class="p-5 " id="CardsCenter">
                            <div class="card text-black " id="Cards2">
                                <img src="https://th.bing.com/th/id/OIP.Cd6bd9SgH9SkUIDV-EJGbgHaHa?w=170&h=180&c=7&r=0&o=5&pid=1.7 " alt="Card Image " class="card-img-top " style="width: 100%; ">
                                <div class="card-body ">
                                    <h4 class="card-title text-uppercase "><i>Web Designing</i>
                                    </h4>
                                    <p class="card-text " style="font-size: 15px; ">HTML</p>
                                </div>
                            </div>
                        </div>
                        <div class="p-5" id="CardsCenter">
                            <div class="card text-black " id="Cards2">
                                <img src="https://th.bing.com/th/id/OIP.fsUMeu3ObGHhO-KK5AwrCgAAAA?w=164&h=180&c=7&r=0&o=5&pid=1.7 " alt="Card Image " class="card-img-top " style="width: 100%; ">
                                <div class="card-body ">
                                    <h4 class="card-title text-uppercase "><i>Web Designing</i>
                                    </h4>
                                    <p class="card-text " style="font-size: 15px; ">CSS</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="MR1">
                        <div class="p-5 " id="CardsCenter">
                            <div class="card text-black " id="Cards2">
                                <img src="https://www.bigdatacloud.com/pub/media/wysiwyg/code_languages/js_1.png " alt="Card Image " class="card-img-top " style="width: 100%; ">
                                <div class="card-body ">
                                    <h4 class="card-title text-uppercase "><i>Web Designing</i>
                                    </h4>
                                    <p class="card-text " style="font-size: 15px; ">JavaScript</p>
                                </div>
                            </div>
                        </div>
                        <div class="p-5 " id="CardsCenter">
                            <div class="card text-black " id="Cards2">
                                <img src="https://www.mirdafox.cz/img/bootstrap-web.png " alt="Card Image " class="card-img-top " style="width: 100%; ">
                                <div class="card-body">
                                    <h4 class="card-title text-uppercase "><i>Web Designing</i>
                                    </h4>
                                    <p class="card-text " style="font-size: 15px; ">Bootstrap</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </center>
        </section>


        <!--Contact Section-->
        <section id="Contact Section">
            <div class="d-sm-block">
                <h1 class="text-center p-4 " id="Sections">Contact Us</h1>
                <div class="container p-4 d-sm-block ">
                    <div class="d-sm-flex ">
                        <p class="lead p-5" id="Paragraphs">Full Name: R.M.Y.S.B.Rathnayake.<br>
                            <br>Short Name: Yoshitha Rathnayake.<br>
                            <br>Phone Number:
                            <a href="https://contacts.google.com/person/c4320499841741239864 " target="_blank " id="TargetLinks"><b><i>+94767073488</i></b></a>
                            <br>
                            <br>Email:
                            <a href="https://mail.google.com/mail/u/0/?fs=1&to=rmysbrathnayake@gmail.com&tf=cm " target="_blank " id="TargetLinks"><b><i>rmysbrathnayake@gmail.com</i></b></a>
                            <br>
                            <br>Web Site:
                            <a href="http://yoshitha.com/ " target="_blank " id="TargetLinks"><b><i>www.yoshitharathnayake.lk</i></b></a><br><br>
                        </p>
                    </div>
                    <h1 class="text-center p-4 ">Follow Us</h1>
                    <center class="iconss ">
                        <a href=" https://chat.whatsapp.com/KRqihLP7J7HEpM2dL6Zwt9 " target="_blank "><img src="https://img.icons8.com/color/48/000000/whatsapp--v1.png " alt="Whatsapp Icon " /></a>
                        <a href="https://t.me/joinchat/hP-WbTXCf185YTg1 " target="_blank "><img src="https://img.icons8.com/color/48/000000/telegram-app--v1.png " alt="Telegram Icon " /></a>
                        <a href="https://github.com/YoshithaRathnayake " target="_blank "><img src="https://img.icons8.com/fluency/48/000000/github.png " alt="GitHub Icon " /></a>
                        <a href="https://twitter.com/YoshithaSenesh " target="_blank "> <img src="https://img.icons8.com/color/48/000000/twitter-circled--v1.png " alt="Twitter Icon " /></a>
                        <a href="https://www.instagram.com/yoshitha_rathnayake/ " target="_blank "><img src="https://img.icons8.com/color/48/000000/instagram-new.png " alt="Instagram Icon " /></a>
                        <a href="https://mail.google.com/mail/u/0/?fs=1&to=rmysbrathnayake@gmail.com&tf=cm " target="_blank "><img src="https://img.icons8.com/color/48/fa314a/gmail-new.png " alt="Gmail Icon " /></a>
                    </center>
                    <center class="icons ">
                        <a href=" https://chat.whatsapp.com/KRqihLP7J7HEpM2dL6Zwt9 " target="_blank "><img src="https://img.icons8.com/color/23/000000/whatsapp--v1.png " alt="Whatsapp Icon " /></a>
                        <a href="https://t.me/joinchat/hP-WbTXCf185YTg1 " target="_blank "><img src="https://img.icons8.com/color/23/000000/telegram-app--v1.png " alt="Telegram Icon " /></a>
                        <a href="https://github.com/YoshithaRathnayake " target="_blank "><img src="https://img.icons8.com/fluency/23/000000/github.png " alt="GitHub Icon " /></a>
                        <a href="https://twitter.com/YoshithaSenesh " target="_blank "> <img src="https://img.icons8.com/color/23/000000/twitter-circled--v1.png " alt="Twitter Icon " /></a>
                        <a href="https://www.instagram.com/yoshitha_rathnayake/ " target="_blank "><img src="https://img.icons8.com/color/23/000000/instagram-new.png " alt="Instagram Icon " /></a>
                        <a href="https://mail.google.com/mail/u/0/?fs=1&to=rmysbrathnayake@gmail.com&tf=cm " target="_blank "><img src="https://img.icons8.com/color/23/fa314a/gmail-new.png " alt="Gmail Icon " /></a>
                    </center>
                    <center>
                        <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="32" height="32" viewBox="0 0 172 172" style=" fill:#000000;"><g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="#ffffff"><path d="M126.13333,5.73333h-80.26667c-6.33533,0 -11.46667,5.13133 -11.46667,11.46667v137.6c0,6.33533 5.13133,11.46667 11.46667,11.46667h80.26667c6.33533,0 11.46667,-5.13133 11.46667,-11.46667v-137.6c0,-6.33533 -5.13133,-11.46667 -11.46667,-11.46667zM100.33333,11.46667c1.5824,0 2.86667,1.28427 2.86667,2.86667c0,1.5824 -1.28427,2.86667 -2.86667,2.86667c-1.5824,0 -2.86667,-1.28427 -2.86667,-2.86667c0,-1.5824 1.28427,-2.86667 2.86667,-2.86667zM77.4,11.46667h11.46667c1.5824,0 2.86667,1.28427 2.86667,2.86667c0,1.5824 -1.28427,2.86667 -2.86667,2.86667h-11.46667c-1.5824,0 -2.86667,-1.28427 -2.86667,-2.86667c0,-1.5824 1.28427,-2.86667 2.86667,-2.86667zM126.13333,154.8h-80.26667v-137.6h17.2l2.3736,2.3736c2.15,2.15 5.06827,3.35973 8.10693,3.35973h24.89987c3.03867,0 5.95693,-1.20973 8.10693,-3.35973l2.37933,-2.3736h17.2z"></path></g></g></svg>
                        <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="44" height="44" viewBox="0 0 172 172" style=" fill:#000000;"><g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="#ffffff"><path d="M164.83333,125.41667v-78.83333c0,-9.89 -8.02667,-17.91667 -17.91667,-17.91667h-121.83333c-9.89,0 -17.91667,8.02667 -17.91667,17.91667v78.83333c0,9.89 8.02667,17.91667 17.91667,17.91667h121.83333c9.89,0 17.91667,-8.02667 17.91667,-17.91667zM77.9375,129c0,-4.45767 3.60483,-8.0625 8.0625,-8.0625c4.45767,0 8.0625,3.60483 8.0625,8.0625c0,4.45767 -3.60483,8.0625 -8.0625,8.0625c-4.45767,0 -8.0625,-3.60483 -8.0625,-8.0625zM21.5,114.66667v-71.66667h129v71.66667z"></path></g></g></svg>
                        <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="44" height="44" viewBox="0 0 172 172" style=" fill:#000000;"><g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="#ffffff"><path d="M14.33333,28.66667v7.16667v93.16667h-14.33333v14.33333h172v-14.33333h-14.33333v-100.33333zM28.66667,43h114.66667v71.66667h-114.66667z"></path></g></g></svg>
                    </center>
                    <center>
                        <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="32" height="32" viewBox="0 0 172 172" style=" fill:white;"><g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="black"><path d="M126.13333,5.73333h-80.26667c-6.33533,0 -11.46667,5.13133 -11.46667,11.46667v137.6c0,6.33533 5.13133,11.46667 11.46667,11.46667h80.26667c6.33533,0 11.46667,-5.13133 11.46667,-11.46667v-137.6c0,-6.33533 -5.13133,-11.46667 -11.46667,-11.46667zM100.33333,11.46667c1.5824,0 2.86667,1.28427 2.86667,2.86667c0,1.5824 -1.28427,2.86667 -2.86667,2.86667c-1.5824,0 -2.86667,-1.28427 -2.86667,-2.86667c0,-1.5824 1.28427,-2.86667 2.86667,-2.86667zM77.4,11.46667h11.46667c1.5824,0 2.86667,1.28427 2.86667,2.86667c0,1.5824 -1.28427,2.86667 -2.86667,2.86667h-11.46667c-1.5824,0 -2.86667,-1.28427 -2.86667,-2.86667c0,-1.5824 1.28427,-2.86667 2.86667,-2.86667zM126.13333,154.8h-80.26667v-137.6h17.2l2.3736,2.3736c2.15,2.15 5.06827,3.35973 8.10693,3.35973h24.89987c3.03867,0 5.95693,-1.20973 8.10693,-3.35973l2.37933,-2.3736h17.2z"></path></g></g></svg>
                        <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="44" height="44" viewBox="0 0 172 172" style=" fill:white;"><g fill="black" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="black"><path d="M164.83333,125.41667v-78.83333c0,-9.89 -8.02667,-17.91667 -17.91667,-17.91667h-121.83333c-9.89,0 -17.91667,8.02667 -17.91667,17.91667v78.83333c0,9.89 8.02667,17.91667 17.91667,17.91667h121.83333c9.89,0 17.91667,-8.02667 17.91667,-17.91667zM77.9375,129c0,-4.45767 3.60483,-8.0625 8.0625,-8.0625c4.45767,0 8.0625,3.60483 8.0625,8.0625c0,4.45767 -3.60483,8.0625 -8.0625,8.0625c-4.45767,0 -8.0625,-3.60483 -8.0625,-8.0625zM21.5,114.66667v-71.66667h129v71.66667z"></path></g></svg>
                        <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="44" height="44" viewBox="0 0 172 172" style=" fill:white;"><g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="black"><path d="M14.33333,28.66667v7.16667v93.16667h-14.33333v14.33333h172v-14.33333h-14.33333v-100.33333zM28.66667,43h114.66667v71.66667h-114.66667z"></path></g></g></svg>
                    </center>
                    <center class="class" id="Powered">
                        <p><i>Powered by Yoshitha Rathnayake</i></p>
                    </center>
                    <div id="DarkThemeBtns">
                        <a onclick="Exit()" class="Btns">EXIT</a>
                        <a onclick="Print()" class="Btns">PRINT</a>
                    </div>
                    <div id="LightThemeBtns">
                        <a onclick="Exit()" class="Btn">EXIT</a>
                        <a onclick="Print()" class="Btn">PRINT</a>
                    </div>
                </div>
            </div>
        </section>
        <center>
            <audio width="50px" height="50px" autoplay>
            <source src="Audio/Recording.m4a" type="audio/m4a">
        </audio></center>

        <script src="Assets/JavaScript.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
</body>

</html>
