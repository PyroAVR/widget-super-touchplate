# com-chilipeppr-widget-super-touchplate
This widget helps you use a touch plate to find the origin on your workpiece.



## ChiliPeppr Widget / Super Touch Plate

All ChiliPeppr widgets/elements are defined using cpdefine() which is a method
that mimics require.js. Each defined object must have a unique ID so it does
not conflict with other ChiliPeppr widgets.

| Item                  | Value           |
| -------------         | ------------- | 
| ID                    | com-chilipeppr-widget-super-touchplate |
| Name                  | Widget / Super Touch Plate |
| Description           | This widget helps you use a touch plate to find the origin on your workpiece. |
| chilipeppr.load() URL | http://raw.githubusercontent.com/PyroAVR/widget-super-touchplate/master/auto-generated-widget.html |
| Edit URL              | http://ide.c9.io/pyroavr/widget-super-touchplate |
| Github URL            | http://github.com/PyroAVR/widget-super-touchplate |
| Test URL              | https://preview.c9users.io/pyroavr/widget-super-touchplate/widget.html |

## Example Code for chilipeppr.load() Statement

You can use the code below as a starting point for instantiating this widget 
inside a workspace or from another widget. The key is that you need to load 
your widget inlined into a div so the DOM can parse your HTML, CSS, and 
Javascript. Then you use cprequire() to find your widget's Javascript and get 
back the instance of it.

```javascript
chilipeppr.load(
  "#myDivWidgetInsertedInto",
  "http://raw.githubusercontent.com/PyroAVR/widget-super-touchplate/master/auto-generated-widget.html",
  function() {
    // Callback after widget loaded into #myDivWidgetInsertedInto
    cprequire(
      ["inline:com-chilipeppr-widget-super-touchplate"], // the id you gave your widget
      function(mywidget) {
        // Callback that is passed reference to your newly loaded widget
        console.log("My widget just got loaded.", mywidget);
        mywidget.init();
      }
    );
  }
);

```

## Publish

This widget/element publishes the following signals. These signals are owned by this widget/element and are published to all objects inside the ChiliPeppr environment that listen to them via the 
chilipeppr.subscribe(signal, callback) method. 
To better understand how ChiliPeppr's subscribe() method works see amplify.js's documentation at http://amplifyjs.com/api/pubsub/

  <table id="com-chilipeppr-elem-pubsubviewer-pub" class="table table-bordered table-striped">
      <thead>
          <tr>
              <th style="">Signal</th>
              <th style="">Description</th>
          </tr>
      </thead>
      <tbody>
      <tr><td colspan="2">(No signals defined in this widget/element)</td></tr>    
      </tbody>
  </table>

## Subscribe

This widget/element subscribes to the following signals. These signals are owned by this widget/element. Other objects inside the ChiliPeppr environment can publish to these signals via the chilipeppr.publish(signal, data) method. 
To better understand how ChiliPeppr's publish() method works see amplify.js's documentation at http://amplifyjs.com/api/pubsub/

  <table id="com-chilipeppr-elem-pubsubviewer-sub" class="table table-bordered table-striped">
      <thead>
          <tr>
              <th style="">Signal</th>
              <th style="">Description</th>
          </tr>
      </thead>
      <tbody>
      <tr><td colspan="2">(No signals defined in this widget/element)</td></tr>    
      </tbody>
  </table>

## Foreign Publish

This widget/element publishes to the following signals that are owned by other objects. 
To better understand how ChiliPeppr's subscribe() method works see amplify.js's documentation at http://amplifyjs.com/api/pubsub/

  <table id="com-chilipeppr-elem-pubsubviewer-foreignpub" class="table table-bordered table-striped">
      <thead>
          <tr>
              <th style="">Signal</th>
              <th style="">Description</th>
          </tr>
      </thead>
      <tbody>
      <tr><td colspan="2">(No signals defined in this widget/element)</td></tr>    
      </tbody>
  </table>

## Foreign Subscribe

This widget/element publishes to the following signals that are owned by other objects.
To better understand how ChiliPeppr's publish() method works see amplify.js's documentation at http://amplifyjs.com/api/pubsub/

  <table id="com-chilipeppr-elem-pubsubviewer-foreignsub" class="table table-bordered table-striped">
      <thead>
          <tr>
              <th style="">Signal</th>
              <th style="">Description</th>
          </tr>
      </thead>
      <tbody>
      <tr><td colspan="2">(No signals defined in this widget/element)</td></tr>    
      </tbody>
  </table>

## Methods / Properties

The table below shows, in order, the methods and properties inside the widget/element.

  <table id="com-chilipeppr-elem-methodsprops" class="table table-bordered table-striped">
      <thead>
          <tr>
              <th style="">Method / Property</th>
              <th>Type</th>
              <th style="">Description</th>
          </tr>
      </thead>
      <tbody>
      <tr valign="top"><td>id</td><td>string</td><td>"com-chilipeppr-widget-super-touchplate"</td></tr><tr valign="top"><td>url</td><td>string</td><td>"http://raw.githubusercontent.com/PyroAVR/widget-super-touchplate/master/auto-generated-widget.html"</td></tr><tr valign="top"><td>fiddleurl</td><td>string</td><td>"http://ide.c9.io/pyroavr/widget-super-touchplate"</td></tr><tr valign="top"><td>githuburl</td><td>string</td><td>"http://github.com/PyroAVR/widget-super-touchplate"</td></tr><tr valign="top"><td>testurl</td><td>string</td><td>"http://widget-super-touchplate-pyroavr.c9users.io/widget.html"</td></tr><tr valign="top"><td>name</td><td>string</td><td>"Widget / Super Touch Plate"</td></tr><tr valign="top"><td>desc</td><td>string</td><td>"This widget helps you use a touch plate to find the origin on your workpiece."</td></tr><tr valign="top"><td>subscribe</td><td>object</td><td>Please see docs above.</td></tr><tr valign="top"><td>foreignPublish</td><td>object</td><td>Please see docs above.</td></tr><tr valign="top"><td>foreignSubscribe</td><td>object</td><td>Please see docs above.</td></tr><tr valign="top"><td>isInitted</td><td>boolean</td><td></td></tr><tr valign="top"><td>init</td><td>function</td><td>function () </td></tr><tr valign="top"><td>audio</td><td>object</td><td></td></tr><tr valign="top"><td>loader</td><td>object</td><td></td></tr><tr valign="top"><td>camera</td><td>object</td><td></td></tr><tr valign="top"><td>scene</td><td>object</td><td></td></tr><tr valign="top"><td>renderer</td><td>object</td><td></td></tr><tr valign="top"><td>scripts</td><td>object</td><td></td></tr><tr valign="top"><td>dom</td><td>undefined</td><td></td></tr><tr valign="top"><td>width</td><td>number</td><td></td></tr><tr valign="top"><td>height</td><td>number</td><td></td></tr><tr valign="top"><td>touchplate</td><td>object</td><td></td></tr><tr valign="top"><td>spindle</td><td>object</td><td></td></tr><tr valign="top"><td>light</td><td>object</td><td></td></tr><tr valign="top"><td>init3d</td><td>function</td><td>function () </td></tr><tr valign="top"><td>introAnim</td><td>function</td><td>function () </td></tr><tr valign="top"><td>deltax</td><td>object</td><td></td></tr><tr valign="top"><td>deltay</td><td>object</td><td></td></tr><tr valign="top"><td>deltafov</td><td>object</td><td></td></tr><tr valign="top"><td>curV</td><td>object</td><td></td></tr><tr valign="top"><td>curFov</td><td>object</td><td></td></tr><tr valign="top"><td>curStep</td><td>object</td><td></td></tr><tr valign="top"><td>steps</td><td>object</td><td></td></tr><tr valign="top"><td>introAnimStep</td><td>function</td><td>function () </td></tr><tr valign="top"><td>gcodeCtr</td><td>number</td><td></td></tr><tr valign="top"><td>isRunning</td><td>boolean</td><td></td></tr><tr valign="top"><td>runZAxis</td><td>function</td><td>function () </td></tr><tr valign="top"><td>runXAxis</td><td>function</td><td>function () </td></tr><tr valign="top"><td>runYAxis</td><td>function</td><td>function () </td></tr><tr valign="top"><td>onRun</td><td>function</td><td>function (evt) </td></tr><tr valign="top"><td>watchForProbeStart</td><td>function</td><td>function () </td></tr><tr valign="top"><td>watchForProbeEnd</td><td>function</td><td>function () </td></tr><tr valign="top"><td>onRecvLineForProbe</td><td>function</td><td>function (data) </td></tr><tr valign="top"><td>onAfterProbeDone</td><td>function</td><td>function (probeData) </td></tr><tr valign="top"><td>isAnimInfiniteRunning</td><td>boolean</td><td></td></tr><tr valign="top"><td>animInfiniteCallback</td><td>object</td><td></td></tr><tr valign="top"><td>animInfiniteStart</td><td>function</td><td>function () </td></tr><tr valign="top"><td>animInfiniteEnd</td><td>function</td><td>function () </td></tr><tr valign="top"><td>animInfinite</td><td>function</td><td>function () </td></tr><tr valign="top"><td>onresize</td><td>function</td><td>function () </td></tr><tr valign="top"><td>load</td><td>function</td><td>function (json) </td></tr><tr valign="top"><td>setCamera</td><td>function</td><td>function (value) </td></tr><tr valign="top"><td>setSize</td><td>function</td><td>function (width, height) </td></tr><tr valign="top"><td>dispatch</td><td>function</td><td>function (array, event) </td></tr><tr valign="top"><td>request</td><td>object</td><td></td></tr><tr valign="top"><td>animate</td><td>function</td><td>function (time) </td></tr><tr valign="top"><td>isHidden</td><td>boolean</td><td></td></tr><tr valign="top"><td>unactivateWidget</td><td>function</td><td>function () </td></tr><tr valign="top"><td>activateWidget</td><td>function</td><td>function () </td></tr><tr valign="top"><td>isVidLoaded</td><td>boolean</td><td></td></tr><tr valign="top"><td>lazyLoadTutorial</td><td>function</td><td>function () </td></tr><tr valign="top"><td>options</td><td>object</td><td></td></tr><tr valign="top"><td>setupUiFromLocalStorage</td><td>function</td><td>function () </td></tr><tr valign="top"><td>saveOptionsLocalStorage</td><td>function</td><td>function () </td></tr><tr valign="top"><td>showBody</td><td>function</td><td>function (evt) </td></tr><tr valign="top"><td>hideBody</td><td>function</td><td>function (evt) </td></tr><tr valign="top"><td>btnSetup</td><td>function</td><td>function () </td></tr><tr valign="top"><td>statusEl</td><td>object</td><td></td></tr><tr valign="top"><td>status</td><td>function</td><td>function (txt) </td></tr><tr valign="top"><td>forkSetup</td><td>function</td><td>function () </td></tr><tr valign="top"><td>threeObj</td><td>object</td><td></td></tr>
      </tbody>
  </table>


## About ChiliPeppr

[ChiliPeppr](http://chilipeppr.com) is a hardware fiddle, meaning it is a 
website that lets you easily
create a workspace to fiddle with your hardware from software. ChiliPeppr provides
a [Serial Port JSON Server](https://github.com/johnlauer/serial-port-json-server) 
that you run locally on your computer, or remotely on another computer, to connect to 
the serial port of your hardware like an Arduino or other microcontroller.

You then create a workspace at ChiliPeppr.com that connects to your hardware 
by starting from scratch or forking somebody else's
workspace that is close to what you are after. Then you write widgets in
Javascript that interact with your hardware by forking the base template 
widget or forking another widget that
is similar to what you are trying to build.

ChiliPeppr is massively capable such that the workspaces for 
[TinyG](http://chilipeppr.com/tinyg) and [Grbl](http://chilipeppr.com/grbl) CNC 
controllers have become full-fledged CNC machine management software used by
tens of thousands.

ChiliPeppr has inspired many people in the hardware/software world to use the
browser and Javascript as the foundation for interacting with hardware. The
Arduino team in Italy caught wind of ChiliPeppr and now
ChiliPeppr's Serial Port JSON Server is the basis for the 
[Arduino's new web IDE](https://create.arduino.cc/). If the Arduino team is excited about building on top
of ChiliPeppr, what
will you build on top of it?

