# graphics_resources

https://pcwalton.github.io/
https://raphlinus.github.io/
http://behdad.org/
http://graphics.stanford.edu/courses/cs348v-18-winter/

Ray Tracing in a Weekend 
http://www.realtimerendering.com/raytracing/Ray%20Tracing%20in%20a%20Weekend.pdf

“How to start learning Graphics Programming”
https://erkaman.github.io/posts/beginner_computer_graphics.html

General history of 2D rendering algorithms
https://hal.inria.fr/hal-01815193/document (see section titled Rendering)
is there a way to get a recording of this?

2D graphics API design considerations
https://raphlinus.github.io/rust/graphics/2018/10/11/2d-graphics.html
https://nical.github.io/posts/rust-2d-graphics-01.html
https://www.reddit.com/r/rust/comments/9nhhh8/a_crate_i_want_2d_graphics/

Design considerations when  using gfx-hal (or something similar) to support a 2D graphics API
https://nical.github.io/posts/rust-2d-graphics-01.html

Vulkan tutorials
https://vulkan-tutorial.com/
https://software.intel.com/en-us/articles/api-without-secrets-introduction-to-vulkan-part-1
https://vulkan.lunarg.com/doc/sdk/1.0.26.0/linux/tutorial.html
https://developer.nvidia.com/vulkan-shader-resource-binding

Gfx-rs tutorials
Following vulkan-tutorial.com: https://github.com/grovesNL/gfx-hal-tutorial
https://github.com/Lokathor/learn-gfx-hal


Trapezoidal pixel coverage algorithm
https://medium.com/@raphlinus/inside-the-fastest-font-renderer-in-the-world-75ae5270c445
https://www.tdcommons.org/cgi/viewcontent.cgi?article=1580&context=dpubs_series (also by Allan MacKinnon of spinel / skc fame)
https://nothings.org/gamedev/rasterize/

Approaches to path/font rendering on GPU
http://w3.impa.br/~diego/projects/GanEtAl14/ Ganacim 2014: Massively-Parallel Vector Graphics
blend2d.com - HN discussion
https://github.com/memononen/nanovg
Paper on slug rendering library: http://jcgt.org/published/0006/02/02/
https://medium.com/@evanwallace/easy-scalable-text-rendering-on-the-gpu-c3f4d782c5ac
(Pathfinder 1) https://pcwalton.github.io/2017/02/14/pathfinder.html
https://aras-p.info/blog/2017/02/15/Font-Rendering-is-Getting-Interesting/
http://kunzhou.net/zjugaps/pathrendering/ Li 2016: Efficient GPU Path Rendering Using Scanline Rasterization

GPU compute resources
https://web.archive.org/web/20160512140551/http://www.pixel.io:80/blog
https://github.com/google/skia/tree/81abc43e6f0b1a789e1bf116820c8ede68d778ab/src/compute/skc
https://www.youtube.com/watch?v=ZTq8wKnVUZ8 Linux.conf.au 2019 talk on open source compute
https://www.youtube.com/watch?v=T5Va6hSGx44 talk on spirv-cross

Shaders
https://thebookofshaders.com - excellent approachable introduction
https://www.shadertoy.com/ - Good tool to get started
https://tutsplus.com/tutorials/search/shadertoy
https://gist.github.com/JBlackCat/65c976151b53b3db8dcc849176a04161
https://news.ycombinator.com/item?id=16457379
https://www.ronja-tutorials.com/2018/11/10/2d-sdf-basics.html

Signed distance field text rendering
https://github.com/behdad/glyphy
https://github.com/Chlumsky/msdfgen

Antialiasing / font rendering
https://web.archive.org/web/20190407075053/http://www.antigrain.com/
https://web.archive.org/web/20180921225907/http://antigrain.com/research/font_rasterization/index.html#FONT_RASTERIZATION
http://rastertragedy.com/ - Great reading and suitable for beginners
https://blog.johnnovak.net/2016/09/21/what-every-coder-should-know-about-gamma/ - Also great for beginners

Instruction synchronization using modern graphics APIs
https://www.khronos.org/assets/uploads/developers/library/2016-vulkan-devday-uk/7-Keeping-your-GPU-fed.pdf
https://github.com/KhronosGroup/Vulkan-Docs/wiki/Synchronization-Examples
https://gpuopen.com/performance-tweets-series-barriers-fences-synchronization/
https://github.com/gwihlidal/vk-sync-rs/blob/c8c16db27b7b2b31b1748afcdd9cd08f93d2e173/src/lib.rs#L1

