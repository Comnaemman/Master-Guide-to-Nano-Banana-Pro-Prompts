# 📸 Product Photography - Part 1

> 15 prompts trong phần này

---

## 1. Train-ad style book advertisement image

*A detailed Japanese prompt for generating a 16:9 business-book-style advertisement featuring a specific book image with Japanese copy points.*

```
Please generate an advertisement image.

==== Ad specifications ===
- Aspect ratio: 16:9 (horizontal)
- Product to advertise: the book in the first attached image
- Main eye-catcher: place the book from the first attached image in a three-dimensional way
- Language: Japanese
- Taste: advertisement for a business book

# Text to include:
- Pre-head copy: 【New print run decided about one week after release】

Book “{argument name="book_title_en" default="Designing from Zero with AI"}” now on sale and doing well.

Amazon Best Seller Ranking
Ranked No.1 in commercial design sales (as of 10/15)
https://t.co/QxbYpfFVj6
```

---

## 2. Luxury minimalist product photography based on a reference image

*A prompt for generating high-end, minimalist commercial product photography in the style of luxury brand ads, using an uploaded reference image of the core product as the base.*

```
Using my uploaded reference image as the base, generate a minimalist, high-quality commercial still life photograph with the aesthetic of a luxury brand advertisement.

Preserve the general shape, proportions, and main color scheme of the core product in the reference so that it is instantly recognizable as the same product, but upgrade the overall texture and atmosphere of the image, making it look like an ad for a top-tier international fragrance, skincare item, or high-end electronic product.

Use a vertical 4:5 composition. The background should be a large area of clean, neutral negative space, such as soft off-white, cool gray, or light beige, creating a quiet, restrained, and expensive studio environment. Apart from the core product and a minimal number of necessary supports, do not add any extra decorations. No clutter, no elaborate scene setup—only keep very simple geometric supports (such as a plain white cube, a cylinder, or a thin transparent panel). The supports must be simple and low-profile, existing only to hold and accentuate the product.

Strongly emphasize the material details of the product, and let the lighting fully serve those materials:
Show frosted glass with a fine, soft matte texture, ceramics with a matte or slightly glazed feel, and polished metal with clean, sharp specular highlights. Liquids should have clearly visible viscosity and volume. Avoid any cheap plastic feel, complex patterns, or gaudy stickers; the overall material quality must feel cool, restrained, and luxurious.

Use professional studio lighting: mainly soft, diffused light from softboxes, plus precise rim light outlining the product’s shape. The contours should be crisp and layered, and the shadows should be soft and clean, with no noise or dirty shadow patches. You may use a near-macro viewpoint, moving in closer to the product to highlight materials and details, while preserving ample negative space around the frame so the product can "speak for itself" in the emptiness.

Keep the overall color scheme neutral and calm. The product’s own color can be slightly more saturated, making it the single visual focal point in the scene. Do not use exaggerated gradient backgrounds, flashy colored lighting, or e-commerce promo aesthetics. No large-price text, labels, or cartoon graphics.

The final result must be a high-resolution commercial key visual that looks ready for a magazine back cover or a high-end brand announcement poster: minimalist, quiet, high-end, with the core product confidently centered, surrounded by clean negative space and precisely controlled lighting.
```

---

## 3. Sora video prompt for Macho Meal McDonald’s commercial

*A short Sora prompt for generating an authentic-looking 1980s-style McDonald’s commercial featuring Macho Man Randy Savage promoting a Macho Meal happy meal.*

```
Authentic vintage 1980s commercial for the {argument name="product name in english" default="Macho Meal happy meal"} at {argument name="brand in english" default="McDonalds"} featuring {argument name="celebrity in english" default="Macho Man Randy Savage"}.
```

---

## 4. 3D paper cut light box illustration framework

*A detailed prompt template for generating dreamy, multi-layered 3D paper cut light box artworks, where you can swap in any theme and the model handles layers, lighting, color logic, and material realism.*

```
Generate an art photograph of a highly dreamy and three-dimensional 3D paper cut light box.  
The paper cut theme is: {argument name="theme" default="a deer in a forest under the moonlight"}.

Layering structure and composition:
Design the image as a real, physical paper cut light box composed of 5–7 layers of paper stacked together. Each layer must have its own depth of field and clear silhouette, and you should be able to see the thickness of the paper and the shadows between layers.

Core structure:
- The image should clearly present a multi-layered silhouette effect, with visible physical spacing between the paper layers.
- Overall composition is vertical 3:4, with the light box centered, leaving a bit of space at the edges, like a glowing art object placed on a table.

Depth layout:
- Foreground (layers 1–2): use dark, intricate silhouettes that form a frame around the edges of the image, with elements matching the current theme, such as branches and vines for forest themes, windows and arches for city or castle themes, or rocks and coral for underwater or fantasy themes.
- Midground (layers 3–4): this holds the core subject of the theme, slightly central in the composition and taking up the main visual weight. The subject’s silhouette must be complete and not overly blocked by the foreground.
- Background (layers 5–6): use more simplified, lower-contrast silhouettes to show distant environment and structures, adding depth to the scene.

Three-dimensionality:
- There must be obvious physical spacing and shadows between layers. Light should pass between the paper layers to create soft gradations of light and dark, emphasizing the paper thickness and 3D depth, so it looks like a real paper cut light box, not a flat illustration.

Light and atmosphere (backlighting):
Backlighting:
- The light source must come from the very back of the scene, shining forward through all the paper layers.
- Light passing through the cutouts in each layer should form soft volumetric light and gradually decreasing brightness and contrast from back to front.

Color gradients (auto-adapting to the theme):
If no specific color scheme is given, automatically choose a main palette and gradient that fit the theme, while keeping a soft, night-light-friendly look. For example, warm gold to cool blue-green for forest themes, teal to deep blue for underwater themes, icy blue to deep blue for winter scenes, amber to electric blue for cyber cities, candlelight gold to deep indigo for castles, or deep blue to purple with golden glows for space themes.
If the user clearly specifies a color direction or mood (such as “cool sci-fi” or “pink-blue dreamy”), follow that as the top priority while maintaining the soft backlit, soothing feeling of a night light.

Overall feel:
The image should feel quiet, healing, and storybook-like, like a softly glowing bedtime story lamp, not a noisy neon poster or infographic.

Materials and details:
Paper texture:
- Emphasize the reality of heavy art paper: fine texture, slight visible fibers, clean sharp cut edges with visible thickness, and light that diffuses softly through the paper like a real fibrous material, not plastic or metal.

Physical light box photography feel:
- Present the image as a photograph of a real light box, not a flat illustration or vector graphic. You can faintly show the light box frame (simple white or light wood) and a slightly blurred tabletop or environment.
- The lighting should feel natural, with real-lens depth of field: slightly blurred foreground, sharp midground subject, and soft background.

Detail decorations:
- You may add a modest amount of tiny floating elements between paper layers to enhance space, such as tiny glowing dots, dust motes, snowflakes, bubbles, or other small particles relevant to the theme. Their number must be restrained so they only enhance atmosphere and depth without cluttering or disrupting the silhouette structure.

Technical parameters: vertical 3:4 ratio, high-resolution output.
```

---

## 5. Cinematic close-up portrait with green eyes and knit sweater

*A detailed portrait prompt for a young woman with dark bangs and green eyes, lit by golden hour sunlight, in a 35mm Kodak Portra 400 aesthetic.*

```
Cinematic close-up portrait of a young woman with dark messy bangs and striking green eyes, resting her chin on a hand covered by a chunky grey knit wool sweater. Her face is pale with a heavy dusting of natural freckles and rosy cheeks, illuminated by a beam of warm golden-hour sunlight creating a dramatic chiaroscuro contrast. 35mm analog film photography style, f/1.8, bokeh, visible film grain, highly detailed skin texture, raw and emotional mood, Kodak Portra 400 aesthetic.
```

---

## 6. GoPro-style extreme sports selfie prompt

*An image prompt for a hyper-realistic wide-angle selfie of a man in an orange jumpsuit and helmet, with a dramatic mountainous landscape below, in an 8K extreme sports aesthetic.*

```
A hyper-realistic GoPro-style selfie of {argument name="subject in english" default="this handsome man"}, wearing an orange jumpsuit and helmet. Wide-angle view from above showing mountains, a shining lake, and green valleys below. Wind-blown {argument name="subject detail in english" default="hair or fur"}, joyful expression, detailed harness, vibrant lighting, 8K extreme-sports photography.
```

---

## 7. Golden hour rooftop portrait photography prompt

*A concise image prompt for a cinematic golden hour rooftop portrait with warm sunlight, wind in the hair, and a 35mm shallow depth of field look.*

```
A person standing on a city rooftop during golden hour, warm sunlight wrapping around their face, subtle lens flare, wind brushing their hair, shallow depth of field, 35mm photography vibe, natural skin texture.
```

---

## 8. Mirror selfie slideshow prompt for a stylish young woman

*A highly structured Nano Banana Pro slideshow prompt describing a young woman taking a mirror selfie with detailed styling, accessories, scene setup, and photography parameters, ideal for social-media-style vertical images.*

```
{
"subject": {
"description": "A young woman taking a mirror selfie, playfully biting the straw of an iced green drink",
"mirror_rules": "ignore mirror physics for text on clothing, display text forward and legible to viewer, no extra characters",
"age": "young adult",
"expression": "playful, nose scrunched, biting straw",
"hair": {
"color": {argument name="hair color" default="brown"},
"style": "long straight hair falling over shoulders"
},
"clothing": {
"top": {
"type": "ribbed knit cami top",
"color": {argument name="top color" default="white"},
"details": "cropped fit, thin straps, small dainty bow at neckline"
},
"bottom": {
"type": "denim jeans",
"color": "light wash blue",
"details": "relaxed fit, visible button fly"
}
},
"face": {
"preserve_original": true,
"makeup": "natural sunkissed look, glowing skin, nude glossy lips"
}
},
"accessories": {
"headwear": {
"type": "olive green baseball cap",
"details": "white NY logo embroidery, silver over-ear headphones worn over the cap"
},
"jewelry": {
"earrings": "large gold hoop earrings",
"necklace": "thin gold chain with cross pendant",
"wrist": "gold bangles and bracelets mixed",
"rings": "multiple gold rings"
},
"device": {
"type": "smartphone",
"details": "white case with pink floral pattern"
},
"prop": {
"type": "iced beverage",
"details": "plastic cup with iced matcha latte and green straw"
}
},
"photography": {
"camera_style": "smartphone mirror selfie aesthetic",
"angle": "eye-level mirror reflection",
"shot_type": "waist-up composition, subject positioned on the right side of the frame",
"aspect_ratio": "9:16 vertical",
"texture": "sharp focus, natural indoor lighting, social media realism, clean details"
},
"background": {
"setting": "bright casual bedroom",
"wall_color": "plain white",
"elements": [
"bed with white textured duvet",
"black woven shoulder bag lying on bed",
"leopard print throw pillow",
"distressed white vintage nightstand",
"modern bedside lamp with white shade"
],
"atmosphere": "casual lifestyle, cozy, spontaneous",
"lighting": "soft natural daylight"
}
}
```

---

## 9. Highly detailed 8K morning still life desk scene prompt

*An extremely detailed Nano Banana Pro prompt describing an 8K, golden-hour still life on an old wooden desk with food, notebook, wine spill, fountain pen, dust particles, and strong texture emphasis, including aspect ratio and stylization hints.*

```
Extreme close-up 8K morning still life on an old wooden desk bathed in golden sunlight through a dusty window:
- Half-eaten glazed {argument name="dessert in English" default="strawberry"} on a fine bone china plate, sticky syrup dripping
- Antique silver fork with food residue and tiny scratches
- Open Moleskine notebook with real leather cover, worn edges, and textured paper showing fibers
- Spilled red wine creating rings on the wood, absorbing into the grain
- Brass fountain pen leaking dark blue ink, pooling and reflecting light
- Crumpled silk handkerchief with subtle embroidery threads
- Dust particles floating in sunbeams, landing on a matte black camera body with micro-scratches
- Small puddle of water with floating dust and lens flare
- Tiny spiderweb strand catching light between objects
- Visible wood grain, knots, and 100-year-old cracks on the desk
Maximum texture detail, subsurface scattering, caustics, sharp specular highlights where needed, photorealistic, shot on medium format Phase One, --ar 4:5 --v 3 --stylize 350
```

---

## 10. Product photography prompt for a Tokyo pop-up atlas scene

*A richly detailed Nano Banana Pro prompt that stages a hardcover atlas with a paper pop-up miniature of Tokyo, specifying key landmarks, typography, lighting, and camera angle for high-end product-style imagery.*

```
An open hardcover atlas lies flat, with a precision pop-up miniature of {argument name="city" default="Tokyo"} rising from a laser-cut slit across the {argument name="map region" default="Asia"} map. Landmarks {argument name="landmark 1" default="Shibuya Crossing"}, {argument name="landmark 2" default="Tokyo Tower"}, and {argument name="landmark 3" default="Sensō-ji Temple"} interlock with folded paper struts. White 3D "{argument name="title text" default="TOKYO"}" emboss/deboss blends into the pop-up platforms. Softboxes at 45° and 120°, polarized reflections, dynamic low angle, razor-sharp fold edges.
```

---

## 11. System JSON prompt template for ultra-realistic iPhone-style AI influencers

*A long-form system-style prompt that defines a role, cognitive principles, visual aesthetic, and JSON schema for generating ultra-realistic mobile-photo influencer images with Nano Banana Pro.*

```
<role>
You are specialized in computational photography, specifically the optical characteristics of the {argument name="phone model" default="iPhone 16/17 Pro Max"} sensor system. You translate human concepts into mathematically precise image generation prompts.
</role>

<cognitive_framework>
<principle name="Context Hunger">
If the user provides a vague concept (for example, "{argument name="example vague concept" default="girl at a cafe"}"), you must explicitly invent the missing environmental, lighting, and styling details to ensure a complete image.
</principle>
<principle name="The iPhone Aesthetic">
All outputs must strictly simulate high-end mobile photography.
- Focal Lengths: {argument name="main focal length" default="24mm"} (Main), {argument name="ultra wide focal length" default="13mm"} (Ultra Wide), or {argument name="telephoto focal length" default="77mm"} (Telephoto).
- Characteristics: "Apple ProRAW" color science, sharp details (Deep Fusion), computational bokeh (Portrait Mode), and Smart HDR dynamic range.
- Avoid: anamorphic lens flares, exaggerated "cinema" bokeh, or vintage film grain (unless specified as a filter).
</principle>
<principle name="Imperfection is Realism">
To achieve "ultra-realism," you must inject terms describing unpolished reality: digital noise (not film grain), skin texture, slightly blown-out highlights (common in mobile), and natural "snapshot" framing.
</principle>
<principle name="JSON Precision">
Your output is a strict JSON object designed for programmatic use.
</principle>
</cognitive_framework>

<visual_analysis_reference>
The "Influencer Aesthetic" is defined by:
- Vibe: "Plandid" (planned candid), effortlessness, aspirational lifestyle.
- Lighting: natural window light, golden hour, or "flash photography" (hard flash) for night shots.
- Framing: vertical (9:16) native mobile aspect ratio, often selfies or point-of-view (POV).
</visual_analysis_reference>

<instructions>
1. Analyze the user's request for subject and mood.
2. Enrich the request using "iPhone Photography" constraints.
3. Format the output strictly as a JSON object with the following schema.
</instructions>

<json_schema>
{
  "meta_data": {
    "style": "iPhone Pro Max Photography",
    "aspect_ratio": "9:16"
  },
  "prompt_components": {
    "subject": "Detailed description of person, styling, pose (mirror selfie, 0.5x angle, etc.)",
    "environment": "Detailed background, location, social setting",
    "lighting": "Smart HDR lighting, natural source, or direct flash",
    "camera_gear": "iPhone 16 Pro Max, Main Camera 24mm f/1.78, or Ultra Wide 13mm",
    "processing": "Apple ProRAW, Deep Fusion, Shot on iPhone",
    "imperfections": "Digital noise, motion blur, authentic skin texture, screen reflection (if mirror)"
  },
  "full_prompt_string": "The combined, comma-separated string optimized for realistic mobile generation",
  "negative_prompt": "Standard negatives + 'professional camera, DSLR, bokeh balls, anamorphic, cinema lighting, studio lighting'"
}
</json_schema>

<task>
Await the user's description of the scene. Generate the JSON output immediately.
</task>
```

---

## 12. JSON Nano Banana Pro prompt for steampunk botanist workbench

*A rich JSON-based Nano Banana Pro prompt describing a hyper-realistic cinematic close-up of a Victorian steampunk botanist’s workbench with a glowing orchid, apothecary bottles, and specific camera and rendering parameters.*

```
{
  "prompt": "A hyper-realistic, cinematic close-up of a Victorian steampunk botanist's workbench. In the center, a heavy, oxidized brass-rimmed bell jar contains a levitating, bioluminescent orchid that glows with a pulsating electric blue light. The light from the flower illuminates dust motes dancing in the air. Next to the jar is a weathered leather field journal open to a page of complex anatomical sketches. A magnifying glass with a bone handle rests on the mahogany desk. In the background, shelves are filled with amber-colored apothecary bottles. The scene captures the texture of condensation on the glass, the grain of the wood, and the subsurface scattering of the flower petals. Shot on an 85mm macro lens, f/1.8 aperture, low-key lighting with high contrast.",
  "parameters": {
    "aspect_ratio": "21:9",
    "output_resolution": "4K",
    "guidance_scale": 8.0,
    "style_preset": "Cinematic",
    "seed": null
  },
  "advanced_config": {
    "identity_locking": false,
    "text_rendering_enabled": true,
    "required_text": [
      "SPECIMEN 004",
      "CHRONO FLORA"
    ]
  }
}
```

---

## 13. Structured JSON prompt for a stylish streetwear portrait of a young woman

*A detailed JSON-style image generation prompt for Nano Banana Pro that recreates a casual, stylish young woman in streetwear against an outdoor urban background, preserving likeness from a user photo.*

```
{
  "image_generation_prompt": {
    "subject": {
      "description": "{argument name="subject description" default="Young woman"}",
      "reference_basis": "{argument name="reference basis" default="User provided photo"}",
      "expression": "{argument name="expression" default="Casual and stylish"}"
    },
    "outfit": {
      "style": "{argument name="outfit style" default="Streetwear"}",
      "top": "{argument name="top" default="Black oversized t-shirt with a cool graphic design"}",
      "bottom": "{argument name="bottom" default="Light blue oversized wide-leg jeans"}",
      "footwear": "{argument name="footwear" default="White chunky sneakers"}",
      "accessories": "{argument name="accessories" default="Black wrist watch"}"
    },
    "pose_and_action": {
      "stance": "{argument name="stance" default="Standing"}",
      "hand_placement": "{argument name="hand placement" default="One hand in pocket"}",
      "holding_object": "{argument name="holding object" default="Iced drink in a plastic cup with a straw"}"
    },
    "environment": {
      "immediate_surroundings": "{argument name="immediate surroundings" default="Steel wire fence"}",
      "background_elements": [
        "{argument name="background element 1" default="Bright blue sky"}",
        "{argument name="background element 2" default="Bamboo trees"}",
        "{argument name="background element 3" default="Modern buildings"}"
      ]
    },
    "technical_details": {
      "medium": "{argument name="medium" default="Digital photography"}",
      "camera_angle": "{argument name="camera angle" default="Low angle / worm's-eye view"}",
      "lighting": "{argument name="lighting" default="Daylight, bright"}"
    }
  }
}
```

---

## 14. Natural Instagram-style car selfie prompt

*An English Nano Banana Pro prompt for generating a natural Instagram-style selfie of a young woman in a luxury car with detailed pose, clothing, lighting, and framing instructions.*

```
A natural Instagram-style selfie of {argument name="subject description" default="a young woman"} with {argument name="hair style and color" default="long, thick black wavy hair"}, sitting on the {argument name="seat color" default="beige leather seat"} of a {argument name="car type" default="luxury vehicle"}.

She is wearing {argument name="top" default="a white long-sleeve button-up shirt"}, tied in a knot below the chest to create a cropped look, paired with {argument name="bottoms" default="light-wash denim shorts"}. A small silver navel piercing is visible.

One arm is raised and resting behind her head in a relaxed pose, while the other hand rests naturally on her leg or thigh. Her body is slightly turned toward the camera, leaning back comfortably against the seat.

Her gaze is directed straight at the camera with a confident and sensual expression, natural soft makeup, and glossy lips.

Shot from eye level or a slightly high angle, as if taken with a selfie stick or a phone’s front camera. A medium to medium-close framing from the waist to the head, with the subject filling most of the frame.

Bright natural daylight pours in through the car windows, with lush green trees visible in the background. Soft, even lighting beautifully illuminates her face and body.

The warm beige leather interior creates a cozy and luxurious atmosphere. candid lifestyle photography aesthetic with an authentic social media selfie vibe.

Colors: bright, airy, and slightly warm-toned. The face and upper body are sharply in focus.
```

---

## 15. JSON-style Nano Banana Pro prompt for realistic faces

*A detailed JSON prompt template for Nano Banana Pro that generates a hyper-idealized Douyin-style night portrait of a girl, including framing, environment, lighting, camera settings, and negative constraints.*

```
{
"intent": "Generate a hyper-idealized, Douyin-style night portrait of the same girl shown in the reference image using direct flash photography, creating a sharp, high-contrast glow.",
"frame": {
"aspect_ratio": "16:9",
"composition": "Extreme close-up selfie framing focused tightly on the eyes and lips, forehead slightly cropped, gaze centered.",
"style_mode": "Flash photography, digital influencer aesthetic, soft-focus realism"
},
"subject": {
"identity": "the same girl from the reference image, with soft youthful features and understated elegance.",
"skin": "with a smooth, luminous finish reflecting the flash, creating a glassy glow with minimal texture.",
"hair": "loose, naturally wavy, catching specular highlights from the flash.",
"wardrobe": "Minimal visibility of a simple, understated top suited for a city night."
},
"environment": {
"location": "Nighttime {argument name="city type in English" default="Indian city"}.",
"weather": "Clear, calm night sky.",
"background": "Dark urban backdrop with blurred bokeh lights from buildings."
},
"lighting": {
"type": "Direct frontal phone flash or high-intensity screen light",
"quality": "Hard, flat lighting that eliminates deep shadows and creates a smooth two-dimensional glow",
"contrast": "Strong separation between the illuminated face and the dark city background",
"catchlight": "Small flash reflection in the center of the pupils"
},
"camera": {
"sensor_format": "Smartphone main camera simulation",
"lens": "24mm wide-angle lens that slightly exaggerates eye size and softens facial proportions",
"aperture_depth_of_field": "f/1.8–f/2.2, sharp on the eyes and lips, instant blur on the background and edges of the hair",
"focus": "Critical focus on the iris texture and eyelashes"
},
"negative": {
"content": "No wet hair, no snow, no rain, no masculine features, no visible pores, no heavy contour makeup, no sunglasses, no hands in frame.",
"style": "No dramatic shadows, no vintage tones, no painterly effects, no warm film look."
}
}
```

---

