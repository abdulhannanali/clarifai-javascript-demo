# Clarifai's JavaScript  Demo 

live at [hannanali.tech/clarifai-javascript-demo](https://hannanali.tech/clarifai-javascript-demo)

This demo is for the online talk I'll  give in combination with the Google Slides located [here](https://goo.gl/A1su2P). 

[![first slide of the presentation](https://cdn.rawgit.com/abdulhannanali/clarifai-javascript-demo/master/assets/clarifai.svg)](https://goo.gl/A1su2P)


## Stuff you need to know and have (clickbaity line?)
Hey, know what? What! This demo is based on JavaScript as is apparent from the name. Cos, rest assured this is the only real dev language. Okay, now let me Clarify (You mean Clarifai? LOL!) some stuff about the demo. AKA **Clarifaing Clarifai**.

It helps if you have a **basic JavaScript understanding** of the things discussed here and have some knowledge of the front end development scenario as well. Even if you don't know thse things you should definitely peek into the code and try out the demo, there are helpful comments along the code to help you. You shouldn't give up cos you don't know some thing, that's a lame excuse my friend! 😉😜😉

#### Clarifai Credentials
There are no credentials provided with the application, so supply your own, go to [developer.clarifai.com](https://developer.clarifai.com), signup, create a new application and copy paste the **client id** and **client secret** of this application in [`keys.js`](./js/keys.js). The demo can't successfully run without the credentials even if you got all the logic 👌👌👌🏎🏎🏎

You can read more about how to setup your application, get the credentials and about many possible integrations on [Clarifai's website](https://clarifai.com).

### How to get it in your system (i am talking about your computer, lol)

Well that's an easy one, you gotta have that [git](https://git-scm.com/download) installed and if you haven't installed it already, seriously, you need to stop being lazy. 

After installing [git](https://git-scm.com/download), copy pasta this line in the command line

```bash
git clone https://github.com/abdulhannanali/clarifai-javascript-demo
```

You can make changes to this demo now, start by looking into [`index.html`](index.html) file

### boiler plate code

There's some boiler plate to make the demo just work but tutorial's designed in a way so you don't need to understand all of it, to complete the demo. Just focus on the important parts marked as **TODO** in `index.js` and `keys.js` files. Especially, the parts where we are making a request to  the Clarifai API and interacting with the response received from it.

### Steps to complete this demo

1. Get the credentials from Clarifai's website and paste them into `keys.js` file
2. Get the tags from the Clarifai's website for the image url entered and supply it to the view logic `displayTags` to get the tags displayed. You need to access `/v1/tag` endpoint using SDK for this purpose.

**FINAL STEP**
Get the demo running somehow

**EXTRA STEP**
use the Clarifai SDK to find the major colors in an image using /v1/color endpoint. (View not implemented rn)

### Libraries and helpers used

##### [Clarifai's JavaScript SDK](https://github.com/Clarifai/clarifai-javascript)
The most notable and important part in this demo is Clarifai's JavaScript SDK which is really easy to use. You can check out the JavaScript's SDK repo [here](https://github.com/Clarifai/clarifai-javascript) and use it in the browser as well as in [nodejs](https://nodejs.org) along with any shiny tool such as [Webpack](https://webpack.io), [Browserify](https://browserify.io) or that new tool that hasn't even come out yet. 

You can check out SDK's for other languages in [Clarifai's Developer Guide](https://developer.clarifai.com/guide)

Other noticeable mentions that are not related with Clarifai are 

##### [jQuery](https://jquery.com)
##### [Bootstrap](https://getbootstrap.com)

Note: The dependencies aren't listed in [`package.json`](package.json)

### Complete demo solution

You can switch to the `complete` branch on github to check out the completed demo.

### Video Tutorial (Coming Soon on your nearest [YouTube](https://youtube.com)) 🎉🎉🎉🎉🎉

### Credits
**
### LICENSE

MIT License. See [LICENSE](LICENSE) for more details.