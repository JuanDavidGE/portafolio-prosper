<template>
    <div class="left_Side">
            <div class="profileText">
                <div class="imgBx">
                    <img alt="profile" src="../assets/Perfil.jpeg">
                </div>
                <h2>JUAN DAVID GONZALEZ ESCOBAR<br><span>Web Developer</span></h2>
            </div>

            <div class="contactInfo">
                <h3 class="title">Contact Info</h3>
                <ul>
                    <li>
                        <span class="icon"><fa icon="fa-solid fa-phone" /></span>
                        <span class="text">+57 3145042208</span>
                    </li>
                    <li>
                        <span class="icon"><fa icon="fa-regular fa-envelope" /></span>
                        <span class="text">juandavidg247@gmail.com</span>
                    </li>
                    <li>
                        <span class="icon"><fa icon="fa-brands fa-github" />
                        </span>
                        <span class="text">JuanDavidGE</span>
                    </li>
                    <li>
                        <span class="icon"><fa icon="fa-brands fa-linkedin-in" /></span>
                        <span class="text">Juan David Gonzalez</span>
                    </li>
                    <li>
                        <span class="icon"><fa icon="fa-solid fa-location-dot" />
                        </span>
                        <span class="text">Pensilvania, Caldas, Colombia</span>
                    </li>
                </ul>
            </div>

            <div class="contactInfo education">
                <h3 class="title">Education</h3>
                <ul>
                    <li>
                        <h5>2021</h5>
                        <h4>Graduate</h4>
                        <h4>Normal Superior de la Presentación</h4>
                    </li>
                    <li>
                        <h5>2020 - 2022</h5>
                        <h4>Professional technician in support and
                            operation of computer systems</h4>
                        <h4>CINOC Colegio Integrado Nacional Oriente De Caldas</h4>
                    </li>
                </ul>
            </div>

            <div class="contactInfo language">
                <h3 class="title">Languages</h3>
                <ul>
                    <li>
                        <span class="text">English</span>
                        <span class="percent">
                            <div style="width: 20%;"></div>
                        </span>
                    </li>
                    <li>
                        <span class="text">Spanish</span>
                        <span class="percent">
                            <div style="width: 99%;"></div>
                        </span>
                    </li>
                </ul>
            </div>
    </div>
</template>

<style lang="scss">

    @import url('https://fonts.googleapis.com/css?family=Poppins:200,300,400,500,600,700,800,900&display=swap');
    .left_Side{
    position: relative;
    background: #003147;
    padding: 40px;
    }
    .profileText{
        position: relative;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding-bottom: 20px;
        border-bottom: 1px solid rgba(255, 255, 255, 0.2);
    }
    .profileText .imgBx{
        position: relative;
        width: 200px;
        height: 200px;
        border-radius: 50%;
        overflow: hidden;
    }
    .profileText .imgBx img{
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        object-fit: cover;
    }
    .profileText h2{
        color: #fff;
        font-size: 1.5em;
        margin-top: 20px;
        text-transform: uppercase;
        text-align: center;
        font-weight: 600;
        line-height: 1.4em;
    }
    .profileText h2 span{
        font-size: 0.8em;
        font-weight: 300;
    }
    .contactInfo{
        padding-top: 40px;
    }
    .title{
        color: #fff;
        text-transform: uppercase;
        font-weight: 600;
        letter-spacing: 1px;
        margin-bottom: 20px;
    }
    .contactInfo ul{
        position: relative;
    }
    .contactInfo ul li{
        position: relative;
        list-style: none;
        margin: 10px 0;
        cursor: pointer;
    }
    .contactInfo ul li .icon{
        display: inline-block;
        width: 30px;
        font-size: 18px;
        color: #03a9f4;
    }
    .contactInfo ul li span{
        color: #fff;
        font-weight: 300;
    }
    .contactInfo.education li{
        margin-bottom: 15px;
    }
    .contactInfo.education h5{
        color: #03a9f4;
        font-weight: 500;
    }
    .contactInfo.education h4:nth-child(2){
        color: #fff;
        font-weight: 500;
    }
    .contactInfo.education h4{
        color: #fff;
        font-weight: 300;
    }
    .contactInfo.language .percent{
        position: relative;
        width: 100%;
        height: 6px;
        background: #081921;
        display: block;
        margin-top: 5px;
    }
    .contactInfo.language .percent div{
        position: absolute;
        top: 0;
        left: 0;
        height: 100%;
        background: #03a9f4;
    }
</style>
