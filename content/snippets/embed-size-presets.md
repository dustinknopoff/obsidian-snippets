/**
A number of classes to adjust the size of embeds in Obsidian, they can be used through the pipeline syntax. Some examples:


![[note|w-10vw]] - sets the width of the embed to 10% of the viewport width
![[note|w-100px]] - sets the width of the embed to 100 pixels
![[note|h-10vh]] - sets the height of the embed to 10% of the viewport height
![[note|h-100px]] - sets the height of the embed to 100 pixels


They can be combined using spaces, for example:
![[note|w-10vw h-10vh]]
![[note|w-100px h-100px]]
![[note|w-100px h-10vh]]
![[note|w-10vw h-100px]]


An option to style the embed is available, too, through the class `styled`:
![[note|styled]]


It can be used in combination with the other classes, for example:
![[note|w-10vw h-10vh styled]]
![[note|w-100px h-100px styled]]
![[note|w-100px h-10vh styled]]
![[note|w-10vw h-100px styled]]


The following classes are available:
.h-100 .. h-2990 in steps of 10
.h-1vh .. h-199vh in steps of 1
.w-100 .. w-2990 in steps of 10
.w-1vw .. w-199vw in steps of 1


*/

/* GENERAL IMPROVEMENTS */
.internal-embed.is-loaded[alt~="styled"] {
    border: 1px solid #ccc;
    border-radius: 5px;
    margin: 20px;
}

.internal-embed.is-loaded[alt~="styled"] .markdown-embed {
    padding: 0;
    border: none;
    position: relative;
}

.internal-embed.is-loaded[alt~="styled"] .markdown-embed-title {
    position: sticky;
    top: 0;
    z-index: 1;
    width: 100%;
    padding: 10px;
    background-color: var(--background-secondary);
}

.internal-embed.is-loaded[alt~="styled"] .markdown-embed-link {
    z-index: 400;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: start;
}

.internal-embed.is-loaded[alt~="styled"] .markdown-embed-link:hover::after {
    content: "";
    position: sticky;
    top: 300px;
    right: 0;
    width: 0;
    height: 0;
    border-top: 20px solid transparent;
    border-bottom: 20px solid transparent;
    border-left: 20px solid var(--background-primary);
    z-index: 399;
}

.internal-embed.is-loaded[alt~="styled"] .markdown-embed-link svg {
    position: sticky;
    top: 0.5rem;
}

.internal-embed.is-loaded[alt~="styled"] .markdown-embed-content {
    padding: 10px;
}

/* HEIGHT OF EMBEDS */
.internal-embed.is-loaded[alt~="h-100"] {
    max-height: 100px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-110"] {
    max-height: 110px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-120"] {
    max-height: 120px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-130"] {
    max-height: 130px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-140"] {
    max-height: 140px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-150"] {
    max-height: 150px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-160"] {
    max-height: 160px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-170"] {
    max-height: 170px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-180"] {
    max-height: 180px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-190"] {
    max-height: 190px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-200"] {
    max-height: 200px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-210"] {
    max-height: 210px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-220"] {
    max-height: 220px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-230"] {
    max-height: 230px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-240"] {
    max-height: 240px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-250"] {
    max-height: 250px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-260"] {
    max-height: 260px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-270"] {
    max-height: 270px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-280"] {
    max-height: 280px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-290"] {
    max-height: 290px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-300"] {
    max-height: 300px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-310"] {
    max-height: 310px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-320"] {
    max-height: 320px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-330"] {
    max-height: 330px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-340"] {
    max-height: 340px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-350"] {
    max-height: 350px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-360"] {
    max-height: 360px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-370"] {
    max-height: 370px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-380"] {
    max-height: 380px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-390"] {
    max-height: 390px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-400"] {
    max-height: 400px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-410"] {
    max-height: 410px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-420"] {
    max-height: 420px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-430"] {
    max-height: 430px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-440"] {
    max-height: 440px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-450"] {
    max-height: 450px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-460"] {
    max-height: 460px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-470"] {
    max-height: 470px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-480"] {
    max-height: 480px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-490"] {
    max-height: 490px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-500"] {
    max-height: 500px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-510"] {
    max-height: 510px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-520"] {
    max-height: 520px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-530"] {
    max-height: 530px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-540"] {
    max-height: 540px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-550"] {
    max-height: 550px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-560"] {
    max-height: 560px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-570"] {
    max-height: 570px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-580"] {
    max-height: 580px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-590"] {
    max-height: 590px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-600"] {
    max-height: 600px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-610"] {
    max-height: 610px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-620"] {
    max-height: 620px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-630"] {
    max-height: 630px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-640"] {
    max-height: 640px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-650"] {
    max-height: 650px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-660"] {
    max-height: 660px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-670"] {
    max-height: 670px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-680"] {
    max-height: 680px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-690"] {
    max-height: 690px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-700"] {
    max-height: 700px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-710"] {
    max-height: 710px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-720"] {
    max-height: 720px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-730"] {
    max-height: 730px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-740"] {
    max-height: 740px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-750"] {
    max-height: 750px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-760"] {
    max-height: 760px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-770"] {
    max-height: 770px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-780"] {
    max-height: 780px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-790"] {
    max-height: 790px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-800"] {
    max-height: 800px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-810"] {
    max-height: 810px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-820"] {
    max-height: 820px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-830"] {
    max-height: 830px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-840"] {
    max-height: 840px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-850"] {
    max-height: 850px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-860"] {
    max-height: 860px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-870"] {
    max-height: 870px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-880"] {
    max-height: 880px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-890"] {
    max-height: 890px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-900"] {
    max-height: 900px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-910"] {
    max-height: 910px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-920"] {
    max-height: 920px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-930"] {
    max-height: 930px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-940"] {
    max-height: 940px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-950"] {
    max-height: 950px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-960"] {
    max-height: 960px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-970"] {
    max-height: 970px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-980"] {
    max-height: 980px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-990"] {
    max-height: 990px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1000"] {
    max-height: 1000px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1010"] {
    max-height: 1010px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1020"] {
    max-height: 1020px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1030"] {
    max-height: 1030px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1040"] {
    max-height: 1040px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1050"] {
    max-height: 1050px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1060"] {
    max-height: 1060px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1070"] {
    max-height: 1070px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1080"] {
    max-height: 1080px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1090"] {
    max-height: 1090px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1100"] {
    max-height: 1100px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1110"] {
    max-height: 1110px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1120"] {
    max-height: 1120px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1130"] {
    max-height: 1130px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1140"] {
    max-height: 1140px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1150"] {
    max-height: 1150px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1160"] {
    max-height: 1160px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1170"] {
    max-height: 1170px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1180"] {
    max-height: 1180px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1190"] {
    max-height: 1190px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1200"] {
    max-height: 1200px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1210"] {
    max-height: 1210px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1220"] {
    max-height: 1220px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1230"] {
    max-height: 1230px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1240"] {
    max-height: 1240px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1250"] {
    max-height: 1250px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1260"] {
    max-height: 1260px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1270"] {
    max-height: 1270px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1280"] {
    max-height: 1280px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1290"] {
    max-height: 1290px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1300"] {
    max-height: 1300px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1310"] {
    max-height: 1310px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1320"] {
    max-height: 1320px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1330"] {
    max-height: 1330px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1340"] {
    max-height: 1340px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1350"] {
    max-height: 1350px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1360"] {
    max-height: 1360px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1370"] {
    max-height: 1370px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1380"] {
    max-height: 1380px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1390"] {
    max-height: 1390px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1400"] {
    max-height: 1400px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1410"] {
    max-height: 1410px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1420"] {
    max-height: 1420px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1430"] {
    max-height: 1430px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1440"] {
    max-height: 1440px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1450"] {
    max-height: 1450px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1460"] {
    max-height: 1460px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1470"] {
    max-height: 1470px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1480"] {
    max-height: 1480px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1490"] {
    max-height: 1490px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1500"] {
    max-height: 1500px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1510"] {
    max-height: 1510px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1520"] {
    max-height: 1520px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1530"] {
    max-height: 1530px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1540"] {
    max-height: 1540px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1550"] {
    max-height: 1550px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1560"] {
    max-height: 1560px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1570"] {
    max-height: 1570px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1580"] {
    max-height: 1580px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1590"] {
    max-height: 1590px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1600"] {
    max-height: 1600px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1610"] {
    max-height: 1610px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1620"] {
    max-height: 1620px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1630"] {
    max-height: 1630px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1640"] {
    max-height: 1640px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1650"] {
    max-height: 1650px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1660"] {
    max-height: 1660px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1670"] {
    max-height: 1670px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1680"] {
    max-height: 1680px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1690"] {
    max-height: 1690px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1700"] {
    max-height: 1700px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1710"] {
    max-height: 1710px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1720"] {
    max-height: 1720px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1730"] {
    max-height: 1730px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1740"] {
    max-height: 1740px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1750"] {
    max-height: 1750px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1760"] {
    max-height: 1760px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1770"] {
    max-height: 1770px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1780"] {
    max-height: 1780px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1790"] {
    max-height: 1790px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1800"] {
    max-height: 1800px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1810"] {
    max-height: 1810px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1820"] {
    max-height: 1820px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1830"] {
    max-height: 1830px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1840"] {
    max-height: 1840px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1850"] {
    max-height: 1850px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1860"] {
    max-height: 1860px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1870"] {
    max-height: 1870px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1880"] {
    max-height: 1880px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1890"] {
    max-height: 1890px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1900"] {
    max-height: 1900px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1910"] {
    max-height: 1910px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1920"] {
    max-height: 1920px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1930"] {
    max-height: 1930px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1940"] {
    max-height: 1940px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1950"] {
    max-height: 1950px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1960"] {
    max-height: 1960px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1970"] {
    max-height: 1970px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1980"] {
    max-height: 1980px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1990"] {
    max-height: 1990px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2000"] {
    max-height: 2000px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2010"] {
    max-height: 2010px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2020"] {
    max-height: 2020px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2030"] {
    max-height: 2030px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2040"] {
    max-height: 2040px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2050"] {
    max-height: 2050px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2060"] {
    max-height: 2060px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2070"] {
    max-height: 2070px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2080"] {
    max-height: 2080px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2090"] {
    max-height: 2090px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2100"] {
    max-height: 2100px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2110"] {
    max-height: 2110px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2120"] {
    max-height: 2120px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2130"] {
    max-height: 2130px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2140"] {
    max-height: 2140px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2150"] {
    max-height: 2150px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2160"] {
    max-height: 2160px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2170"] {
    max-height: 2170px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2180"] {
    max-height: 2180px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2190"] {
    max-height: 2190px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2200"] {
    max-height: 2200px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2210"] {
    max-height: 2210px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2220"] {
    max-height: 2220px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2230"] {
    max-height: 2230px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2240"] {
    max-height: 2240px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2250"] {
    max-height: 2250px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2260"] {
    max-height: 2260px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2270"] {
    max-height: 2270px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2280"] {
    max-height: 2280px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2290"] {
    max-height: 2290px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2300"] {
    max-height: 2300px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2310"] {
    max-height: 2310px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2320"] {
    max-height: 2320px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2330"] {
    max-height: 2330px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2340"] {
    max-height: 2340px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2350"] {
    max-height: 2350px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2360"] {
    max-height: 2360px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2370"] {
    max-height: 2370px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2380"] {
    max-height: 2380px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2390"] {
    max-height: 2390px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2400"] {
    max-height: 2400px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2410"] {
    max-height: 2410px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2420"] {
    max-height: 2420px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2430"] {
    max-height: 2430px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2440"] {
    max-height: 2440px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2450"] {
    max-height: 2450px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2460"] {
    max-height: 2460px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2470"] {
    max-height: 2470px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2480"] {
    max-height: 2480px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2490"] {
    max-height: 2490px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2500"] {
    max-height: 2500px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2510"] {
    max-height: 2510px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2520"] {
    max-height: 2520px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2530"] {
    max-height: 2530px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2540"] {
    max-height: 2540px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2550"] {
    max-height: 2550px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2560"] {
    max-height: 2560px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2570"] {
    max-height: 2570px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2580"] {
    max-height: 2580px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2590"] {
    max-height: 2590px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2600"] {
    max-height: 2600px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2610"] {
    max-height: 2610px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2620"] {
    max-height: 2620px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2630"] {
    max-height: 2630px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2640"] {
    max-height: 2640px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2650"] {
    max-height: 2650px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2660"] {
    max-height: 2660px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2670"] {
    max-height: 2670px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2680"] {
    max-height: 2680px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2690"] {
    max-height: 2690px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2700"] {
    max-height: 2700px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2710"] {
    max-height: 2710px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2720"] {
    max-height: 2720px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2730"] {
    max-height: 2730px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2740"] {
    max-height: 2740px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2750"] {
    max-height: 2750px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2760"] {
    max-height: 2760px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2770"] {
    max-height: 2770px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2780"] {
    max-height: 2780px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2790"] {
    max-height: 2790px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2800"] {
    max-height: 2800px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2810"] {
    max-height: 2810px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2820"] {
    max-height: 2820px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2830"] {
    max-height: 2830px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2840"] {
    max-height: 2840px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2850"] {
    max-height: 2850px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2860"] {
    max-height: 2860px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2870"] {
    max-height: 2870px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2880"] {
    max-height: 2880px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2890"] {
    max-height: 2890px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2900"] {
    max-height: 2900px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2910"] {
    max-height: 2910px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2920"] {
    max-height: 2920px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2930"] {
    max-height: 2930px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2940"] {
    max-height: 2940px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2950"] {
    max-height: 2950px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2960"] {
    max-height: 2960px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2970"] {
    max-height: 2970px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2980"] {
    max-height: 2980px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2990"] {
    max-height: 2990px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-1vh"] {
    max-height: 1vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-2vh"] {
    max-height: 2vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-3vh"] {
    max-height: 3vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-4vh"] {
    max-height: 4vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-5vh"] {
    max-height: 5vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-6vh"] {
    max-height: 6vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-7vh"] {
    max-height: 7vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-8vh"] {
    max-height: 8vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-9vh"] {
    max-height: 9vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-10vh"] {
    max-height: 10vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-11vh"] {
    max-height: 11vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-12vh"] {
    max-height: 12vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-13vh"] {
    max-height: 13vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-14vh"] {
    max-height: 14vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-15vh"] {
    max-height: 15vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-16vh"] {
    max-height: 16vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-17vh"] {
    max-height: 17vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-18vh"] {
    max-height: 18vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-19vh"] {
    max-height: 19vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-20vh"] {
    max-height: 20vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-21vh"] {
    max-height: 21vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-22vh"] {
    max-height: 22vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-23vh"] {
    max-height: 23vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-24vh"] {
    max-height: 24vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-25vh"] {
    max-height: 25vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-26vh"] {
    max-height: 26vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-27vh"] {
    max-height: 27vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-28vh"] {
    max-height: 28vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-29vh"] {
    max-height: 29vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-30vh"] {
    max-height: 30vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-31vh"] {
    max-height: 31vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-32vh"] {
    max-height: 32vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-33vh"] {
    max-height: 33vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-34vh"] {
    max-height: 34vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-35vh"] {
    max-height: 35vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-36vh"] {
    max-height: 36vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-37vh"] {
    max-height: 37vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-38vh"] {
    max-height: 38vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-39vh"] {
    max-height: 39vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-40vh"] {
    max-height: 40vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-41vh"] {
    max-height: 41vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-42vh"] {
    max-height: 42vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-43vh"] {
    max-height: 43vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-44vh"] {
    max-height: 44vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-45vh"] {
    max-height: 45vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-46vh"] {
    max-height: 46vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-47vh"] {
    max-height: 47vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-48vh"] {
    max-height: 48vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-49vh"] {
    max-height: 49vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-50vh"] {
    max-height: 50vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-51vh"] {
    max-height: 51vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-52vh"] {
    max-height: 52vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-53vh"] {
    max-height: 53vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-54vh"] {
    max-height: 54vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-55vh"] {
    max-height: 55vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-56vh"] {
    max-height: 56vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-57vh"] {
    max-height: 57vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-58vh"] {
    max-height: 58vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-59vh"] {
    max-height: 59vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-60vh"] {
    max-height: 60vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-61vh"] {
    max-height: 61vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-62vh"] {
    max-height: 62vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-63vh"] {
    max-height: 63vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-64vh"] {
    max-height: 64vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-65vh"] {
    max-height: 65vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-66vh"] {
    max-height: 66vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-67vh"] {
    max-height: 67vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-68vh"] {
    max-height: 68vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-69vh"] {
    max-height: 69vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-70vh"] {
    max-height: 70vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-71vh"] {
    max-height: 71vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-72vh"] {
    max-height: 72vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-73vh"] {
    max-height: 73vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-74vh"] {
    max-height: 74vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-75vh"] {
    max-height: 75vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-76vh"] {
    max-height: 76vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-77vh"] {
    max-height: 77vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-78vh"] {
    max-height: 78vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-79vh"] {
    max-height: 79vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-80vh"] {
    max-height: 80vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-81vh"] {
    max-height: 81vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-82vh"] {
    max-height: 82vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-83vh"] {
    max-height: 83vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-84vh"] {
    max-height: 84vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-85vh"] {
    max-height: 85vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-86vh"] {
    max-height: 86vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-87vh"] {
    max-height: 87vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-88vh"] {
    max-height: 88vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-89vh"] {
    max-height: 89vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-90vh"] {
    max-height: 90vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-91vh"] {
    max-height: 91vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-92vh"] {
    max-height: 92vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-93vh"] {
    max-height: 93vh;
    overflow: auto;
}

.internal-embed.is-loaded[attr="94vh"] {
    max-height: 94vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-95vh"] {
    max-height: 95vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-96vh"] {
    max-height: 96vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-97vh"] {
    max-height: 97vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-98vh"] {
    max-height: 98vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-99vh"] {
    max-height: 99vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-100vh"] {
    max-height: 100vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-101vh"] {
    max-height: 101vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-102vh"] {
    max-height: 102vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-103vh"] {
    max-height: 103vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-104vh"] {
    max-height: 104vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-105vh"] {
    max-height: 105vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-106vh"] {
    max-height: 106vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-107vh"] {
    max-height: 107vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-108vh"] {
    max-height: 108vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-109vh"] {
    max-height: 109vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-110vh"] {
    max-height: 110vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-111vh"] {
    max-height: 111vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-112vh"] {
    max-height: 112vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-113vh"] {
    max-height: 113vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-114vh"] {
    max-height: 114vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-115vh"] {
    max-height: 115vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-116vh"] {
    max-height: 116vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-117vh"] {
    max-height: 117vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-118vh"] {
    max-height: 118vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-119vh"] {
    max-height: 119vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-120vh"] {
    max-height: 120vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-121vh"] {
    max-height: 121vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-122vh"] {
    max-height: 122vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-123vh"] {
    max-height: 123vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-124vh"] {
    max-height: 124vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-125vh"] {
    max-height: 125vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-126vh"] {
    max-height: 126vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-127vh"] {
    max-height: 127vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-128vh"] {
    max-height: 128vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-129vh"] {
    max-height: 129vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-130vh"] {
    max-height: 130vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-131vh"] {
    max-height: 131vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-132vh"] {
    max-height: 132vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-133vh"] {
    max-height: 133vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-134vh"] {
    max-height: 134vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-135vh"] {
    max-height: 135vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-136vh"] {
    max-height: 136vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-137vh"] {
    max-height: 137vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-138vh"] {
    max-height: 138vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-139vh"] {
    max-height: 139vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-140vh"] {
    max-height: 140vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-141vh"] {
    max-height: 141vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-142vh"] {
    max-height: 142vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-143vh"] {
    max-height: 143vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-144vh"] {
    max-height: 144vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-145vh"] {
    max-height: 145vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-146vh"] {
    max-height: 146vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-147vh"] {
    max-height: 147vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-148vh"] {
    max-height: 148vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-149vh"] {
    max-height: 149vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-150vh"] {
    max-height: 150vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-151vh"] {
    max-height: 151vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-152vh"] {
    max-height: 152vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-153vh"] {
    max-height: 153vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-154vh"] {
    max-height: 154vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-155vh"] {
    max-height: 155vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-156vh"] {
    max-height: 156vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-157vh"] {
    max-height: 157vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-158vh"] {
    max-height: 158vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-159vh"] {
    max-height: 159vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-160vh"] {
    max-height: 160vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-161vh"] {
    max-height: 161vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-162vh"] {
    max-height: 162vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-163vh"] {
    max-height: 163vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-164vh"] {
    max-height: 164vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-165vh"] {
    max-height: 165vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-166vh"] {
    max-height: 166vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-167vh"] {
    max-height: 167vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-168vh"] {
    max-height: 168vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-169vh"] {
    max-height: 169vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-170vh"] {
    max-height: 170vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-171vh"] {
    max-height: 171vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-172vh"] {
    max-height: 172vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-173vh"] {
    max-height: 173vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-174vh"] {
    max-height: 174vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-175vh"] {
    max-height: 175vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-176vh"] {
    max-height: 176vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-177vh"] {
    max-height: 177vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-178vh"] {
    max-height: 178vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-179vh"] {
    max-height: 179vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-180vh"] {
    max-height: 180vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-181vh"] {
    max-height: 181vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-182vh"] {
    max-height: 182vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-183vh"] {
    max-height: 183vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-184vh"] {
    max-height: 184vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-185vh"] {
    max-height: 185vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-186vh"] {
    max-height: 186vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-187vh"] {
    max-height: 187vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-188vh"] {
    max-height: 188vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-189vh"] {
    max-height: 189vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-190vh"] {
    max-height: 190vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-191vh"] {
    max-height: 191vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-192vh"] {
    max-height: 192vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-193vh"] {
    max-height: 193vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-194vh"] {
    max-height: 194vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-195vh"] {
    max-height: 195vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-196vh"] {
    max-height: 196vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-197vh"] {
    max-height: 197vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-198vh"] {
    max-height: 198vh;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="h-199vh"] {
    max-height: 199vh;
    overflow: auto;
}

/* WIDTH OF EMBEDS */


.internal-embed.is-loaded[alt~="w-100"] {
    max-width: 100px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-110"] {
    max-width: 110px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-120"] {
    max-width: 120px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-130"] {
    max-width: 130px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-140"] {
    max-width: 140px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-150"] {
    max-width: 150px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-160"] {
    max-width: 160px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-170"] {
    max-width: 170px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-180"] {
    max-width: 180px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-190"] {
    max-width: 190px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-200"] {
    max-width: 200px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-210"] {
    max-width: 210px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-220"] {
    max-width: 220px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-230"] {
    max-width: 230px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-240"] {
    max-width: 240px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-250"] {
    max-width: 250px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-260"] {
    max-width: 260px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-270"] {
    max-width: 270px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-280"] {
    max-width: 280px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-290"] {
    max-width: 290px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-300"] {
    max-width: 300px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-310"] {
    max-width: 310px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-320"] {
    max-width: 320px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-330"] {
    max-width: 330px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-340"] {
    max-width: 340px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-350"] {
    max-width: 350px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-360"] {
    max-width: 360px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-370"] {
    max-width: 370px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-380"] {
    max-width: 380px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-390"] {
    max-width: 390px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-400"] {
    max-width: 400px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-410"] {
    max-width: 410px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-420"] {
    max-width: 420px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-430"] {
    max-width: 430px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-440"] {
    max-width: 440px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-450"] {
    max-width: 450px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-460"] {
    max-width: 460px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-470"] {
    max-width: 470px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-480"] {
    max-width: 480px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-490"] {
    max-width: 490px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-500"] {
    max-width: 500px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-510"] {
    max-width: 510px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-520"] {
    max-width: 520px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-530"] {
    max-width: 530px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-540"] {
    max-width: 540px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-550"] {
    max-width: 550px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-560"] {
    max-width: 560px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-570"] {
    max-width: 570px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-580"] {
    max-width: 580px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-590"] {
    max-width: 590px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-600"] {
    max-width: 600px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-610"] {
    max-width: 610px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-620"] {
    max-width: 620px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-630"] {
    max-width: 630px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-640"] {
    max-width: 640px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-650"] {
    max-width: 650px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-660"] {
    max-width: 660px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-670"] {
    max-width: 670px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-680"] {
    max-width: 680px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-690"] {
    max-width: 690px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-700"] {
    max-width: 700px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-710"] {
    max-width: 710px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-720"] {
    max-width: 720px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-730"] {
    max-width: 730px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-740"] {
    max-width: 740px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-750"] {
    max-width: 750px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-760"] {
    max-width: 760px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-770"] {
    max-width: 770px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-780"] {
    max-width: 780px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-790"] {
    max-width: 790px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-800"] {
    max-width: 800px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-810"] {
    max-width: 810px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-820"] {
    max-width: 820px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-830"] {
    max-width: 830px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-840"] {
    max-width: 840px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-850"] {
    max-width: 850px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-860"] {
    max-width: 860px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-870"] {
    max-width: 870px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-880"] {
    max-width: 880px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-890"] {
    max-width: 890px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-900"] {
    max-width: 900px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-910"] {
    max-width: 910px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-920"] {
    max-width: 920px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-930"] {
    max-width: 930px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-940"] {
    max-width: 940px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-950"] {
    max-width: 950px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-960"] {
    max-width: 960px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-970"] {
    max-width: 970px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-980"] {
    max-width: 980px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-990"] {
    max-width: 990px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1000"] {
    max-width: 1000px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1010"] {
    max-width: 1010px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1020"] {
    max-width: 1020px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1030"] {
    max-width: 1030px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1040"] {
    max-width: 1040px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1050"] {
    max-width: 1050px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1060"] {
    max-width: 1060px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1070"] {
    max-width: 1070px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1080"] {
    max-width: 1080px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1090"] {
    max-width: 1090px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1100"] {
    max-width: 1100px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1110"] {
    max-width: 1110px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1120"] {
    max-width: 1120px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1130"] {
    max-width: 1130px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1140"] {
    max-width: 1140px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1150"] {
    max-width: 1150px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1160"] {
    max-width: 1160px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1170"] {
    max-width: 1170px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1180"] {
    max-width: 1180px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1190"] {
    max-width: 1190px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1200"] {
    max-width: 1200px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1210"] {
    max-width: 1210px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1220"] {
    max-width: 1220px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1230"] {
    max-width: 1230px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1240"] {
    max-width: 1240px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1250"] {
    max-width: 1250px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1260"] {
    max-width: 1260px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1270"] {
    max-width: 1270px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1280"] {
    max-width: 1280px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1290"] {
    max-width: 1290px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1300"] {
    max-width: 1300px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1310"] {
    max-width: 1310px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1320"] {
    max-width: 1320px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1330"] {
    max-width: 1330px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1340"] {
    max-width: 1340px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1350"] {
    max-width: 1350px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1360"] {
    max-width: 1360px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1370"] {
    max-width: 1370px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1380"] {
    max-width: 1380px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1390"] {
    max-width: 1390px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1400"] {
    max-width: 1400px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1410"] {
    max-width: 1410px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1420"] {
    max-width: 1420px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1430"] {
    max-width: 1430px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1440"] {
    max-width: 1440px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1450"] {
    max-width: 1450px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1460"] {
    max-width: 1460px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1470"] {
    max-width: 1470px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1480"] {
    max-width: 1480px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1490"] {
    max-width: 1490px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1500"] {
    max-width: 1500px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1510"] {
    max-width: 1510px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1520"] {
    max-width: 1520px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1530"] {
    max-width: 1530px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1540"] {
    max-width: 1540px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1550"] {
    max-width: 1550px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1560"] {
    max-width: 1560px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1570"] {
    max-width: 1570px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1580"] {
    max-width: 1580px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1590"] {
    max-width: 1590px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1600"] {
    max-width: 1600px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1610"] {
    max-width: 1610px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1620"] {
    max-width: 1620px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1630"] {
    max-width: 1630px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1640"] {
    max-width: 1640px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1650"] {
    max-width: 1650px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1660"] {
    max-width: 1660px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1670"] {
    max-width: 1670px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1680"] {
    max-width: 1680px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1690"] {
    max-width: 1690px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1700"] {
    max-width: 1700px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1710"] {
    max-width: 1710px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1720"] {
    max-width: 1720px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1730"] {
    max-width: 1730px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1740"] {
    max-width: 1740px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1750"] {
    max-width: 1750px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1760"] {
    max-width: 1760px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1770"] {
    max-width: 1770px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1780"] {
    max-width: 1780px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1790"] {
    max-width: 1790px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1800"] {
    max-width: 1800px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1810"] {
    max-width: 1810px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1820"] {
    max-width: 1820px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1830"] {
    max-width: 1830px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1840"] {
    max-width: 1840px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1850"] {
    max-width: 1850px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1860"] {
    max-width: 1860px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1870"] {
    max-width: 1870px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1880"] {
    max-width: 1880px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1890"] {
    max-width: 1890px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1900"] {
    max-width: 1900px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1910"] {
    max-width: 1910px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1920"] {
    max-width: 1920px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1930"] {
    max-width: 1930px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1940"] {
    max-width: 1940px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1950"] {
    max-width: 1950px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1960"] {
    max-width: 1960px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1970"] {
    max-width: 1970px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1980"] {
    max-width: 1980px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1990"] {
    max-width: 1990px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2000"] {
    max-width: 2000px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2010"] {
    max-width: 2010px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2020"] {
    max-width: 2020px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2030"] {
    max-width: 2030px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2040"] {
    max-width: 2040px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2050"] {
    max-width: 2050px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2060"] {
    max-width: 2060px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2070"] {
    max-width: 2070px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2080"] {
    max-width: 2080px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2090"] {
    max-width: 2090px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2100"] {
    max-width: 2100px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2110"] {
    max-width: 2110px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2120"] {
    max-width: 2120px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2130"] {
    max-width: 2130px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2140"] {
    max-width: 2140px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2150"] {
    max-width: 2150px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2160"] {
    max-width: 2160px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2170"] {
    max-width: 2170px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2180"] {
    max-width: 2180px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2190"] {
    max-width: 2190px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2200"] {
    max-width: 2200px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2210"] {
    max-width: 2210px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2220"] {
    max-width: 2220px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2230"] {
    max-width: 2230px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2240"] {
    max-width: 2240px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2250"] {
    max-width: 2250px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2260"] {
    max-width: 2260px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2270"] {
    max-width: 2270px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2280"] {
    max-width: 2280px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2290"] {
    max-width: 2290px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2300"] {
    max-width: 2300px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2310"] {
    max-width: 2310px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2320"] {
    max-width: 2320px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2330"] {
    max-width: 2330px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2340"] {
    max-width: 2340px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2350"] {
    max-width: 2350px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2360"] {
    max-width: 2360px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2370"] {
    max-width: 2370px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2380"] {
    max-width: 2380px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2390"] {
    max-width: 2390px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2400"] {
    max-width: 2400px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2410"] {
    max-width: 2410px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2420"] {
    max-width: 2420px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2430"] {
    max-width: 2430px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2440"] {
    max-width: 2440px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2450"] {
    max-width: 2450px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2460"] {
    max-width: 2460px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2470"] {
    max-width: 2470px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2480"] {
    max-width: 2480px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2490"] {
    max-width: 2490px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2500"] {
    max-width: 2500px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2510"] {
    max-width: 2510px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2520"] {
    max-width: 2520px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2530"] {
    max-width: 2530px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2540"] {
    max-width: 2540px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2550"] {
    max-width: 2550px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2560"] {
    max-width: 2560px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2570"] {
    max-width: 2570px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2580"] {
    max-width: 2580px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2590"] {
    max-width: 2590px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2600"] {
    max-width: 2600px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2610"] {
    max-width: 2610px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2620"] {
    max-width: 2620px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2630"] {
    max-width: 2630px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2640"] {
    max-width: 2640px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2650"] {
    max-width: 2650px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2660"] {
    max-width: 2660px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2670"] {
    max-width: 2670px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2680"] {
    max-width: 2680px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2690"] {
    max-width: 2690px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2700"] {
    max-width: 2700px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2710"] {
    max-width: 2710px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2720"] {
    max-width: 2720px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2730"] {
    max-width: 2730px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2740"] {
    max-width: 2740px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2750"] {
    max-width: 2750px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2760"] {
    max-width: 2760px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2770"] {
    max-width: 2770px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2780"] {
    max-width: 2780px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2790"] {
    max-width: 2790px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2800"] {
    max-width: 2800px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2810"] {
    max-width: 2810px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2820"] {
    max-width: 2820px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2830"] {
    max-width: 2830px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2840"] {
    max-width: 2840px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2850"] {
    max-width: 2850px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2860"] {
    max-width: 2860px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2870"] {
    max-width: 2870px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2880"] {
    max-width: 2880px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2890"] {
    max-width: 2890px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2900"] {
    max-width: 2900px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2910"] {
    max-width: 2910px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2920"] {
    max-width: 2920px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2930"] {
    max-width: 2930px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2940"] {
    max-width: 2940px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2950"] {
    max-width: 2950px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2960"] {
    max-width: 2960px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2970"] {
    max-width: 2970px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2980"] {
    max-width: 2980px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2990"] {
    max-width: 2990px;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-1vw"] {
    max-width: 1vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-2vw"] {
    max-width: 2vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-3vw"] {
    max-width: 3vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-4vw"] {
    max-width: 4vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-5vw"] {
    max-width: 5vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-6vw"] {
    max-width: 6vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-7vw"] {
    max-width: 7vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-8vw"] {
    max-width: 8vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-9vw"] {
    max-width: 9vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-10vw"] {
    max-width: 10vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-11vw"] {
    max-width: 11vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-12vw"] {
    max-width: 12vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-13vw"] {
    max-width: 13vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-14vw"] {
    max-width: 14vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-15vw"] {
    max-width: 15vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-16vw"] {
    max-width: 16vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-17vw"] {
    max-width: 17vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-18vw"] {
    max-width: 18vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-19vw"] {
    max-width: 19vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-20vw"] {
    max-width: 20vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-21vw"] {
    max-width: 21vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-22vw"] {
    max-width: 22vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-23vw"] {
    max-width: 23vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-24vw"] {
    max-width: 24vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-25vw"] {
    max-width: 25vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-26vw"] {
    max-width: 26vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-27vw"] {
    max-width: 27vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-28vw"] {
    max-width: 28vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-29vw"] {
    max-width: 29vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-30vw"] {
    max-width: 30vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-31vw"] {
    max-width: 31vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-32vw"] {
    max-width: 32vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-33vw"] {
    max-width: 33vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-34vw"] {
    max-width: 34vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-35vw"] {
    max-width: 35vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-36vw"] {
    max-width: 36vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-37vw"] {
    max-width: 37vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-38vw"] {
    max-width: 38vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-39vw"] {
    max-width: 39vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-40vw"] {
    max-width: 40vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-41vw"] {
    max-width: 41vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-42vw"] {
    max-width: 42vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-43vw"] {
    max-width: 43vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-44vw"] {
    max-width: 44vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-45vw"] {
    max-width: 45vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-46vw"] {
    max-width: 46vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-47vw"] {
    max-width: 47vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-48vw"] {
    max-width: 48vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-49vw"] {
    max-width: 49vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-50vw"] {
    max-width: 50vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-51vw"] {
    max-width: 51vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-52vw"] {
    max-width: 52vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-53vw"] {
    max-width: 53vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-54vw"] {
    max-width: 54vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-55vw"] {
    max-width: 55vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-56vw"] {
    max-width: 56vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-57vw"] {
    max-width: 57vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-58vw"] {
    max-width: 58vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-59vw"] {
    max-width: 59vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-60vw"] {
    max-width: 60vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-61vw"] {
    max-width: 61vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-62vw"] {
    max-width: 62vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-63vw"] {
    max-width: 63vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-64vw"] {
    max-width: 64vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-65vw"] {
    max-width: 65vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-66vw"] {
    max-width: 66vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-67vw"] {
    max-width: 67vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-68vw"] {
    max-width: 68vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-69vw"] {
    max-width: 69vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-70vw"] {
    max-width: 70vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-71vw"] {
    max-width: 71vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-72vw"] {
    max-width: 72vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-73vw"] {
    max-width: 73vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-74vw"] {
    max-width: 74vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-75vw"] {
    max-width: 75vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-76vw"] {
    max-width: 76vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-77vw"] {
    max-width: 77vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-78vw"] {
    max-width: 78vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-79vw"] {
    max-width: 79vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-80vw"] {
    max-width: 80vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-81vw"] {
    max-width: 81vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-82vw"] {
    max-width: 82vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-83vw"] {
    max-width: 83vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-84vw"] {
    max-width: 84vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-85vw"] {
    max-width: 85vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-86vw"] {
    max-width: 86vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-87vw"] {
    max-width: 87vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-88vw"] {
    max-width: 88vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-89vw"] {
    max-width: 89vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-90vw"] {
    max-width: 90vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-91vw"] {
    max-width: 91vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-92vw"] {
    max-width: 92vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-93vw"] {
    max-width: 93vw;
    overflow: auto;
}

.internal-embed.is-loaded[attr="94vw"] {
    max-width: 94vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-95vw"] {
    max-width: 95vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-96vw"] {
    max-width: 96vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-97vw"] {
    max-width: 97vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-98vw"] {
    max-width: 98vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-99vw"] {
    max-width: 99vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-100vw"] {
    max-width: 100vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-101vw"] {
    max-width: 101vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-102vw"] {
    max-width: 102vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-103vw"] {
    max-width: 103vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-104vw"] {
    max-width: 104vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-105vw"] {
    max-width: 105vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-106vw"] {
    max-width: 106vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-107vw"] {
    max-width: 107vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-108vw"] {
    max-width: 108vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-109vw"] {
    max-width: 109vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-110vw"] {
    max-width: 110vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-111vw"] {
    max-width: 111vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-112vw"] {
    max-width: 112vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-113vw"] {
    max-width: 113vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-114vw"] {
    max-width: 114vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-115vw"] {
    max-width: 115vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-116vw"] {
    max-width: 116vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-117vw"] {
    max-width: 117vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-118vw"] {
    max-width: 118vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-119vw"] {
    max-width: 119vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-120vw"] {
    max-width: 120vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-121vw"] {
    max-width: 121vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-122vw"] {
    max-width: 122vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-123vw"] {
    max-width: 123vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-124vw"] {
    max-width: 124vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-125vw"] {
    max-width: 125vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-126vw"] {
    max-width: 126vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-127vw"] {
    max-width: 127vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-128vw"] {
    max-width: 128vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-129vw"] {
    max-width: 129vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-130vw"] {
    max-width: 130vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-131vw"] {
    max-width: 131vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-132vw"] {
    max-width: 132vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-133vw"] {
    max-width: 133vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-134vw"] {
    max-width: 134vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-135vw"] {
    max-width: 135vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-136vw"] {
    max-width: 136vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-137vw"] {
    max-width: 137vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-138vw"] {
    max-width: 138vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-139vw"] {
    max-width: 139vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-140vw"] {
    max-width: 140vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-141vw"] {
    max-width: 141vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-142vw"] {
    max-width: 142vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-143vw"] {
    max-width: 143vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-144vw"] {
    max-width: 144vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-145vw"] {
    max-width: 145vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-146vw"] {
    max-width: 146vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-147vw"] {
    max-width: 147vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-148vw"] {
    max-width: 148vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-149vw"] {
    max-width: 149vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-150vw"] {
    max-width: 150vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-151vw"] {
    max-width: 151vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-152vw"] {
    max-width: 152vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-153vw"] {
    max-width: 153vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-154vw"] {
    max-width: 154vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-155vw"] {
    max-width: 155vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-156vw"] {
    max-width: 156vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-157vw"] {
    max-width: 157vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-158vw"] {
    max-width: 158vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-159vw"] {
    max-width: 159vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-160vw"] {
    max-width: 160vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-161vw"] {
    max-width: 161vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-162vw"] {
    max-width: 162vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-163vw"] {
    max-width: 163vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-164vw"] {
    max-width: 164vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-165vw"] {
    max-width: 165vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-166vw"] {
    max-width: 166vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-167vw"] {
    max-width: 167vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-168vw"] {
    max-width: 168vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-169vw"] {
    max-width: 169vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-170vw"] {
    max-width: 170vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-171vw"] {
    max-width: 171vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-172vw"] {
    max-width: 172vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-173vw"] {
    max-width: 173vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-174vw"] {
    max-width: 174vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-175vw"] {
    max-width: 175vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-176vw"] {
    max-width: 176vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-177vw"] {
    max-width: 177vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-178vw"] {
    max-width: 178vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-179vw"] {
    max-width: 179vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-180vw"] {
    max-width: 180vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-181vw"] {
    max-width: 181vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-182vw"] {
    max-width: 182vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-183vw"] {
    max-width: 183vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-184vw"] {
    max-width: 184vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-185vw"] {
    max-width: 185vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-186vw"] {
    max-width: 186vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-187vw"] {
    max-width: 187vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-188vw"] {
    max-width: 188vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-189vw"] {
    max-width: 189vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-190vw"] {
    max-width: 190vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-191vw"] {
    max-width: 191vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-192vw"] {
    max-width: 192vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-193vw"] {
    max-width: 193vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-194vw"] {
    max-width: 194vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-195vw"] {
    max-width: 195vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-196vw"] {
    max-width: 196vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-197vw"] {
    max-width: 197vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-198vw"] {
    max-width: 198vw;
    overflow: auto;
}

.internal-embed.is-loaded[alt~="w-199vw"] {
    max-width: 199vw;
    overflow: auto;
}

