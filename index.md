---

layout: sc5

style: |

    .slide h3 {
        font-size: 30px;
        font-weight: bold;
    }

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
    img.cover {
      width: 100%;
    }
---

# Pattern libraries through trial and error {#Cover}

<div class="main-logo__wrapper">
    <object class="main-logo" data="themes/sc5/images/logo.min.svg#white" type="image/svg+xml"></object>
</div>

*Brought to you by&nbsp;[Varya&nbsp;Stepanova](http://varya.me/) from [SC5](http://sc5.io), 26th October 2016*
{: .credits }

<!--
This story sums up my experience in developing modular web solutions and pattern libraries. In fact, I am now doing
exactly the same what I was doing 8 years ago. But how I do it is very different from how I did it back then. And the
reasoning of choices for methods and tools to apply goes directly from grasping human nature, no less. BEM, living
styleguides and visual regression tests are involved.
-->

<style>

#Cover {
  background-image:url('pictures/fantacy-library.jpg');
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

## Bonjour!
{: .shout }

## Me
{: .no-title }

### Now
Senior Software Specialist at <b>SC5</b> (Helsinki)

### Before
<b>TMG</b> (Amsterdam, the Netherlands); <b>Yandex</b>&nbsp;(Moscow,&nbsp;Russia)

### Area of expertise
Components on the web: libraries, SGDD, BEM. Techs: CSS, JavaScript, etc

## Dreams

Developing is good but I want something more.

Do smth for not doing anything.

## Blocks

I want to develop interfaces like walls with blocks.

## Yandex
{: .shout }

## Yandex
{: .cover .no-title }

![](pictures/yandex.png){: .cover }

## Yandex services
{: .cover .no-title }

![](pictures/yandex-all.png){: .cover }

## The blocks
{: #the-blocks }

![](pictures/yandex-blocks.png){: .cover }

<style>
#the-blocks h2 {
  margin-bottom: 0.25em;
}
</style>

## Lego
{: #lego }

![](pictures/yandex-library.png){: .cover }

<style>
#lego h2 {
  margin-bottom: 0;
}
</style>

## Version upgrade

Twitter bootstrap problem

## Templates

Data layer, template layer

## BEM

## BEM eco system

Possible to make a styleguide but complex

## Good our of it

* component file structure
* documenttaion near code

## Going over the test

Работа над ошибками


## Living styleguides

## KSS

Documentation in the code

## SC5 Styleguide

## Visual tests

More slides

## Client projects

## Open source

* Start in open source
* Feature is more than code

## Around the globe
{: .shout }

## Conferences
{: .no-title }

<object type="image/svg+xml"
  data="pictures/World-movie.svg" class="world"></object>

<style>
#conferences .world {
  width: 100%;
}
</style>

## Thank you
{: .thanks }

Varya Stepanova<br/>
[@varya_en](https://twitter.com/varya_en){: .twitter }

### Slides: [varya.me/dotcss-2016](http://varya.me/dotcss-2016/)

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
