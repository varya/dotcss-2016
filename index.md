---

layout: sc5

style: |

    #Cover .main-logo__wrapper {
        width: 100%;
        text-align: center;
    }
    #Cover object.main-logo {
        z-index: 5;
        position: static;
        width: 200px;
        margin: 35px 50px;
    }

    #Cover h2 {
        margin:80px 0 0;
        color:#FFF;
        text-align:center;
        font-size:60px;
        line-height: 1.5em;
        }
    #Cover p {
        margin:10px 0 0;
        text-align:center;
        color:#FFF;
        font-size:20px;
        }
        #Cover p a {
            color:#FFF;
            }
    #Picture h2 {
        color:#FFF;
        }
    #SeeMore h2 {
        font-size:100px
        }
    #SeeMore img {
        width:0.72em;
        height:0.72em;
        }
    body {
      font-family: 'PT Sans', sans-serif;
      font-size: 24px;
    }
    .slide h2 {
      font-size: 52px; /* for cyrilic */
    }
    .slide>div {
      font-size: 32px;
      padding-top: 50px;
    }
    .slide ol li,
    .slide ul li {
      text-indent: -1em;
    }
    .slide pre {
        background-color: #efefef;
        padding: 15px;
    }
    .slide pre code {
        line-height: 1.5em;
        font-size: 26px;
    }
    .slide pre code:before {
        content: "";
    }
    .shout.slide {
      background-color: #ef4942;
    }
    .shout.slide h2 {
      color: #fff;
    }
    .no-title h2 {
      display: none;
    }
---

# Title {#Cover}

<div class="main-logo__wrapper">
    <object class="main-logo" data="themes/sc5/images/logo.min.svg#white" type="image/svg+xml"></object>
</div>

*Brought to you by&nbsp;[Varya&nbsp;Stepanova](http://varya.me/) from [SC5](http://sc5.io), 26th October 2016*
{: .credits }

<style>

#Cover {
  background-image:url('pictures/cover.jpg');
  background-size: cover;
  background-position: 0 0, center;
}

#Cover h2 {
  text-shadow: 7px 3px 7px rgba(0,0,0,0.5);
  font-size: 48px;
  margin-top: 220px;
}

#Cover .credits {
    margin-top: 105px;
}
#Cover .credits,
#Cover .credits a {
  font-size: 20px;
  color: #fff;
  font-family: 'Lora',sans-serif;
  font-style: italic;
  text-shadow:
    3px 2px 3px rgba(0,0,0,0.5),
    -3px 2px 3px rgba(0,0,0,0.5),
    10px -2px 17px rgba(0,0,0,0.9);
}
</style>

## Chapter
{: .shout }

## Slide

Hello there!

## Thank you
{: .thanks }

Varya Stepanova<br/>
[@varya_en](https://twitter.com/varya_en){: .twitter }

### The tool: [github.com/sc5/sc5-styleguide-visualtest](https://github.com/SC5/sc5-styleguide-visualtest)

### Working code: [github.com/varya/varya.github.com](http://git.io/visual-tests-demo)

### Slides: [varya.me/turku-frontend-2016](http://varya.me/turku-frontend-2016/)

<style>
.thanks h3 {
  font-size: 38px;
  margin-bottom: 0.5em;
}
.thanks .twitter
{
  text-decoration: none;
  color: currentColor;
  background: none;
}
.thanks .twitter::before
{
  content: "";
  display: inline-block;
  width: 1.5em;
  height: 1.5em;
  background-image:url('pictures/twitter-logo.png');
  background-size: cover;
  margin-right: 0.5em;
  margin-bottom: -0.5em;
}
</style>
