mraid-html5
===========
mraid-html5 is an example repository to ease mraid html5 ads integration using LiquidM SDK.

## Repository content

Currently repository contains two directories:

#### examples/

Directory contains 3 working integrations

#### src/

Directory contains assets necessary to test your integration locally:

* mraid.js - mraid library, as described in mraid specification it needs to be included in every ad parts
* prelude.js - mraid controller, handles instructions send by mraid.js and perform them on the ad container and the ad
* container_template.erb - container template file, with which LiquidM ad servers wrap your ad.

## More informations

For more informations we recommend you to read Mobile Rich-media Ad Interface Definitions http://www.iab.net/media/file/IAB_MRAID_v2_FINAL.pdf or contact LiquidM (support@liquidm.com)
