# W-13682535 - Gov Cloud Premier+ - Washington State Liquor Control Board - Custom LWC inside the OmniScript is not rendering in production portal

Hopefully this bundle will allow you to repro the OmniScript issue with LWCs and scoped namespaces.  It contains all the necessary components and licenses, but your mileage may vary when it comes to deployment.

Steps:
1. Clone this repo
2. Create a scratch org
3. Deploy this code (hopefully it will work, may have to use --forceoverwrite)
4. Go to All Sites
5. Copy the site URL
6. In an incognito window, load the URL

Hopefully you will see an empty page, and if you enabled break-on-error, you will see the scoped namespace error.  Also, you will notice that the page is not running with LWS.