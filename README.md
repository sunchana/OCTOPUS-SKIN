 This simulation models the living skin of a cephalopod — squid, octopus, cuttlefish — using two layered computational systems running simultaneously in the browser.

The background texture is driven by a Gray-Scott reaction-diffusion system — a pair of virtual chemicals (an activator and an inhibitor) that diffuse and react across a grid, spontaneously forming the organic spotted and labyrinthine patterns seen in animal pigmentation. The same mathematics underlies the spots on a leopard, the stripes on a zebrafish, and the patterns on real cephalopod skin.

On top of this, an excitable medium — modelled after the behaviour of biological nerve tissue — propagates travelling waves across the skin. Each point on the grid can fire, then enter a refractory period before it can fire again. This naturally produces circular wavefronts that annihilate on collision, closely matching how chromatophore expansion signals actually spread across a squid's mantle.

Three cell types are rendered: large dark chromatophores (pigment-filled sacs that expand under muscular control), smaller yellow-green xanthophores, and tiny scattered erythrophores that provide the magenta-red punctuation visible in close-up photography of real squid skin. All cells are invisible at rest and only appear as an excitation wave passes through them.

Technique
Gray-Scott RD + excitable medium, Canvas 2D, pure JS

Interaction
Click or drag to inject a wavefront; sliders control speed, density, and expansion

Reference
Close-up photography of Loligo vulgaris (European squid) skin

Made with
Claude Sonnet 4.6 — iterative creative coding session
