
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vampire's Nest</title>
        <link rel="icon" href="icon.png">
    <link href="/style.css" rel="stylesheet">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Special+Elite&display=swap">
    
  </head>
  
  <body>


<style>
:root {
   content: red;
 }
 
 body {
   background-image: url("background.jpg");
   background-repeat: no-repeat;
   background-attachment: fixed;
   background-size: cover;
   font-family: "Special Elite", monospace;
   color: red;
       }

* {
 box-sizing: border-box;
}

#container {
 max-width: 900px;
 margin: 0 auto;
 position: relative;
 z-index: 1;
}
          
      a:link {
        color: #cfbb9c;
        background-color: transparent;
        text-decoration: none;
      }
      a:visited {
        color: #cfbb9c;
        background-color: transparent;
        text-decoration: none;
      }
      a:hover {
        color: #cfbb9c;
        background-color: transparent;
        text-decoration: underline;
      }

        hr {
          border: 2px dashed red;
        }
  #navbar {
   height: 117px;
   position: relative;
   z-index: 1;
   justify-content: center;
   text-align: center;
  }
  
  .navbuttons {
   display: inline-block;
   transition: all 100ms ease;
   transition-delay: 0ms;
  }
  .navbuttons:hover {
   transform: translateY(-11px);
  }

.tooltip {
  position: relative;
  display: inline-block;
}

.tooltip .tooltiptext {
  visibility: hidden;
  background-color: black;
  color: red;
  text-align: center;
  width: 100px;
  border-radius: 6px;
  padding: 6px;
  border: 1px dashed red;
  position: absolute;
  z-index: 4;
  top: 140px;
  left: 20px;
}

.tooltip:hover .tooltiptext {
  visibility: visible;
}

  #flex {
   display: flex;
   justify-content: space-around;
   position: relative;
   z-index: 1;
  }

  aside {
   width: 240px;
   padding: 10px;
   position: relative;
  }

  main {
   flex: 1;
   padding: 20px;
   order: 2;
   text-align: center;
   border: 3px dashed red;
   border-radius: 10px;
   max-width: 600px;
   margin-left: 15px;
   margin-right: 15px;
   background-image: linear-gradient(rgba(255,	0, 0, 0), rgba(255,	0,	0, .5));
   position: relative;
  }

  #leftSidebar {
   order: 1;
   border: 3px dashed red;
   border-radius: 10px;
   background-image: linear-gradient(rgba(255, 0, 0, 0), rgba(255, 0, 0, .4));
   position: relative;
  }

  #rightSidebar {
    order: 3;
   border: 3px dashed red;
   border-radius: 10px;
   background-image: linear-gradient(rgba(255, 0, 0, 0), rgba(255, 0, 0, .4));
   position: relative;
  }

  footer {
   width: 100%;
   height: 123px;
   text-align: center;
   padding: 20px;
   position: relative;
  }

  .box {
   padding: 10px;
   text-align: justify;
  }
  
  .borderedbox {
   padding: 10px;
   border: 2px dashed red;
   border-radius: 10px;
  }
  
  .updates {
   border: 2px dashed red;
   padding: 10px;
   border-radius: 10px;
   overflow: scroll;
   height: 170px;
   font-size: smaller;
   background-color: rgb(255, 0, 0, .2);
  }
            
  #topBar {
   width: 100%;
   height: 30px;
   padding: 10px;
  }

    #floatyliv {
    background-image: url(oliverpaint.png);
    background-size: cover;
    width: 312px;
    height: 535px;
    margin-left: 25px;
    margin-top: 15px;
    background-repeat: no-repeat;
    position: absolute;
    z-index: 3;
    image-rendering: initial;
    filter: drop-shadow(3px 3px 4px rgba(0,0,0,0.5));
    }
    
    #skrilli {
      position: absolute;
      z-index: 3;
      background-image: url(skrilliantfloaternew.png);
      background-size: cover;
      width: 177px;
      height: 350px;
      margin-left: 1250px;
      margin-top: 1000px;
    animation: skrilli 1s infinite;
    animation-timing-function: ease-in-out;
    }
 
@keyframes skrilli {
    0% { transform: translate(0,  0px); }
    50%  { transform: translate(0, 15px); }
    100%   { transform: translate(0, -0px); }    
}

    
    .nestbox {
      width: 205px;
      height: 40px;
      overflow: scroll;
      background-color: rgb(255, 0, 0, 0.2);
      padding: 3px;
      font-size: x-small;
    }
    
    .linkback {
      width: 200px;
      font-size: small;
    }
    
    .todolist {
      border: 2px dashed red;
      padding: 10px;
      border-radius: 10px;
      overflow: scroll;
      font-size: smaller;
      background-color: rgb(255, 0, 0, 0.2)
    }
    
    .politik {
      max-width: 550px;
      max-height: 350px;
      overflow: scroll;
      border-radius: 10px;
      background-image: linear-gradient(rgba(255, 0 , 0, 0), rgba(255, 0, 0, .35));
      text-align: justify;
      padding: 10px;
    }
    
    #engie {
    background-image: url(tinydeskengie.gif);
    width: 90px;
    height: 90px;
    margin-left: 1250px;
    margin-top: 2050px;
    background-repeat: no-repeat;
    position: absolute;
    z-index: 3;
    image-rendering: initial;
    filter: drop-shadow(3px 3px 4px rgba(0,0,0,0.5));
    }
.abtme {<-forhalloween
  background-image: url(abtme.png);
  background-size: cover;
  width: 200px;
  height: 50px;
  position: absolute;
  z-index: 2;
  top: 400px;
  left: 235px;
}

        </style>
              
  <div class="tooltip"><span class="tooltiptext">say hi to Oliver! They/them!</span><div id="floatyliv"></div></div>
  <div id="engie"></div>
  <div id="skrilli"></div>
  <!--<div class="abtme"></div>-->
    
        <center><img src="vampiresdentitle.png" width="1200" height="240">        
    
               
            <div id="headerArea">
        <nav id="navbar">
    <div class="navbuttons"><a href="https://lupinus.neocities.org"><img src="homebutton.png" width="150"></a></div>
    <div class="navbuttons"><a href="https://lupinus.neocities.org/gallery"><img src="gallerybutton.png" width="150"></a></div>
    <div class="navbuttons"><a href="https://lupinus.neocities.org/cast"><img src="castbutton.png" width="150"></a></div>
    <div class="navbuttons"><a href="https://lupinus.neocities.org/blinkies"><img src="blinkiesbutton.png" width="150"></a></div>
    <div class="navbuttons"><a href="https://lupinus.neocities.org/shrinedirectory"><img src="shrinesbutton.png" width="150"></a></div>
    <div class="navbuttons"><a href="https://lupinus.neocities.org/ecology"><img src="ecologybutton.png" width="150"></a></div>
    <div class="navbuttons"><a href="https://lupinus.neocities.org/readz"><img src="reads.png" width="150"></a></div>
          </nav>
            </div></center> 
            
               <div id="container">               
    <div id="flex">
        <aside id="leftSidebar">
             <div class="box">
     <div class="navbuttons"><a href="https://lupinus.neocities.org/businesscard"><img src="abtme1.png" width="200"></a></div>
   Hello! My name's Loopy. I'm a white twenty-something full time wage slave from California who loves art, history, botany, counterculture, metal music, ecology, and vampires. <strong>They/Them!</strong>
             </div>
             
    <center><br><img src="skeleton.gif" width="150" height="20">
    <img src="skullnbones.gif" width="150" height="20">
    <img src="rip.gif" width="150" height="20">
    <img src="butch4butch.gif" width="150" height="20">

  <hr>
        
          <div class="navbuttons"><a href="https://decolonizepalestine.com/"><img src="decolonizepalestine.png" width="200" alt="Decolonize Palestine"></a></div>
          <div class="navbuttons"><a href="https://www.house.gov/representatives/find-your-representative"><img src="reps.png" width="200" alt="Find your county representative here"></a></div>
          <div class="navbuttons"><br><a href="https://bdsmovement.net/Act-Now-Against-These-Companies-Profiting-From-Genocide"><img src="bdsboycottbutton.png" width="200" alt="Palestinian BDS Movement Boycotts"></a></div>
          <img src="comfort.gif" width="200" alt="Comfort the afflicted, afflict the comfortable">
    
    <hr>
    Cool sites to check out!
    <hr>
        <br><div class="navbuttons"><a href="https://itai-yo.neocities.org/"><img src="https://itai-yo.neocities.org/pics/blinkieznstampz/itai-yo.gif" width="88" height="31"></a></div>
        <div class="navbuttons"><a href="https://atomicgothic.neocities.org/"><img src="ag_main_button.gif"></a></div>
        <div class="navbuttons"><a href="https://berii.neocities.org"><img src="https://berii.neocities.org/button.gif"></a></div>
        <div class="navbuttons"><a href="https://vulturpolitik.neocities.org/"><img src="https://vulturpolitik.neocities.org/img/vulturblinkie.gif" width="88"></a></div>
        <div class="navbuttons"><a href="https://kornloser.neocities.org/"><img src="https://kornloser.neocities.org/pics/sitebutton.png" width="88" height="31"></a></div>
        <div class="navbuttons"><a href="https://fortisarbor.neocities.org"><img src="https://fortisarbor.neocities.org/graphics/sitebutton.png" alt="Fortis Arbor button"></a></div>
        <div class="navbuttons"><a href="https://organicrobot.neocities.org/"><img src="https://organicrobot.neocities.org/Images/Index/button.gif" width="88" height="31"></a></div>
        <div class="navbuttons"><a href="https://bugcreature.neocities.org/queercore"><img src="https://bugcreature.neocities.org/images/queercore/queercore.gif" width="88" height="31"></a></div>
        <div class="navbuttons"><a href="https://alexorcist.neocities.org/"><img src="https://alexorcist.neocities.org/images/neo%20button%20done.gif" width="88"></a></div>
        <div class="navbuttons"><a href="https://digibun.neocities.org" target="_blank"><img src="https://digibun.neocities.org/img/digibun.png"></a></div>
        <div class="navbuttons"><a href="https://ghostscape.neocities.org/"><img src="https://ghostscape.neocities.org/button.gif"></a></div>
        <div class="navbuttons"><a href="https://scilab.neocities.org" target="_blank"><img src="https://res.cloudinary.com/dpdevbgml/image/upload/v1704396511/button_3_ei0vtc.png"></a></div>
        <div class="navbuttons"><a href="https://dreadromantic.neocities.org" target="blank"><img src="https://dreadromantic.neocities.org/other_images/my%20button.png"></a></div>
        <div class="navbuttons"><a href="https://zombiie.neocities.org/"><img src="https://zombiie.neocities.org/images/button.gif" width="88" height="31"></a></div>
        <div class="navbuttons"><a href="https://montysmortuary.neocities.org/"><img src="https://montysmortuary.neocities.org/images/ezgif.com-resize.gif"></a></div>
        <div class="navbuttons"><a href="https://shadowmoses.neocities.org/"><img src="https://shadowmoses.neocities.org/siteassets/sitebutton3.gif" width="88" height="31"></a></div>
        <div class="navbuttons"><a href="https://n-razm.neocities.org/"><img src="https://n-razm.neocities.org/resources/images/buttons/n-razm_button_v2.png"></a></div>
        <div class="navbuttons"><a href="https://bensect.neocities.org/"><img src="https://bensect.neocities.org/site%20button.png"></a></div>
        <div class="navbuttons"><a href="https://lovevy.neocities.org/"><img src="https://lovevy.neocities.org/images/arobutton.gif"></a></div>
        <div class="navbuttons"><a href="https://worm-lungs.neocities.org/"><img src="https://worm-lungs.neocities.org/worm-lungs-button.gif"></a></div>
        <div class="navbuttons"><a href="https://ultra-tetra.neocities.org/"><img src="neopananimated.gif"></a></div>
    <hr>
            
    <div class="linkback"><center>Link back to Vamp's Nest!
    <br><img src="vampiresnestbutton.gif">
    <div class="nestbox">&lt;a href="https://lupinus.neocities.org/"&gt; &lt;img src="https://lupinus.neocities.org/vampiresnestbutton.gif"&gt; &lt;/a&gt;</div>
    </center></div></center>
    
    <hr>
    
    <div class="box"><center><small>You Are Visitor:</small>
    <br><a href="https://www.free-website-hit-counter.com"><img src="https://www.free-website-hit-counter.com/c.php?d=7&id=159750&s=40" border="0" width="200" alt="Website Hit Counter"></a></center></div>
            
    <hr>
            
            <center><a href="hhttps://lupinus.neocities.org/biscuitshrine"><small>This site is dedicated to Biscuit! We love u, baby!
            <br><img src="bisky.jpg" style="height:200px;width:200px;object-fit:cover;border-radius:10px;">
            <br>Dec 5th, 2009 - May 29th, 2023</small></a></center>
            
      <!--<p><center>-->
        <!--<img src="frankenstein.png"><img src="eraserhead.gif">-->
        <!--<img src="alienstamp2.gif"><img src="sawstamp.png">-->
        <!--<img src="americanwarewolfstamp.png"><img src="reanimatorstamp.png">-->
        <!--<img src="evildeadstamp.png"><img src="elvirastamp.png"></center> -->

        </aside>
            
            
  <main>
    <img src="welcomesign1.png" width="550" height="191">
    
    <div class="box">The Vampire's Nest is a personal site for artwork, shrines, ocs, and cool stuff I salvage. The usual warnings for <strong>eyestrain</strong> and <strong>flashing images</strong> apply to all pages, in addition to warnings for <strong>blood, gore, swearing, crude humor,</strong> and <strong>suggestive themes</strong>. You can find other cool Neocities websites on the left sidebar; below that, some resources to help Palestine during the ongoing genocide. On the right sidebar you can find Vampire! Magazine (an OC zine) and the OC pages. Below that, the update log and some fun bits 'n bobs. Feel free to steal my blinkies! No credit needed! 
    Hail satan, and have a lovely afternoon!
    
    <hr>
    
    </div>
    <div class="box"><center><h3>DONATE TO PALESTINIAN RELIEF NOW!</h3>
      <div class="navbuttons"><a href="https://www.pcrf.net/"><img src="PCRFbutton.png" width="150" alt="PCRF: Palestine Children's Relief Fund charity donation button"></a></div>
      <div class="navbuttons"><a href="https://docs.google.com/spreadsheets/d/1-DDMFyn-ttboPXrz1bB3MFk7BlzCwfugh4259Wh7U1s/htmlview#"><img src="evacbutton.png" width="150" alt="Evacuation Fundraisers button"></a></div>
      <div class="navbuttons"><a href="https://helpgazachildren.notion.site/8517fdaec81a4568a0c1d1ddd0496732?v=59c939b12256426398ab7056b201e952"><img src="HELPGAZACHILDRENbutton.png" width="150" alt="Help Gaza Children: Notion site central hub charity donation button"></a></div>
      <p>See the links on the left sidebar for the history of the genocide in Palestine, active BDS movement boycotts, and a local representative locator that you can use to contact them and enact change.
      <br><center><img src="https://64.media.tumblr.com/1ad757bf44965a5fdfdc889942f0c674/97e0582dfe651544-b4/s250x400/d25d392835240498f7fd9b11a6721cc790a2f831.gif" alt="Free Palestine"></center>

      </center>
      </div>
    
    <hr>
    
<div class="politik">
<img src="political.png" alt="Why does it always have to be political?" style="float:left;width:300px;">
This page (and the website as a whole) is a love letter to anarchy and punk culture. Why focus so strongly on politics? <a href="https://tracyabell.com/2023/11/11/palestinian-poetry/">"In order for me to write poetry that isn't political, I must listen to the birds, and in order to hear the birds, the warplanes must be silent." —Marwan Makhoul</a> 
<br>I could go on and on about how politics effects everything we do, but at the end of the day, punk is political because we got done dirty by the status quo in myriad ways and we just want to live our lives and listen to bangin' music. A big part of being punk is realizing the world as we know it is built on training people to be polite and digressing while the rich and powerful step on their necks and tell them it's supposed to be this way (that it's always been this way). All the bullshit we live under is a symptom of a sick society running the planet into the ground — and taking as many innocent people with it as possible. So, why NOT make it political? Use your space and time on this earth to scream to power, on behalf of the people who are dying by the thousands in the name of a handful of rich cunts' bottom lines. Find your representatives. Show up to protests. Graffiti something. Do everything you can to make everyone's lives a little better.  
</div>
    <hr>

    <!--<p><img src="orangestamp1.png"><img src="purplestamp8.gif"><img src="halloweenstamp2.gif"><img src="purplestamp2.png"><img src="happyweenstamp.gif">-->

         <div class="box">
      <center><img src="coolart.png" width="300">
      <br><img src="https://64.media.tumblr.com/a5a23488fb0c2aac5ca85a9f3160f311/93e7f106e12d7d26-36/s1280x1920/35190dec340a40c2ff2466fd32bbe53303c86a93.png" width="500"></center>
      <br>"Start HRT Today! What Are You Waiting For?" by <a href="https://www.tumblr.com/sylladextrous/765228645285609472/start-hrt-today-whatre-you-waiting-for-fuck-it">Sylladextrous</a>.
      <br>I love this little propaganda piece so much. The world could always use more trans women &lt;3
     <hr>
    
      <br><strong>I'm always a little disappointed I can't put MORE art on here but I do have limited space. For more cool art, check out my <a href="https://lupinus-bicolor.tumblr.com/archive/tagged/aesthetic">Tumblr tag!</a></strong>
      <!--<center><img src="spiderpumpkins.png" width="550"></center>-->
          </div>

  </main>
                
                
  <aside id="rightSidebar">
    <div class="box">
      <img src="button1.png" width="200" height="92" alt="Best viewed on desktop">
      <img src="button2.png" width="200" height="89" alt="Image heavy">
      <img src="button3.png" width="200" height="90" alt="Work in progress">
    </div>
    
    <hr>
    
      <center>
      <br><div class="navbuttons"><a href="https://lupinus.neocities.org/vampiremagazine"><img src="vampstamp.png" alt="Vampire! Magazine"></a></div>
      <br><div class="navbuttons"><a href="https://lupinus.neocities.org/oliverspage"><img src="oliverspagebutton.png" width="200" alt="Oliver's Page"></a></div>
      <br><div class="navbuttons"><a href="https://lupinus.neocities.org/salierispage"><img src="salierispagebutton.png" width="200" alt="Salieri's Page"></a></div>
      <br><div class="navbuttons"><a href="https://lupinus.neocities.org/skrilliantspage"><img src="skrilliantspagebutton.png" width="200" alt="Skrilliant's Page"></a></div>
      </center>
              <div class="updates">
                <h3>Update Log!</h3>
                <p>November 28th, 2024:
                <br>-New Cool Art of the Week!
                <br>-Added the Favorite Films section to the Favorite Shit page! Expect reviews and ramblings aplenty in the future!
                <br>-Decorated the Favorite Shit page with more xenomorphs :)
                <br>-New stamps, blinkies, and Picmix images added to Blinkies!
                <br>-Added a little Salieri drawing to the Readz page
                <br>-Added a link to my Dreamwidth journal in the Ecology page!
                <p>November 14th, 2024:
                <br>-New Cool Art of the Week!
                <br>-Changed the background of the Rainbow Shrine
                <br>-Updated the Directory links
                <br>-New artwork in the Gallery!
                <br>-New stamps and blinkies!
                <br>-Put in a little ramble on the Business Card. Will likely remove it.
                <p>November 2nd, 2024:
                <br>-Vamp's Nest has shed its Halloween skin! We're back to normal, baby!
                <br>-New blinkies and stamps in the Blinkies page!
                <br>-Tweaking the "Favorite Shit" page. Still need a better name for it.
                <br>-New Cool Art of the Week!
                <p>October 21st, 2024:
                <br>-New (old) art added to the Gallery!
                <br>-New Cool Art of the Week!
                <br>-New mulch post in the "Plant Rants" section of the Ecology page!
                <p>October 16th, 2024:
                <br>-New Cool Art of the Week!
                <br>-New stamps and blinkies!
                <br>-Stamps have been organized by color!
                <br>-Minor updates to the Anarchy page! Keep an eye out!
                <p>October 9th, 2024:
                <br>-THANKS FOR 200 FOLLOWERS ON NEOCITIES! Wow you guys like vampires huh
                <br>-New blinkies and stamps!
                <br>-New Cool Art of the Week!
                <br>-Commission info pages completed!
                <br>-New ebooks added to the Readz page!
                <p>October 1st, 2024:
                <br>-New Cool Art of the Week!
                <br>-New linked site buttons on the left sidebar!
                <p>September 28th, 2024:
                <br>-The Halloween Update is here!
                <p>September 24th, 2024:
                <br>-New Cool Art of the Week!
                <br>-Couple new articles added to Readz!
                <br>-Working on commission pages!
                <p>September 17th, 2024:
                <br>-New Cool Art of the Week!
                <br>-Updated the Directory to look a little snazzier
                <br>-Anarchy page is in its infancy! Don't look yet LOL
                <br>-Going to throw together a commission page later as well
                <p>September 11th, 2024:
                <br>-New Cool Art of the Week!
                <br>-Pending membership in the Transing the Web webring!
                <p>September 7th, 2024:
                <br>-New Blinkies! You know where to find 'em
                <br>-CLICKSPLOSIONS have been added to the rainbow shrine. I'll add a couple buttons that don't do anything, just to show off the new feature :)
                <br>-Finally figured out how to float Skrilliant on the side here! Say hi!
                <br>-Working on a Vampire! Magazine issue No.8 (actual issue number 2, lol)
                <br>-Anarchy section soon to come on the home page!
                <p>August 26th, 2024:
                <br>-Added a bunch of new stickers to the Rainbow Shrine
                <br>-Made some new blinkies! Find them on the Blinkies page
                <br>-One (1) older art piece added to the Gallery page
                <br>-Last major update to the Animal Jam shrine! Added the Artists' section, the Jam-a-Gram icon, and the "See you in Jamaa!" widget.
                <br>-New Cool Art of the Week!
                <p>August 18th, 2024:
                <br>-First original work published to the Writings page!
                <br>-New Cool Art of the Week!
                <p>August 16th, 2024:
                <br>-Original Writings page has been added and linked to the Readz page! Heavy page construction to follow
                <p>August 13th, 2024: 
                <br>-The Animal Jam Shrine has been completed!
                <br>-New Cool Art of the Week!
                <p>August 10th, 2024:
                <br>-New stamps, blinkies, dividers, and picmix gifs have been added to the Blinkies page!
                <br>-Updated category text bumpers with some fun fonts on the Blinkies page!
                <br>-Expect the Blinkies page layout to change for easier accessability soon
                <br>-Animal Jam shrine's layout is complete; all that's needed is the content!
                <br>-The Favorite Shit page has been added to the Directory.
                <br>-Old updates have been moved to the <a href="https://lupinus.neocities.org/pastupdates">Past Updates</a> page.
                <p>August 4th, 2024: 
                <br>-New blinkies added to the Blinkies Page
                <br>-Work on the Animal Jam Shrine is maaaaaybe 90% finished
                <br>-New Cool Art of the Week!
                <br>-Edited my little punk manifesto also :)
                <p>July 26th, 2024:
                <br>-Rainbow shrine has been completed!
                <br>-Shrine Directory and Page Directory have been updated in accordance
                <br>-Making a little page for all my favorite characters and whatnot
                <p>July 24th, 2024:
                <br>-The Rainbow Shrine has been created! Completion will follow soon :)
                <br>-New Cool Art of the Week!
                <br>-Lots of new entries in the Readz page!
                <br>-Tinkering with Oliver's page!
                <br>-New Transformers fanart in the Gallery!
                <p>July 14th, 2024:
                <br>-New Cool Art of the Week!
                <br>-New additions to the Readz page!
                <p>July 10th, 2024: 
                <br>-Still chipping away at the Animal Jam shrine!
                <br>-New blinkies have been uploaded!
                <br>-No Cool Art of the Week this week, I'm very tired.
                <br>-New resources linked on the Ecology page
                <p>July 2nd, 2024:
                <br>-I have been whacking this stupid animal jam shrine with the metaphorical hammer for three days now and I think it's finally learned to behave itself. Yippee!
                <br>-(obviously) work on the Animal Jam shrine is well underway
                <br>-New Cool Art of the Week!
                <br>-If you see my test dump page laying around, dont worry about it. its ugly for a reason.
                <br>-Blinkies have officially been sorted by color!
                <br>-New blinkies!
                <p>June 25th, 2024:
                <br>-New Cool Art of the Week!
                <p>June 22nd, 2024:
                <br>-New graphics and blinkies added to the Blinkies page!
                <br>-Added official valve nyan potaDOS illustration to the Portal Shrine!
                <br>-New art of the week! (apologies for lazy commentary lately, I've been tired)
                <br>-Working out some aesthetic tweaks on Skrilliant's OC page
                <br>-Work has begun on sorting blinkies by color! Pray for me.
                <p>June 10th, 2024:
                <br>-Attempting to fix my floaty Skrilliant image :(
                <br>-Minor additions to Loopy's Plant Picks section of the Ecology page
                <br>-New cool art of the week
                <br>-Tiny Desk Engineer has been added
                <br>-Minor changes to the Blinkies page; just adjusting some font sizes
                <p>June 5th, 2024:
                <br>-Added the Evacuation Funds button for Gaza citizens; clicking it will lead you to a list of individual family fundraisers that urgently need donations.
                <br>-Added Loopy's Plant Picks section to the Ecology Page (check it out if you live in CA :))
                <br>-Continuing minor updates to Skrilliant's oc page
                <br>-New cool art of the week!
                <p>June 3rd, 2024:
                <br>-Went ALL OUT on the cheesey goth look of Skrilliant's OC page! Still not completely satisfied with it, but it's been fun.
                <br>-New art of the week!
                <br>-Added some site buttons to check out
                <br>-Added new fanlist buttons below!
                <p>May 30th, 2024:
                <br>-MAJORLY revamped the Cast page! Check it out!
                <br>-New art of the week!
                <br>-big sleeby.
                <p>May 24th, 2024: 
                <br>-Fixed a few broken links on the Readz page
                <br>-Check out the new fan list buttons below this :)
                <br>-Added swag as hell buttons for Neocities sites to check out !! please do check them out, they're awesome
                <p>May 21st, 2024:
                <br>-New stamps and blinkies on the Blinkies page! (I apologize for how many I have. I might be lowkey hooked on collecting them)
                <br>-Archiving last year's updates <a href="https://lupinus.neocities.org/pastupdates">HERE</a>
                <p>May 16th, 2024:
                <br>-Added some hover text to the Oliver drawing at the top of this page :)
                <br>-Minor spacing tweaks to a few pages
                <br>-New stamps and blinkies added to the Blinkies page!
                <br>-debating whether or not i should make some more oc pages or leave them as the little cards i'll add to the Cast page.
                <br>-Making dedicated oc pages is fun but very time consuming.... hmmmmmm
                <br>-Then again I do So love collecting graphics for them.
                <br>-oughh

              </div>

  <div class="box">
    <center>
     (Fake) Ad Space
      <img src="https://64.media.tumblr.com/e13672728f107d685eb260b3ba704434/8ad52f26931b81b3-cc/s500x750/32de1e6a7147df16b5c0074af70de9af7bf9fc9d.png" width="200" alt="Why don't YOU look like THIS? (skeleton) THIS IS THE IDEAL BODY">
      <img src="https://imgur.com/CA4wB00.png" width="200" alt="Say no to false dichotomies! Join the vampire warewolf alliance">
      <img src="https://64.media.tumblr.com/cc99a35b7f90869224feadfbf9de160b/8ad52f26931b81b3-fb/s1280x1920/84926397f8211801d5cac7ac645b97e20cf23dea.png" width="200" alt="Suck on this! Barry's Bloody Bubblegum Pops">
      <img src="scrrd.jpg" width="200" alt="I'm scared and I'm not having any fun">
      <!--<br><img src="trickortreat.gif">-->
      <!--<br><img src="imafreak.gif" width="150" height="20">-->
      <!--<br><img src="michaelmeyers.gif" width="150" height="20">-->
      <!--<br><img src="pumpkinhead.gif" width="150" height="20">-->
      <!--<br><img src="foundfootage.gif" width="150" height="20">-->
      <!--<br><img src="thegreatpumpkin.gif" width="150" height="20">-->
      <!--<br><img src="residentofhalloweentown.gif" width="150" height="20">-->
      <!--<br><img src="itsalwayshalloween.gif" width="150" height="20">-->
      <!--<br><img src="itsaghosttown.gif" width="150" height="20">-->
      <!--<br><img src="halloweenbats.gif" width="150" height="20">-->
      <!--<br><img src="happyhalloween3.gif" width="150" height="20">-->
      <!--<br><img src="booaholic.gif" width="150" height="20">-->
      <!--<br><img src="boopurple.gif" width="150" height="20">-->
      <!--<br><img src="ilovehalloween.gif" width="150" height="20">-->
      <!--<br><img src="thecrow.gif" width="150" height="20">-->
      <!--<br><img src="pumpkintime.gif" width="150" height="20">-->
      <!--<br><img src="alien.gif" width="150" height="20">-->
      <!--<br><img src="silenceofthelambs.gif" width="150" height="20">-->
      <!--<br><img src="texaschainsaw.gif" width="150" height="20">-->
      <!--<br><img src="hellraiser.gif" width="150" height="20">-->
      <!--<br><img src="hannibalblinkie.gif" width="150" height="20">-->
      <!--<br><img src="blairwitch.gif" width="150" height="20">-->
      <!--<br><img src="greenbats.gif" width="150" height="20">-->
      <!--<br><img src="happyhalloween2.gif" width="150" height="20">-->
      <!--<br><img src="gimmesomepumpkinpie.gif" width="150" height="20">-->
      <!--<br><img src="halloweenstamp1.gif" width="96"><img src="happyhalloweenstamp.gif" width="96">-->
      <!--<br><img src="halloweenstamp4.png" width="96"><img src="halloweenstamp3.png" width="96">-->
      <!--<br><img src="ihearthalloweenstamp.png" width="96"><img src="purpleweenstamp.gif" width="96">-->
      <!--<br><img src="halloweenstamp5.png" width="96"><img src="halloweenstamp6.gif" width="96">-->
      </center>
    </div>
    
    <div class="todolist">
      To Do List:
      <br>-Make a media page
      <br>-Make a random aesthetic dump page
      <br><s>-Sort blinkies by color</s>
      <br><s>-work on the Portal Shrine</s>
      <br><s>-ADD STAMPS!</s>
      <br>-graffiti the homepage!
      <br><s>-overhaul the Meat Shrine</s>
      <br>-Look at this Tiny Desk Engineer →
      <br>-Dork around with iframes?
    </div>
    
    <hr>
    
    <center>FANLISTS AND WEBRINGS
    <br>
    <a href="https://fanlistings.nickifaulk.com/skulls/"><img src="skullfanbuttonsmall.png"></a>
    <a href="https://10-31.net/fans/spooky/buttons.php"><img src="halloweendecorfanbuttonsmall.png"></a>
    <a href="https://10-31.net/halloween/buttons.php"><img src="halloweenfanbuttonsmall.png"></a>
    <a href="http://lectersgirl.altervista.org/htv"><img src="hannibalfanbuttonsmall.png"></a>
    <br>
    <a href="http://theatregirl.net/vampire"><img src="vampirefanbuttonsmall.jpg"></a>
    <a href="https://mikh.net/elvira"><img src="elvirafanbuttonsmall.jpg"></a>
    <a href="https://10-31.net/fans/rhps/buttons.php"><img src="rockyhorrorfanbuttonsmall.png"></a>
    <a href="https://www.heartofsnow.net/alice"><img src="alicecooperfanbuttonsmall.jpg"></a>
    <br>
    <a href="https://fans.thislove.nu/mozilla"><img src="firefoxfanbuttonsmall.png"></a>
    <a href="http://fan.koukeisha.net/eq-fanlisting/"><img src="egyptqueenfanbuttonsmall.JPG"></a>
    <a href="http://lectersgirl.altervista.org/psycho/index.php"><img src="americanpsychofanbuttonsmall.png"></a>
    <a href="http://lectersgirl.altervista.org/sotl"><img src="silenceofthelambsfanbuttonsmall.png"></a>
    <br>
    <a href="https://fan.glast-heim.net/glados/"><img src="gladosfanlistbuttonsmall.png"></a>
    <br>
    <script src="https://transring.neocities.org/ring.js" data-widget="nb"></script>

    </center>
    </aside>
 </div><!--flex end ;3-->
      
    <footer id="footer">
        <div class="navbuttons"><a href="https://letterboxd.com/LupinusBicolor/"><img src="letterboxd.png" width="90" height="90"></a></div>
        <div class="navbuttons"><a href="https://lupinus-bicolor.tumblr.com/"><img src="tumblr.png" width="90" height="90"></a></div>
        <div class="navbuttons"><a href="https://twitter.com/Eitrad"><img src="twitter.png" width="90" height="90"></a></div>
        <p><div class="navbuttons"><a href="https://lupinus.neocities.org/directory"><img src="directorybutton.png" width="200" height="123"></a></div>
      <p>Construction began: August 26th, 2023</p>
    </footer>
                </div><!--container end :3c-->
      
  </body>
</html>




















# 💫 HELLO ITS ME HAFIZH SALAM KENAL💫:


---

# 💻 Tech Stack:
<p align="center">
  <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript" />
  <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white" alt="Adobe" />
  <img src="https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" />
  <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white" alt="MariaDB" />
  <img src="https://img.shields.io/badge/sql-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/expo-1C1E24?style=for-the-badge&logo=expo&logoColor=#D04A37" alt="Expo" />
  <img src="https://img.shields.io/badge/CodeIgniter-%23EF4223.svg?style=for-the-badge&logo=codeIgniter&logoColor=white" alt="CodeIgniter" />
  <img src="https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel" />
  <img src="https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure" />
  <img src="https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase" alt="Firebase" />
  <img src="https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React Native" />
</p>

# 📊 GitHub Stats:
<div id="header" align="center">
  <div id="header">
    <a href="https://github-readme-streak-stats.herokuapp.com/?user=HFZH-SC&theme=dark&hide_border=false">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=HFZH-SC&theme=dark&hide_border=false" alt="GitHub Streak" />
    </a>
    <br/>
    <a href="https://github-readme-stats.vercel.app/api/top-langs/?username=HFZH-SC&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=HFZH-SC&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact" alt="Top Languages" />
    </a>
  </div>
</div>

