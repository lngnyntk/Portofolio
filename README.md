# Belajar bikin portofolio menggunakan html, css

## Sktruktur Web
### Header
        a Home
        a About
        a Project
        a Contact
### Home
        h1 Name
        p Status
### About
        left 
            img Profile
        right 
            h2 About Me
            p lorem50
### Project
        .box * 3
            img Image-Project
            h3 Project-1
            p lorem20
### Contact
        left
            h3 Contact
        right
            a Github
            a Youtube
            a Instagram

## img yang digunakan
    Profile
    Project
    Icon Home, About, Project, Contact, Github, Youtube, Instagram

## Font
### Poppins (dari google font,  taruh di header) 
    <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
    </style>

## Cara Penggunaan Dasar
        .poppins-regular {
    font-family: "Poppins", sans-serif;
    font-weight: 400;
    font-style: normal;
    }

## Color
    :root {
    --Background: rgb(246, 248, 213);
    --Primary: rgb(33, 133, 213);
    --Secondary: rgb(52, 140, 212);
    --Text: Black;
    }

## Clip-path
### Clip-Path for custom shape from http://bennettfeely.com/clippy/
    img {
    clip-path: polygon(50% 0%, 83% 12%, 100% 43%, 94% 78%, 68% 100%, 32% 100%, 6% 78%, 0% 43%, 17% 12%);
    }

## Icon
### Using Feather Icon from https://feathericons.com
### Cara Penggunaan:
### 1. Tulis di head
    <script src="/src/feather.js"></script> 
### 2. Tulis ditempat yang mau digunakan
    <i data-feather="github"></i>
### 3. Tulis di body
    <script>feather.replace();</script>

