# Burnout Upscaling Project
A community project meant to upscale, restore or remake Burnout Dominator's textures with modern and future high resolution standards in mind.
The project uses ESRGAN (mainly the 4xUltraSharp and Remacri models for textures and 4xAnimeSharp and 8xNMKD Typescale 175k for UI and Fonts respectively, using Nero AI Upscaler as support when fit), Vectorization (Mainly for simple shapes -UI- that AI upscaling would overwork/deform) and recreation/restoration as last resource.

# BUP Upscaling Standard
The BUP US is a set of working rules created for the contributors to follow to achieve consistency.

  *Target Sizes (using smaller side as reference ONLY for 2:1 textures)
* Avoid hitting 8K.
* 2K for secondary objects.
* 4K for cars, big UI elements and big atlases.
* 512 for small icons/sprites.
* 1024 for big icons/sprites.

* Upscale Ratio target for PSP is 16x (basically 2 x4 passes, for UI you can Lanczos downscale the output to 50% and apply more passes to achieve bigger clarity [recommended to test both]).
* 64x64 In-Game textures (not UI) are more fit for recreation but upscales are welcome if the results are decent. Most UI Elements are fit for upscaling even at 32x32 and definitely at 64x64.
* Contrast, tonality, brightness and other image parameters should not be modified unless absolutely necessary.
* Event/Series/Vehicle preview images should be 2048x1024 and treated with the 1x DeJPEG Fatality PLUSUltra 200000G filter as final pass.
* Don't upscale or upload mip-maps.

# Notes
* 4xUltraSharp is appropriate for cleaner textures, does a pretty good job with complex ones as well.
* Remacri is appropriate for complex textures, pretty good for clean textures as well.
* Nero AI Upscaler (Standard mode) is appropriate for environmental/crisp/detailed and maybe complex textures, generates lots of patterns giving a realistic feeling to textures. Doesn't work well with poorly defined textures and tends to add JPEG-like noise. Can give stunning results or very poor ones.

# How to Contribute
Prerequisites:
* Download the texture pack and install it on your PC.
* If for any reason you delete the textures.ini, you need to create one and set the hash to xxh64 and enable ignoreAddress, otherwise your filenames will be wrong and the submission will be rejected until named properly.
* Dump textures little by little using savestates and keeping the texture pack enabled at all times to avoid redundant work.

Requirements:
* Adhere to the BUP Upscaling Standard.
* Upload only correctly named files.
