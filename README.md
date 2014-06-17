mraid-html5
===========
mraid-html5 is an example repository to ease mraid html5 ads integration with LiquidM SDK.

Before you upload your ad into LiquidM platform you need to:

* include all files from src directory;
* adjust config.json;
* pack everything into zip format.

Please check examples directory to see 3 different working implementations.

## Repository content

#### examples/

Directory contains three example ads in raw and zip format:

* one_part_expand_mraid - an example one part expandable ad;
* resize_mraid - an example use of resize method;
* two_part_mraid - an example two part expandable ad.

We also provide you with 3 html helper files. You can use them to see how example ads work and also to test your integration.

#### src/

Directory contains assets you need to include into mraid zip package:

* mraid.js - mraid library, as described in mraid specification it needs to be included in every ad part;
* prelude.js - mraid controller, handles instructions send by mraid.js and perform them on the ad container and the ad. This file will be send by LiquidM servers and in included in the target website, where your ad will be displayed.
* container_template - container template file, with which LiquidM servers wrap your ad;
* config.json - you need to adjust it before you included in the mraid zip package.

## Live examples

You can see this examples in action using following url:

http://liquidm.github.io/mraid-html5/

## More informations

For more informations we recommend you to read Mobile Rich-media Ad Interface Definitions http://www.iab.net/media/file/IAB_MRAID_v2_FINAL.pdf or contact LiquidM.
