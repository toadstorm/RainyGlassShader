# RainyGlassShader

![rain sample](https://www.toadstorm.com/blog/wp-content/uploads/2021/02/raindrops_sphere_2.gif)

A Unity built-in shader for a plausible rain-on-glass effect. Has high-end and mobile variants. As seen in ["The Conservatory"](https://vrchat.com/home/launch?worldId=wrld_2e37b570-7f57-46d5-9ef5-e33d1326c70b) on VRChat.

This shader was constructed using Amplify Shader Editor. It uses a bit of math to animate the two included textures. The shader is fully parameterized so it can create rainy looks of varying intensities.

The main shader uses a grabpass for the fake refraction effect. On Android, please use the mobile shader that doesn't use a grabpass. It's highly recommended that you edit this shader or any other grabpass shaders in your scene to ensure that they're named identically wherever possible to avoid performance loss.

For information on how this shader was constructed, see this article: [https://www.toadstorm.com/blog/?p=742](https://www.toadstorm.com/blog/?p=742)
