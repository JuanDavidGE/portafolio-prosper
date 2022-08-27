<template>
    <div class="right_Side">
            <div class="about">
                <h2 class="title2">Profile</h2>
                <p>I have potential attitudes in front-end development and in turn I
                    perform with excellent skills in backend development. My interest in the
                    development of new technologies is very high. The taste for solving problems
                    with new technologies, leads me to carry out unimaginable ideas before any
                    audience.
                </p>
            </div>
            <div class="about">
                <h2 class="title2">Experience</h2>
                <div class="box">
                    <div class="year_company">
                        <h5>2020 - 2021</h5>
                        <h5>CINOC</h5>
                    </div>
                    <div class="text">
                        <h4>Senior Developer C#</h4>
                        <p>I worked as a student of the Professional
                            Technique in support and operation
                            of computer systems, showing excellent
                            skills in the development of the C# language.
                            In this way solving in a professional way the practices
                            proposed by the institution.</p>
                    </div>
                </div>

                <div class="box">
                    <div class="year_company">
                        <h5>2022</h5>
                        <h5>ProsperCity</h5>
                    </div>
                    <div class="text">
                        <h4>Web Developer</h4>
                        <p>In the process of educating the routes in Platzi
                            sponsored by ProsperCity and the
                            support of tutors, they further enriched my
                            knowledge and motivation for front-end
                            development. In this way I further strengthen
                            my skills in the languages of html,
                            css and JavaScript.</p>
                    </div>
                </div>
            </div>

            <div class="about skills">
                <h2 class="title2">Professional skills</h2>
                <div class="box">
                    <h4>html</h4>
                    <div class="percent">
                        <div style="width: 60%;"></div>
                    </div>
                </div>
                <div class="box">
                    <h4>CSS</h4>
                    <div class="percent">
                        <div style="width: 60%;"></div>
                    </div>
                </div>
                <div class="box">
                    <h4>JavaScript</h4>
                    <div class="percent">
                        <div style="width: 30%;"></div>
                    </div>
                </div>
                <div class="box">
                    <h4>C#</h4>
                    <div class="percent">
                        <div style="width: 70%;"></div>
                    </div>
                </div>
                <div class="box">
                    <h4>Java</h4>
                    <div class="percent">
                        <div style="width: 30%;"></div>
                    </div>
                </div>
            </div>
            <div class="about interest">
                <h2 class="title2">Interest</h2>
                <ul>
                    <li><fa class="faa" icon="fa-solid fa-gamepad" />Gaming</li>
                    <li><fa class="faa" icon="fa-solid fa-microphone" />Singing</li>
                    <li><fa class="faa" icon="fa-solid fa-book" />Reading</li>
                    <li><fa class="faa" icon="fa-solid fa-utensils" />Cooking</li>
                </ul>
            </div>
    </div>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Poppins:200,300,400,500,600,700,800,900&display=swap');
.right_Side{
    position: relative;
    background: #fff;
    padding: 40px;
}
.about{
    margin-bottom: 50px;
}
.about:last-child{
    margin-bottom: 0;
}
.title2{
    color: #003147;
    text-transform: uppercase;
    letter-spacing: 1px;
    margin-bottom: 10px;
}
p{
    color: #333;
}
.about .box{
    display: flex;
    flex-direction: row;
    margin: 20px 0;
}
.about .box .year_company{
    min-width: 150px;
}
.about .box .year_company h5{
    text-transform: uppercase;
    color: #848c90;
    font-weight: 600;
}
.about .box .text h4{
    text-transform: uppercase;
    color: #2a7da2;
    font-size: 16px;
}
.skills .box{
    position: relative;
    width: 100%;
    display: grid;
    grid-template-columns: 150px 1fr;
    justify-content: center;
    align-items: center;
}
.skills .box h4{
    text-transform: uppercase;
    color: #848c99;
    font-weight: 500;
}
.skills .box .percent{
    position: relative;
    width: 100%;
    height: 10px;
    background: #f0f0f0;
}
.skills .box .percent div{
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    background: #03a9f4;
}
.interest ul{
    display: grid;
    grid-template-columns: repeat(4,1fr);
}
.interest ul li{
    list-style: none;
    color: #333;
    font-weight: 500;
    margin: 10px 0;
}
.interest ul li .faa{
    color: #03a9f4;
    font-size: 18px;
}
</style>
