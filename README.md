AR-playground
===

Vuforia
---

#### Install for Unity

1. Get a `Vuforia` dev account [here](https://developer.vuforia.com/user/register)
2. Download the [Unity SDK](https://developer.vuforia.com//downloads/sdk)
3. Double click it to import it into your *Unity* app

#### Adding the license
1. Create a new [license key](https://developer.vuforia.com/targetmanager/licenseManager/licenseListing)
2. Add the license key into the `AR Camera` object on any Unity scene

#### Creating a target database
Targets are stored in a special database-like vuforia file. 

1. Upload your target images on the Vuforia [target manager](https://developer.vuforia.com/targetmanager) and download the database file when finished.
2. Check the rating value on the image, higher is better
3. If the rating is bad clic on the image name for details and then on `Show features` at the bottom, this will show you what the machine is looking for.

Here is how to [think about target quality](https://developer.vuforia.com/library/articles/Solution/Image-Target-Enhancement-Grayscale-Histogram-Quality-Indicator).

#### Samples

Check out the [samples](https://developer.vuforia.com/downloads/samples) for a quick start.