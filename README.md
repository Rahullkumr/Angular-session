# Angular-session
## Day 1 

session on Angular (Google)

why Angular?
1. software is just crud.
2. angular is a client side library. It has nothing to do with server
3. earlier, almost 80% of work was done on the server but today all presentation and basic operations are done
  on the browser. server need is reduced by 20%
  
 Why and why now, why not 10 years back?
 eg. of bmw.
 json = js object notation
 
 is there memory in browser?
 why is it happening today?
 because ecosystem was not there and today's clients ie mobile and laptops are capable enough to do such calculations.
 
 vvi What is node?
 node = Node.js is an open-source, cross-platform, JavaScript runtime environment that executes JavaScript code outside of a web browser(c++)
 run by:
 html = html parser
 css = css parser
 js = js engine in the browser (taken from V8 engine used by chrome an opensource engine)
 firefox engine is Spidermonkey.
 
 development stacks are: <br/>
 LAMP <br/>
 WAMP <br/>
 MEAN(popular because of ability to develop an app using only one language ie JS) <br/>
 MERN(popular because of ability to develop an app using only one language ie JS) <br/>
 
-------------------------------
Angular: component based framework. what is component based?
ENTIRE page is made up of independent component, like different components for header, footer, body and other.
These days we don't make a single page webpage.

mvvc = model = date, view

what is single page app?
eg Instagram, there is no next page concept.

why single page appln?
because developers wanted to keep you engaged on the same page. 

programmer's view point:
whenever u were switching to next page entire page was reloaded, but in one page only required data is reloaded.

# TypeScript (object oriented)
Angular vs AngularJS

browser doesn't understand TS.
TS = superset of JS
Since modern rowsers(as of now) do not understand TypeScript,  a TS compiler or transpiler is required to convert the TS code to regular JS code.

why only Angular not AngularJS?
because of inclusion of TS in the library. AngularJS is the first version.

JS and TS both are same for programmers, since every TS code is automatically converted into JS as browser dosn't understand TS.
--------------------------

## Let's do installation and run our first Angular app
Why we need node for angular developent?
node is needed for development of angular apps.

## Installation
1. Install node:
```diff
+ new way
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
sudo apt-get install -y nodejs

- old way
nvm install 16.10    (only 16.1 is working in codespace)
node --version
```

2. Install Angular: 
```
npm install -g @angular/cli     (-g is for global access)
ng version
```

## Create and run first Angular app
```
ng new demoapp1
cd demoapp1
ng serve -o
```
-----------
# Day2

1. run the angular app using ```ng serve -o```
   <p>
     The Path of running an angular app is: see pdf
   </p>
   
2. Create three modules (header, body and footer) and connect them with app-route
   ```
   ng g c header
   ng g c body
   ng g c footer
   ```
   
-------------------------
# Day 3

services will communicate to external world.

Why services?
components vs services?

```ng g s newfoldername``` for creating service

inject service class to the component

## Links provided
1. [Courses by Amrendra sir](https://akajay.in/learny/)

2. [Presentation link](https://docs.google.com/presentation/d/e/2PACX-1vSuakldhmsoxtx3SW_ZlukMImjHswgd6KdSRRbWOIXXE99oIE8ab4e1d-XJKfhtQJ9Tp0Oma-FMA_ad/pub?start=false&loop=false&delayms=3000&slide=id.g2296c731ee8_0_0)

3. [TODO APP step by step](https://docs.google.com/presentation/d/e/2PACX-1vSuakldhmsoxtx3SW_ZlukMImjHswgd6KdSRRbWOIXXE99oIE8ab4e1d-XJKfhtQJ9Tp0Oma-FMA_ad/pub?start=false&loop=false&delayms=3000&slide=id.g25258cab8bc_0_4)

4. [Angular Services and DI](https://docs.google.com/presentation/d/e/2PACX-1vTeWR2kHhqf6hk9JpMG8FcPIud-mPwgXB0xX9vxcp2QZse9NTruXo7fL8ZbTffvk4YXnLbNbIy3uZOq/pub?start=false&loop=false&delayms=3000&slide=id.p)

5. [Routing and SPA](https://docs.google.com/presentation/d/e/2PACX-1vS1Xe9LUMgyb79TdyhWlyN-BcKoP41U0j7OXTGk2dvUZIbIp953I0ETatXm9ZDZ2LSz_dBWAIhrXFCh/pub?start=false&loop=false&delayms=3000&slide=id.p)

## TODO APPS
1. [todoapp1.zip](https://drive.google.com/file/d/19E79COFjpaTTbtClsyWr3m_APFqyja-h/view?usp=sharing)
2. [todoapp2.zip](https://drive.google.com/file/d/1ZdGByeOah5NYTtDOY9JN2d7GK9HgAggs/view?usp=sharing)
3. [todoapp3.zip](https://drive.google.com/file/d/1wGt1slz911QFdePAzAQVeYNFXJXx4qRT/view?usp=sharing)
