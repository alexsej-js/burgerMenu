body {
    height: 100%;
    line-height: 1;
    font-size: 16px;
    background: #333;
    color: #000;
}
body.lock {
    overflow: hidden;
}
a {
    text-decoration: none;
}
li {
    list-style: none;
}
.wrapper {
    min-height: 100%;
    margin: 0 auto;
}
.page {
    padding: 90px 30px 0 30px;
}

/* header */
.header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 10;
    background-color: chocolate;
}
.header-container {
    max-width: 90%;
    min-height: 70px;
    margin: 0 auto;
    display: flex;
    padding: 0 30px;
    align-items: center;
    justify-content: space-between;
}
.header-logo {
    border-radius: 50%;
    width: 40px;
    height: 40px;
    background-color: #fff;
    position: relative;
    z-index: 5;
}
.menu-list > li {
    position: relative;
    margin: 0 0 0 20px;
}
.menu-link {
    font-size: 18px;
    color: #fff;
    transition: all 0.3s ease-in;
}
.menu-link:hover {
    text-decoration: underline;
}
.menu-arrow {
    display: none;
    cursor: pointer;
}
/* ------------------------------------- */

body.pc .menu-list > li:hover .menu-sub__list {
    opacity: 1;
    visibility: visible;
    transform: translate(0px 0px);
    pointer-events: all;
}
body.touch .menu-list > li {
    display: flex;
    align-items: center;
}
body.touch .menu-arrow {
    display: block;
    width: 0;
    height: 0;
    margin-left: 5px;
    border-left: 5px solid transparent;
    border-right: 5px solid transparent;
    border-top: 10px solid #fff; 
    transition: transform 0.8s ease-in-out;
}
body.touch .menu-link {
    flex: 1 1 auto;
}
body.touch .menu-list > li.active-arrow .menu-sub__list {
    opacity: 1;
    visibility: visible;
    transform: translate(0px 0px);
    pointer-events: all;
}
body.touch .menu-list > li.active-arrow .menu-arrow {
    transform: rotate(-180deg);
}
/* ------------------------------------- */
.menu-sub__list {
    display: flex;
    flex-direction: column;
    align-items: center;
    position: absolute;
    top: 100%;
    right: 0;
    background-color: #000;
    padding: 15px;
    min-width: 200px;
}
.menu-sub__list li {
    margin-bottom: 10px;
}
.menu-sub__list li:last-child {
    margin-bottom: 0;
}
.menu-sub__link {
    color: #fff;
}
.menu-icon {
    display: none;
}
@media (min-width: 767px) {
    .menu-list {
        display: flex;
        align-items: center;
    }
    .menu-list > li {
        padding:  10px 0;
    }
    .menu-sub__list > li {
        padding:  5px 0;
    }
    .menu-sub__list  {
        transform: translate(0px 10%);
        opacity: 0;
        visibility: hidden;
        pointer-events: none;
        transition: all 0.3s ease;
    }
} 

@media (max-width: 767px) {
    .menu-icon {
        display: block;
        z-index: 5;
        position: relative;
        width: 30px;
        height: 18px;
        cursor: pointer;
    }
    .menu-icon span,
    .menu-icon::after,
    .menu-icon::before {
        left: 0;
        position: absolute;
        height: 10%;
        width: 100%;
        transition: all 0.3s ease-in-out;
        background-color: #fff;
    }
    .menu-icon::after,
    .menu-icon::before {
        content: "";
    }
    .menu-icon::before {
        top: 0;
    }
    .menu-icon::after {
        bottom: 0;
    }
    .menu-icon span {
        top: 50%;
        transform: scale(1) translate(0px -50%);
    }
    .menu-icon.active span {
        width: 0;
    }
    .menu-icon.active::before {
        top: 50%;
        transform: rotate(-45deg) translate(0px, -50%);
    }
    .menu-icon.active::after {
        bottom: 50%;
        transform: rotate(45deg) translate(0px, 50%);
    }
    .menu-body {
        position: fixed;
        top: 0;
        left: -150%;
        width: 100%;
        height: 100%;
        background-color: rgba(0, 0, 0, 0.8);
        padding: 100px 30px 30px 30px;
        transition: left 0.3s ease-in-out 0s;
        overflow: auto;
    }
    .menu-body.active {
        left: 0;
    }
    .menu-body::before {
        content: '';
        position: fixed;
        width: 100%;
        height: 70px;
        top: 0;
        left: 0;
        background-color: #912105;
        z-index: 5;
    }
    .menu-list {
        width: 100%;
        align-items: flex-start;
        display: flex;
        flex-direction: column;
    }
    .menu-list > li {
        flex-wrap: wrap;
        margin-bottom: 30px;
    }
    .menu-list > li:last-child {
        margin-bottom: 0;
    }
    .menu-list > li.active-arrow .menu-sub__list {
        display: block;
    }
    .menu-link {
        font-size: 24px;
    }
    .menu-sub__list {
        position: relative;
        background-color: rgba(255, 255, 255, 0.808);
        flex: 1 1 100%;
        margin-top: 20px;
        display: none;
    }
    .menu-sub__link {
        font-size: 20px;
        color: #000;
    }
    body.touch .menu-link {
        flex: 0 0 auto;
    }
}
    










.section-page {
    padding: 30px;
    min-width: 90%;
    margin: 0 auto;
}
.section-page-1 {
    background-color: aqua;
}
.section-page-2 {
    background-color: tomato;
}
.section-page-3 {
    background-color: aquamarine;
}
.page-titel {
    font-size: 40px;
    margin: 0 0 20px 0;
}
.page-text {
    line-height: 150%;
    font-size: 16px;
}
.page-text p {
    margin: 0 0 20px 0;
}
.page-sub__titel {
    font-size: 30px;
    margin: 0 0 20px 0;
}
