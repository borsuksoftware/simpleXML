# simpleXML
simpleXML is a jQuery plugin which can be used to dynamically render XML in a visually appealing way within a website.

## Structure
There are 3 parts to the plugin:
* javascript
* css
* image file

To use the plugin, simply include the above 3 files into your project (note that based off where the image file is put on your site, it might be necessary to update the CSS file accordingly) and ensure that the javascript file is included after jQuery has been added (pretty much any version of jQuery will do).

To use the plugin, then the following can be used:

  $(“#simpleUseCase”).empty().simpleXML({ xmlString: xml });
  
## Options
The following options are available

| Parameter | Description |
| --- | --- |
| xml | The XML object to be shown |
| xmlString | The XML string to be shown (will be parsed into the above XML format) |
| collapsedText | The text shown when the node is collapsed (defaults to '...') |

Note that at least one of xml or xmlString must be supplied.

## FAQs
#### Can I use in this my project etc.?
Yes. Please do. The only thing that we ask (and you don't have to do so) is that you let us know if it's proved useful for you. That motivates us to keep providing components.

#### I want to update the look and feel of the expanders etc. How do I do so?
All of this is controlled by standard css and the image file. Make any changes there and they'll be reflected. 

#### I have a suggestion, what do I do?
Contact us @ simpleXML@borsuksoftware.co.uk or create an issue above.
