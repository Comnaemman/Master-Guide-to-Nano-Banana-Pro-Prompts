# 📸 Product Photography - Part 2

> 15 prompts trong phần này

---

## 16. 3D chibi miniature brand concept store prompt

*A reusable prompt to generate 3D chibi-style miniature concept stores for any brand, focusing on their signature product, colors, and cozy interior with tiny figures.*

```
A 3D chibi-style miniature concept store for {argument name="brand name" default="Starbucks"}, creatively designed with an exterior inspired by the brand’s most iconic products or packaging (for example, a giant {argument name="core product of the brand" default="chicken bucket/hamburger/donut/roast duck"}). The store is two stories tall with large glass windows that clearly showcase a cozy, richly decorated interior: decorations themed around {argument name="primary color of the brand" default="primary color of the brand"}, warm lighting, and busy staff wearing outfits that match the brand. Cute tiny figures walk and sit along the street, surrounded by benches, streetlights, and potted plants, creating a charming urban scene. It is rendered in a miniature cityscape style using Cinema 4D, with the aesthetic of blind-box toys, abundant detail, and realistic yet soft lighting that evokes a relaxed afternoon atmosphere. Please include the mini characters by referring to the attached character sheet. --ar 2:3
```

---

## 17. Ad replacement and brand adaptation prompt for Nano Banana Pro

*A structured Nano Banana Pro prompt for recreating a provided advertisement concept while replacing the original product with the user’s own brand product, matching mood and composition while removing competitor branding.*

```
Recreate the provided advertisement concept, but substitute the original product with {argument name="my product in English" default="my product"}.

Requirements:

Visual continuity
Match the source ad’s mood, lighting, camera angle, composition, and overall atmosphere.
Do not replicate or keep any competitor logos, text, or brand marks.

Product replacement
Insert the product from {argument name="uploaded image in English" default="my uploaded image"} in place of the original item.
Ensure the replacement appears naturally integrated with accurate scale, proportions, reflections, and shadows.

Scene adaptation
Adjust all background elements, props, surfaces, and textures so they reflect {argument name="brand style in English" default="my brand’s visual style"}, flavor or aesthetic cues, and thematic identity.
Remove or redesign any elements tied to the competitor’s brand.

Output quality
Maintain photorealistic rendering throughout.
Ensure the final composition feels authentic to the original ad concept but clearly represents my brand.
```

---

## 18. Mid-20th-century war photojournalism style framework

*A Chinese prompt framework for generating gritty, realistic mid-20th-century war photojournalism style images that feel like candid shots taken under pressure, with emphasis on authenticity over cinematic perfection.*

```
[Instruction: Based on the structured description below, generate an authentic documentary photography image.]

Visual style: mid-20th-century war news photojournalism (1940–1970) – raw and unposed.

1. Core subject (specific micro narrative)
{argument name="core scene" default="a mud-covered medic in a rainy trench bandaging a soldier’s arm, looking exhausted, with barbed wire obscuring the foreground"}

2. Aesthetic characteristics (anti-cinematic approach)
Photography style definition:
This must not look like a carefully lit movie still. It has to look like a raw, even slightly blurry moment, snapped by a war photographer under extreme pressure and danger. The composition should feel accidental, chaotic, slightly off-balance or imperfect. Prioritize absolute authenticity over perfect framing.

Light and atmosphere:
Avoid overly dramatic, theatrical, perfectly staged lighting. Use whatever light is available on site (usually bad): flat and oppressive overcast diffuse light, dim flickering indoor light, or harsh direct flash creating hard, ugly shadows. The atmosphere should feel gritty, dirty, and suffocatingly immersive.

3. Physical texture (film realism)
Physical properties:
Simulate high-speed, coarse-grain black-and-white film that has been push-processed.
* Focus and blur: because of the chaotic, tense environment, the main subject may be slightly out of focus, soft, or shaken. Moving people or objects must show obvious motion blur to reflect the forced use of slow shutter speeds.
* Grain: the whole image is covered with heavy, organic silver halide film grain. Avoid artificial scratches or frame borders added in post; focus on the rough materiality of the film itself.

4. Technical constraints
* Color mode: monochrome black and white.
* Lens language: 35mm wide-angle prime lens (classic reportage perspective including more environmental information).
* Period accuracy: strictly consistent with the 1940s–1970s timeline (clothing, weapons, environmental details).
```

---

## 19. Cafe date POV profile photo prompt for Nano Banana Pro

*A detailed Nano Banana Pro image-generation prompt that creates a realistic boyfriend-material cafe date POV profile photo from a face photo, ideal for dating app profile pictures.*

```
{
  "settings": {
    "aspect_ratio": "{argument name="aspect ratio" default="3:4"}",
    "resolution": "{argument name="resolution" default="8k"}",
    "quality_preset": "{argument name="quality preset" default="high quality"}",
    "style_emulation": "{argument name="style" default="shot on iPhone style"}"
  },

  "photography_style": {
    "type": ["{argument name="photo type 1" default="realistic candid photo"}", "{argument name="photo type 2" default="photorealistic"}"],
    "perspective": "{argument name="perspective" default="POV date shot"}",
    "vibe": "{argument name="vibe" default="Boyfriend material"}",
    "lighting": {
      "source": "{argument name="light source" default="natural sunlight"}",
      "quality": "{argument name="light quality" default="soft flat lighting"}"
    },
    "focus": {
      "depth_of_field": "{argument name="depth of field" default="shallow"}",
      "background": "{argument name="background" default="blurred with other customers"}"
    }
  },

  "subject": {
    "demographics": {
      "gender": "{argument name="gender" default="male"}",
      "nationality": "{argument name="nationality" default="Japanese"}",
      "age_range": "{argument name="age range" default="20s"}",
      "descriptor": "{argument name="appearance impression" default="handsome"}"
    },

    "features": {
      "skin_texture": "{argument name="skin texture" default="naturally smooth, clear complexion, blemish-free"}",
      "retouching_level": "{argument name="retouching level" default="subtle and realistic"}"
    },

    "attire": {
      "jacket": "{argument name="jacket" default="matte black oversized nylon jacket"}",
      "jewelry": "{argument name="jewelry" default="simple silver ring (left ring finger)"}"
    },
    "pose_action": {
      "posture": "{argument name="posture" default="sitting, leaning forward, elbows on table"}",
      "hands": "{argument name="hand position" default="holding paper coffee cup with both hands"}",
      "face_interaction": "{argument name="face interaction" default="bringing cup to mouth, slightly covering mouth"}"
    }
  },

  "environment": {
    "location": "{argument name="location" default="stylish cafe"}",
    "immediate_surroundings": "{argument name="table" default="light wooden table"}",
    "architectural_details": [
      "{argument name="architectural detail 1" default="white industrial ceiling"}",
      "{argument name="architectural detail 2" default="glass partitions"}"
    ]
  }
}
```

---

## 20. JSON selfie-in-car mirror prompt for Nano Banana Pro

*A detailed JSON-formatted prompt for generating an ultra-realistic selfie of a young woman reflected in a car’s side mirror, including subject, clothing, props, environment, lighting, style, and a negative prompt.*

```
{
  "image_generation_prompt": {
    "subject": {
      "description": "Young woman with long brown hair",
      "pose": "Leaning gently on car window, resting head on one hand, relaxed and confident",
      "action": "Taking a selfie in the side mirror reflection"
    },
    "clothing": {
      "top": "Simple red turtleneck long-sleeve top",
      "accessories": "Minimalist stud earrings"
    },
    "props": {
      "item": "{argument name=\"phone model\" default=\"iPhone 17 Pro Max\"}",
      "details": "Realistic proportions, accurate lens design, held in hand"
    },
    "environment": {
      "location": "Outdoors, reflected in the side mirror of a {argument name=\"car model\" default=\"black Toyota Land Cruiser\"}",
      "background": "Trees and orange-blue evening sky",
      "depth_of_field": "Subtly blurred background for depth (bokeh)"
    },
    "lighting": {
      "type": "Golden hour",
      "characteristics": "Warm sunlight, soft natural glow, evening light, realistic shadows"
    },
    "style": {
      "aesthetic": "Natural, ultra-realistic, minimalist, Instagram style",
      "quality": "8k resolution, highly detailed, sharp focus, cinematic photography"
    },
    "technical_constraints": {
      "perspective": "Accurate mirror reflection, correct optical orientation",
      "distortion_control": "No exaggeration or distortion of features or phone"
    }
  },
  "negative_prompt": "cartoon, illustration, painting, drawing, bad anatomy, disfigured, deformed, blurry face, low quality, pixelated, unnatural lighting, distorted phone, wrong reflection angle, extra fingers, messy hair, heavy makeup, text, watermark"
}
```

---

## 21. 9-grid Japanese photobook layout prompt for Nano Banana Pro

*A very detailed prompt that creates a 9-photo Japanese photobook page with a day-to-night narrative, consistent character, styled outfits, and typographic title in the bottom margin.*

```
**[Type]:** A scanned page from a high-end Japanese photobook (shashin-shu). **A 9-grid photo layout printed on textured matte art paper.** **[Layout design]:** The 9 photos are arranged in a clean grid with **wide white margins** at the bottom to accommodate typography.  **[Subject consistency - STRICT]:** * **Source:** Based strictly on the uploaded reference image. **[SAME CHARACTER IN ALL PANELS].** * **Styling strategy:** **[RANDOMLY SELECT ONE]:**     1.  **{Classic}:** {argument name="classic outfit" default="Loose white shirt + shorts"}.     2.  **{Soft}:** {argument name="soft outfit" default="Beige knit cardigan + camisole"}.     3.  **{Pure}:** {argument name="pure outfit" default="White lace-trimmed slip dress"} (best for bath transitions).     * **Note:** In Row 3 (Bath), the outfit should create a "wet look" or reveal some skin.  **[Typography & Japanese elements - the artistic touch]:** *(The AI must render a title text in the bottom white margin.)* **[RANDOMLY SELECT ONE title theme]:** 1.  **{Theme: Summer}:** Large Japanese text **"{argument name="summer title Japanese" default="青い夏"}"** with small English text **"{argument name="summer title English" default="BLUE SUMMER"}"** below it. 2.  **{Theme: Private}:** Large Japanese text **"{argument name="private title Japanese" default="私小説"}"** with small English text **"{argument name="private title English" default="PRIVATE NOVEL"}"** below it. 3.  **{Theme: Air}:** Large Japanese text **"{argument name="air title Japanese" default="空気感"}"** with small English text **"{argument name="air title English" default="AIRY MOMENTS"}"** below it. * **Signature:** The handwritten text **"{argument name="signature text" default="By : Berryxia"}"** is placed artistically next to the title or in a corner like a watermark.  **[Grid narrative - the "day to night" journey]:**  **Row 1: Outdoor breath (wind & light)** 1.  **Top-left (wide):** Subject standing in the wind, hair blowing, **backlit by the sun**. 2.  **Top-middle (detail):** Close-up of a **hand holding a glass bottle of soda** or blocking the sun. 3.  **Top-right (motion):** Blurry candid shot of the subject **walking away on a street**.  **Row 2: Indoor play (props & "hiding")** 4.  **Center-left (hiding):** Subject sitting on tatami, **using a dried flower to cover one eye**. 5.  **Center (candid):** Subject **lying upside down on a sofa**, reading a book, face partially hidden. 6.  **Center-right (fetish focus):** Focus on **bare feet curled on the rug** or fingers touching hair.  **Row 3: Private/wet (steam & skin)** 7.  **Bottom-left (steamy back):** **Back view in a steamy bathroom**. Wet hair sticking to the nape of the neck. Soft focus. 8.  **Bottom-middle (immersion):** Subject **submerged in a bathtub**, water up to the chin, dreamy high-key lighting. 9.  **Bottom-right (end):** Detail of **steam on a mirror**.  **[Aesthetic style]:** * **Film stock:** Fujifilm Pro 400H (cyan shadows, airy highlights). * **Texture:** **Visible paper texture**, slight vignetting, layout design feel.  **[Parameters]:** --ar 2:3 --style raw --v 6.0 --stylize 200 --cref [URL] --cw 80 --no commercial smile, stiff posing, studio lighting. Use indoor hotel style B for output.
```

---

## 22. Direct flash gamer girl Nano Banana Pro JSON tag prompt

*A structured Nano Banana Pro image prompt defining a direct-flash gamer girl scene using a label and descriptive tags, ideal for retro gaming room photography aesthetics.*

```
{
  "label": "{argument name="label" default="direct-flash-gamer-girl"}",
  "tags": [
    "{argument name="lighting style" default="direct flash"}",
    "{argument name="room theme" default="retro gamer room"}",
    "{argument name="era photography" default="1990s photography"}",
    "{argument name="image aesthetic" default="film aesthetic"}",
    "{argument name="subject type" default="gamer girl"}",
    "{argument name="background detail" default="collectibles shelf"}",
    "{argument name="camera angle" default="low angle"}",
    "{argument name="pose" default="sitting pose"}"
  ]
}
```

---

## 23. Luxury seaside hotel terrace portrait prompt

*A complex Nano Banana Pro prompt for an ultra-realistic portrait of a woman at a luxury seaside hotel terrace dinner, with strict reference matching, accessories, props, lighting, and mood fully specified.*

```
{
  "project": "Ultra-Realistic Portrait",
  "reference_settings": {
    "use_reference_image": true,
    "fidelity_strength": "{argument name="reference fidelity" default="100%"}",
    "instruction": "Face and outfit must match reference photo 100% with absolutely no alterations."
  },
  "subject": {
    "demographics": "{argument name="subject gender" default="Woman"}",
    "focus_features": ["Eyes", "Nose", "Lips"],
    "expression": "Smiling, cute, fresh, dreamy, slightly sensual",
    "pose": "Sitting at a white table, resting chin on both hands, turning slightly",
    "hair": {
      "style": "Straight, large top bun",
      "accessory": "Bow matching the outfit",
      "texture": "Soft layered, loose strands falling naturally across face",
      "movement": "Slightly blown by wind"
    },
    "makeup": {
      "cheeks": "Natural blush on cheeks and nose",
      "lips": "Full lips, soft pink-peach tone"
    }
  },
  "fashion_and_accessories": {
    "outfit": "Exact match to reference image",
    "shoes": "High-heel shoes (matching reference)",
    "bag": "Same bag as reference photo",
    "jewelry": {
      "necklace": "Thin gold with alternating charms (heart, crescent moon, Gucci pendant)",
      "bracelet": "Delicate Gucci bracelet with charms",
      "rings": "Gold rings",
      "watch": "Steel-band Patek Philippe",
      "earrings": "Small gold Gucci earrings"
    }
  },
  "environment": {
    "location": "Luxury hotel terrace / Seaside",
    "time_of_day_options": [
      "Option A: Deep blue evening sky, stars, shooting star, moonlight",
      "Option B: Early sunrise, orange-yellow sky tones"
    ],
    "background_elements": [
      "Warm reflections from luxury hotel",
      "Calm seascape"
    ]
  },
  "props": {
    "table_setting": "White table",
    "items": [
      "Glass with a single white rose",
      "Wine glass",
      "Wine bottle",
      "Plate set with knife and fork",
      "Large T-bone steak in center",
      "Candle glass (adding warm highlight)"
    ]
  },
  "photography_style": {
    "aesthetic": "2000s digital-camera flash style",
    "lighting": "Realistic flash brightness, warm tone, slight shine on skin",
    "mood": "Relaxing, warm, nostalgic, stylish, elegant, slightly sexy",
    "shot_type": "Close-up portrait"
  },
  "technical_parameters": {
    "aspect_ratio": "{argument name="aspect ratio" default="3:4"}",
    "detail_level": "{argument name="detail level" default="8k"}",
    "style_tags": ["photo", "realistic", "flash photography"]
  }
}
```

---

## 24. Glassmorphism SaaS-style PPT design prompt for Nano Banana Pro

*A comprehensive UI/UX presentation design prompt that lets Nano Banana Pro generate 16:9 slides in a futuristic glass card style, combining Apple Keynote minimalism and modern SaaS aesthetics.*

```
You are an expert-level UI/UX presentation designer. Generate high-fidelity, futuristic 16:9 presentation slides. Based on visual balance aesthetics, automatically choose the most perfect composition among a cover, grid layout, or data visualization.

For the global visual language, the style should seamlessly blend Apple Keynote minimalism, modern SaaS product design, and glassmorphism. The overall mood should feel premium, immersive, clean, and breathable. Use cinematic volumetric lighting, soft ray-traced reflections, and ambient occlusion. For the color scheme, choose either deep void black or pure ceramic white as the base, accented with flowing aurora gradients such as neon purple, electric blue, soft coral orange, and cyan for the background and UI highlights.

For the content modules on each slide, intelligently integrate the following elements:

1. Use a bento grid system as the layout engine, organizing content inside modular rounded-rectangle containers. The containers must be frosted glass with blur, featuring delicate white edges and soft shadows, and strictly preserve generous internal whitespace to avoid crowding.

2. Insert gift-like 3D objects, rendering unique, high-end abstract 3D artifacts as visual anchors. They should look like tangible, expensive gifts or collectibles, with materials such as polished metal, iridescent acrylic, transparent glass, or soft silicone, and shapes like floating capsules, spheres, shields, Möbius strips, or fluid waves.

3. For typography and data, use clean sans-serif fonts with high contrast. If there are charts, use glowing 3D donut charts, capsule-shaped progress bars, or floating numbers; the charts should look like glowing neon toys.

Composition logic reference: If generating a cover, place a huge, complex 3D glass object in the center with bold large text over it and aurora waves stretching in the background. If generating a content slide, use the bento grid layout with 3D icons on small cards and text on large cards. If generating a data slide, use a split-screen design: typography on the left, and a large, glowing 3D data visualization chart floating on the right.

Rendering quality requirements: Unreal Engine 5 rendering, 8K resolution, ultra-detailed textures, strong UI design sense, UX interface, Dribbble trending style, award-winning design quality.
```

---

## 25. Product sketch to final render prompt

*A prompt for turning a rough product sketch into a clean, mass-manufactured style render with specific materials and lighting while preserving the original proportions.*

```
Render this sketch as a final mass-manufactured product. Studio lighting, injection-molded glossy white plastic body, polished oak handle, stainless steel drip tray. Keep the exact proportions of the messy sketch.
```

---

## 26. Packaging mockup with tiny text test prompt

*A concise English prompt used to test tiny text rendering and deep reasoning by asking Nano Banana Pro to generate a herbal tea box packaging mockup with accurate labels and instructions.*

```
Packaging mockup for a herbal tea box, with an accurate nutrition label, barcode, and small-print brewing instructions.
```

---

## 27. Gym selfie portrait of woman on yoga mat for Nano Banana Pro

*A structured JSON prompt describing a young woman after a workout, sitting on a yoga mat in a modern gym, wiping sweat and holding a water bottle, with detailed clothing, accessories, and background elements in a vertical gym selfie aesthetic.*

```
{
  "subject": {
    "description": "A young woman sitting on yoga mat, wiping sweat with towel, holding water bottle",
    "mirror_rules": "N/A - direct gym photo",
    "age": "late 20s",
    "expression": "accomplished, slight breathlessness, confident smile",
    "hair": {
      "color": "blonde with highlights",
      "style": "high ponytail, slightly messy with flyaways from workout"
    },
    "clothing": {
      "top": {
        "type": "sports bra",
        "color": "dusty rose pink",
        "details": "medium support, strappy back detail, moisture visible from sweat"
      },
      "bottom": {
        "type": "high-waisted leggings",
        "color": "black with mesh panels",
        "details": "ankle length, mesh cutouts on calves, compression fit"
      }
    },
    "face": {
      "preserve_original": true,
      "makeup": "minimal, dewy from workout, natural flushed cheeks, no eye makeup"
    }
  },
  "accessories": {
    "headwear": {
      "type": "none",
      "details": "hair pulled back in scrunchie"
    },
    "jewelry": {
      "earrings": "small diamond studs",
      "necklace": "none",
      "wrist": "rose gold fitness tracker, black hair ties on wrist",
      "rings": "none"
    },
    "device": {
      "type": "smartphone",
      "details": "propped against dumbbell, recording workout selfie"
    },
    "prop": {
      "type": "insulated water bottle",
      "details": "matte black 32oz bottle with motivational quote sticker, condensation visible"
    }
  },
  "photography": {
    "camera_style": "gym selfie aesthetic, smartphone front camera",
    "angle": "slightly above eye level, sitting position",
    "shot_type": "full upper body and crossed legs, centered composition",
    "aspect_ratio": "9:16 vertical",
    "texture": "crisp detail, bright gym lighting, energetic feel"
  },
  "background": {
    "setting": "modern gym studio",
    "wall_color": "light gray with motivational mural",
    "elements": [
      "purple yoga mat laid out",
      "set of dumbbells scattered nearby",
      "white towel draped over shoulder",
      "blurred gym equipment in background",
      "large mirror reflecting back wall",
      "resistance bands coiled on floor"
    ],
    "atmosphere": "energetic, accomplished, health-focused",
    "lighting": "bright overhead LED gym lighting, even coverage"
  }
}
```

---

## 28. Ad recreation prompt using your product and brand aesthetics

*A text prompt for Nano Banana Pro that recreates an existing advertisement layout with your own product and branding, keeping the composition and mood while removing competitor branding.*

```
Recreate this ad concept using {argument name="your product" default="my product"} instead of the competitor’s product. Keep the same mood, lighting, composition, and overall vibe. Remove all competitor branding.
Replace the product with the one from {argument name="reference image" default="my uploaded image"} and adapt all background elements, props, and surrounding textures to be visually relevant to {argument name="your brand" default="my product’s brand"}, {argument name="flavor profile" default="my product’s flavor profile"}, and aesthetic — not the original brand’s. Maintain photorealism and accurate product proportions.
```

---

## 29. Candid night street portrait with Ferrari prompt

*A structured JSON prompt for creating a candid 35mm film-style night street portrait of a person leaning on a yellow Ferrari, with detailed lighting, attire, and environment controls.*

```
{
  "image_metadata": {
    "resolution": "{argument name="resolution" default="1200x1200px"}",
    "genre": "Candid street portrait",
    "editing_note": "Face edited without alteration to features"
  },
  "photography_style": {
    "medium": "Analog 35mm film-style",
    "overall_aesthetic": [
      "raw",
      "nostalgic",
      "gritty"
    ],
    "visual_artifacts": {
      "grain": "Subtle but distinct film grain visible throughout frame",
      "bokeh": "Soft in background"
    },
    "color_grade": {
      "palette": "Muted and slightly warm",
      "contrast": "High contrast (typical of flash)"
    }
  },
  "lighting_characteristics": {
    "primary_source": {
      "type": "Camera flash",
      "direction": "Direct, shining on face and body"
    },
    "effects_on_subject": {
      "highlights": "Strong",
      "shadows": "Sharp, cast behind subject",
      "skin_glow": "Slight glow from flash"
    },
    "ambient_light": {
      "level": "Minimal",
      "sources": ["streetlights", "car headlights", "neon signs"],
      "appearance": "Blurred and slightly halated"
    }
  },
  "subject_details": {
    "pose": {
      "stance": "Leaning next to vehicle",
      "arms": "Folded across chest",
      "style": "Natural, candid"
    },
    "expression": "Slight smile towards the camera",
    "features": {
      "skin_texture": "Natural"
    },
    "attire": {
      "top": "Army green V-neck knit crop vest",
      "bottom": "Black shorts",
      "footwear": "White-grey New Balance 530 sneakers"
    }
  },
  "environmental_context": {
    "time_of_day": "Night",
    "setting": "Dark city street",
    "key_elements": {
      "foreground_object": "Bright yellow Ferrari F8",
      "background": {
        "brightness": "Dark",
        "noise_level": "Minimal"
      }
    }
  }
}
```

---

## 30. Futuristic facial age-checker infographic portrait

*A long, detailed prompt for creating a hyper-realistic portrait infographic that analyzes facial aging factors with overlays and labeled percentages, styled like a premium cosmetic-tech ad.*

```
A hyper-realistic, high-resolution portrait infographic based on ({argument name="reference_photo_en" default="your photo"}). Keep the same person, identity, hairstyle, clothing, and natural skin tone from ({argument name="reference_photo_short_en" default="your photo"}), with a neutral studio background. Overlay a subtle, semi-transparent facial analysis grid over the entire face, similar to a 3D face-scanning mesh: thin, soft white lines following the facial contours, slightly glowing but not hiding the skin details. Add one clean vertical red laser line running down one side of the face, like a futuristic scan. All analysis lines must be soft, minimal, and elegant, exactly like a cosmetic-tech advertisement.

Create a clean medical–aesthetic infographic that evaluates 5 aging factors using global data percentages:
1. Fine lines and wrinkles
2. Skin texture and elasticity
3. Facial volume and sagging
4. Eye area aging signs
5. Skin tone and pigmentation

For each factor, place a small label with a thin line pointing to the relevant facial area, and next to it write a short title and a realistic percentage score from 0–100% (based on global data), for example:
“Fine lines & wrinkles – 18%”
“Skin texture & elasticity – 72%”
“Facial volume & sagging – 35%”
“Eye area aging signs – 41%”
“Skin tone & pigmentation – 63%”

Use clean, modern sans-serif typography and small technical-style text, like a scientific facial analysis UI. At the bottom of the image, in the center, write a large bold text showing the final estimated real age based on the analysis, for example:
“ESTIMATED AGE: (random number based on face analysis)”

Overall style: futuristic AI-guided skincare analysis, minimalistic, premium editorial lighting, no gender specified, suitable for any human face.
```

---

