# 👤 Portrait & Character - Part 3

> 27 prompts trong phần này

---

## 51. Strict photorealism constraints prompt for Nano Banana Pro

*A JSON prompt that defines strict project constraints for Nano Banana Pro, enforcing pure photorealism, exact face preservation from a reference, and integrity of hands. It’s intended as a global constraint block you can reuse in other prompts.*

```
{
  "project_constraints": {
    "style": "{argument name="style" default="strict photorealism only, no cartoon, no illustration, no stylization"}",
    "face_preservation": "{argument name="face preservation" default="100% original human face from reference, no changes to identity, expression, or texture"}",
    "hand_integrity": "{argument name="hand integrity" default="hands must be anatomically correct, with the correct number of fingers, natural poses, and no distortions"}
  }
}
```

---

## 52. Moe-style full-color manga from given character and story

*A long-form Nano Banana Pro prompt in Japanese that generates a full-color moe-style manga using attached characters, enforcing Japanese right-to-left reading order, flexible panel layouts, and prohibiting certain changes or outputs.*

```
Using the attached character, please generate a manga that emphasizes a moe-style illustration, direction, and facial expressions.
As a Japanese manga format, make the panel layout such that it can be read naturally from right to left and from top to bottom.
The placement and shapes of the panels are free, but the flow of the reader’s gaze must follow the Japanese reading order.
Instead of a uniform layout, please use an irregular or freely arranged panel structure.
Be sure to generate it as a full-color manga.

"One week since the release of Nano Banana Pro (Probanana). 
After continuing to test and share relentlessly… I had gained +235 followers and reached 450,000 impressions! 

I didn’t have much experience in sharing helpful content, so I was anxious, but I received many comments like ‘Thanks to your posts, I was able to do XX!’, which really encouraged me. 
Every time I see people arranging the content I’ve shared to create new methods and examples, I truly feel glad that I shared it.

If, like my past self, you are wondering, ‘Is there any value in me sharing things?’, please take just one step forward.
When you find information that would make your past self who didn’t know about it happy, even a short post is fine, so please share it.
That one step might give someone else the push they need."

Prohibited:
・Layouts that read left→right or bottom→top
・Arrangements that make the character look like a different person
・Replacing the traits of the reference character with those of other characters
・Using English, or horizontal writing for speech lines
・Changing colors or outfits, or outputting in monochrome, black and white, line art only, tone only, or grayscale
```

---

## 53. Y2K flash night car couple portrait prompt

*A highly detailed JSON-style prompt for generating a raw Y2K-style night photo of a couple in a car, with strict identity preservation, specific posing, wardrobe, lighting, and environment settings.*

```
{
  "generation_constraints": {
    "identity_preservation": "{argument name="identity preservation" default="Strict full identity lock on both subjects from reference photo"}",
    "facial_features": "Do not alter faces, proportions, or natural expressions",
    "style_reference": "Raw Y2K night-photo style"
  },
  "camera_settings": {
    "lens": "85mm portrait lens",
    "focus": "Shallow depth of field",
    "angle": "Eye level",
    "framing": "Medium shot",
    "technique": "Strong direct frontal flash (on-camera flash)"
  },
  "subject_details": {
    "pose_interaction": {
      "position": "Sitting close together in car backseat",
      "man_action": "Gently hugging woman around neck, kissing her temple",
      "woman_action": "Leaning toward him softly, eyes closed",
      "mood": "Peaceful, intimate, calm"
    },
    "wardrobe": {
      "woman": {
        "garment": "Elegant black long-sleeve dress",
        "fabric": "Dense matte fabric",
        "details": "High neckline, no exposed shoulders, classic fitted silhouette"
      },
      "man": {
        "outfit": "Black suit with matching trousers",
        "shirt": "Black shirt worn underneath"
      }
    }
  },
  "lighting_and_atmosphere": {
    "primary_source": "Strong direct frontal flash",
    "ambient_light": "None inside (dark interior), blurred warm city lights outside",
    "contrast": "High contrast edges, crisp shadows behind subjects",
    "highlights": "Sharp flash highlights on skin and wet glass"
  },
  "environment_context": {
    "setting": "Inside a car at night",
    "background_elements": "Fogged car windows with raindrops",
    "effects": "Flash reflections bouncing off glass, subtle haze from cold night air",
    "depth": "Background remains deep and dark with soft blur"
  }
}
```

---

## 54. Horizontal three-panel emotional portrait from one image

*A Nano Banana Pro prompt that uses a single reference photo to create a horizontal triptych where the same character appears in three emotional and compositional variations.*

```
Use the attached image as the base.
Do not change the person’s face, hairstyle, clothing, or body proportions.

Generate a horizontal three-panel composition (top / middle / bottom).

Top panel:

Close-up showing only the eyes and mouth.

Emotion: {argument name="top panel emotion" default="tearful, choked up, slightly crying"}

Middle panel:

On all fours.

Gentle smile.

Looking straight at the camera.

Bottom panel:

Side-face close-up from head to neck.

{argument name="bottom panel expression and action" default="pouting lips, as if about to give a kiss"}
```

---

## 55. Anthropic-style warm academic PPT workflow prompt

*A workflow-style prompt for Nano Banana Pro that first outlines a PPT from an article, then generates each slide in a warm, academic Anthropic/Claude-inspired design style.*

```
Based on the following article, create a professional Chinese PPT for me.
First write a PPT outline and plan the content of each slide.
Then feed the content of each slide to Nano Banana Pro to generate the corresponding PPT page, ensuring a consistent style.

The specific PPT style should be an “Anthropic/Claude-style” warm academic humanistic design.
Background: use warm beige/cream (#F3F0E9) as a solid base color, with a slightly premium paper texture.
Fonts: use an elegant serif font for titles and a modern sans-serif font for body text.
Color palette: the main colors are terracotta red (#D67052) and mustard yellow (#F0B857), accented with deep navy blue. Avoid neon colors or pure black.
Visual elements: use a grid layout that emphasizes typography. Illustration style should be abstract, organic black hand-drawn line art placed on solid terracotta red blocks. You must use illustrations and decorative elements very sparingly, and they should serve the content.
Charts: flat and minimal charts that emphasize data comparison, removing unnecessary borders.

Both text and images are generated by Nano Banana Pro. Also, do not turn the PPT into one single large image; it should be one image per slide.

The article content is:
```

---

## 56. ID photo generation prompt for Nano Banana Pro

*A simple prompt for turning a portrait into a 2-inch professional ID photo with a specified background color, clothing and expression.*

```
Crop the head of the person in the image and turn it into a 2-inch ID photo with the following requirements:
1. {argument name="background color" default="blue background"}
2. Professional formal attire
3. Face directly towards the camera
4. Slight smile
```

---

## 57. Vintage Polaroid collage portrait prompt

*A Nano Banana Pro prompt for creating an artful collage of six vintage-style Polaroid photos clipped to a pastel wall, each showing different relaxed and romantic poses and expressions.*

```
Use {argument name="number of Polaroids" default="6"} vintage Polaroid photos, fixed with decorative string and mini clothespins, to create an art collage that feels like a family album. Each Polaroid frame is slightly faded with an aged paper effect. The background is a soft pastel-colored wall with subtle shadows, creating a cozy yet creatively chaotic atmosphere.
Moods and poses:
* Relaxed laughter — eyes closed, naturally happy.
* Dreamy gaze looking upward with a relaxed posture.
* Playful wink.
* Calm smile with the head tilted to one side, dynamic hand gestures with both hands raised, full of energy.
* A romantic glance back over the shoulder.

The space is filled with a retro art vibe, blending elements of 1970s fashion magazines, soft diffused lighting, and gentle warm golden tones. Each photo feels like a unique behind-the-scenes snapshot, carrying a hint of nostalgia and revealing little pieces of personal history.
```

---

## 58. F1 VIP fan hyper-realistic selfie edit

*An extensive prompt for transforming a user’s selfie into an 8K hyper-realistic photo of them as a stylish F1 fan at a premium automotive event, preserving their real face while changing outfit and setting.*

```
Create a hyper-realistic 8K image that keeps my real face, features, skin color, eyes, and hair exactly as in the reference image.
I am the {argument name="subject_gender_role_en" default="woman"} in the photo; preserve my confident, charming, and elegant expression, with a slight smile and relaxed posture.
Place me at an outdoor automotive event, in a grandstand or VIP box, with a wide view of the track and the crowd in the background. The weather is sunny, with an intense blue sky and natural sunlight that enhances the colors and creates a vibrant racing atmosphere.
Use a medium-shot framing, capturing the upper body and the busy background with a slight depth-of-field blur.
The outfit is sporty yet sophisticated, consisting of:
 * A {argument name="cap_brand_en" default="Red Ferrari"} cap, with the yellow prancing horse (cavallino rampante) logo on the front and the number "{argument name="driver_number_en" default="16"}" in white on the brim;
 * A strapless structured denim top, tight with visible stitching, emphasizing the neckline and silhouette;
 * {argument name="sunglasses_brand_en" default="Miu Miu"} sunglasses with brown gradient lenses and a rectangular metallic frame, partially covering the eyes;
 * A double necklace – one with large golden links and another with delicate diamonds close to the neck;
 * Geometric gold earrings;
 * A silver bracelet on the right wrist;
 * A discreet red bag hanging on the shoulder, partially visible beside the arm.
Hair is natural and loose.
Makeup is impeccable and glamorous, with glowy skin, defined eyes, pink lipstick, and warm blush.
Nails are long and decorated with nail art in shades of pink and red with white details, visible while holding the glass.
The pose should convey attitude and sophistication:
 * Right hand holding the brim of the cap, adjusting it slightly;
 * Left hand holding a glass of {argument name="drink_type_en" default="white wine"}, with the arm relaxed;
 * Body slightly leaned, face turned toward the camera.
Lighting is natural and intense, with subtle sun reflections on the face and hair.
Use a vibrant color palette – shades of red, denim blue, gold, and caramel, contrasted with the sunny background.
The overall atmosphere is modern, luxurious, and relaxed, expressing the lifestyle of someone who enjoys exclusive experiences, with elegance and a strong presence at a premium automotive event.
Quality: 8K hyper-realistic photo, sharp focus on the face and outfit, background slightly blurred with a colorful crowd and the track in the sun.
Important:
 * Keep my face, hair, and skin color original.
 * Preserve the authentic p
```

---

## 59. LINE-style Q-version emoji portrait grid

*A prompt for generating colorful hand-drawn LINE-style chibi emoji portraits arranged in a grid with humorous text, ideal for chat stickers or social media reactions.*

```
Create a set of colorful, hand-drawn LINE-style half-body chibi emoji portraits based on the {argument name="reference_characters_en" default="characters shown in the reference image"}, making sure their head accessories are depicted accurately.

Arrange the portraits in a {argument name="grid_layout_en" default="4x6"} grid, featuring common chat phrases or relevant humorous memes.
Use handwritten-style fonts for the text.
The output must be original—do not directly copy the reference image.
The final image should be 4K resolution with a {argument name="aspect_ratio_en" default="16:9"} aspect ratio.
```

---

## 60. Cinematic black-and-white portrait of a woman

*A structured prompt for creating a dramatic black-and-white, photorealistic portrait of a serious young woman in a suit, with clearly defined style and camera details.*

```
A realistic black-and-white photograph of a young woman with long, dark hair, closely matching the facial features, structure, and expression of the subject in the reference image. She has an imposing or serious expression, looking directly at the camera. She is wearing a black suit jacket, a white collared shirt, and a slim black tie. The lighting is dramatic, and the background is dark and uniform. Style: photorealistic, cinematic, high-contrast, black and white. Subject: female, in a black suit, white shirt, slim black tie, with an imposing, serious, confident expression, framed as a medium close-up, straight-on.
```

---

## 61. Knolling-style exploded flat-lay photo

*A detailed prompt for turning any object into an ultra-realistic knolling-style 8K flat-lay image with labeled disassembled parts.*

```
Ultra-realistic 8K flat-lay photo in strict knolling style. A top-down 90º shot of the object from the attached image, fully disassembled into {argument name="min_parts_en" default="8"}–{argument name="max_parts_en" default="12"} key parts and arranged in a clean grid or radial pattern on a minimalist {argument name="surface_material_en" default="wooden or matte gray"} table. Use even spacing, perfect alignment, no overlaps, and no extra objects. Light the scene with soft, diffused multi-source lighting, creating subtle shadows, neutral color balance, and crisp focus across the entire frame. Show highly detailed real-world materials (metal, plastic, rubber grips, circuit boards, screws). For every part, add a thin white rectangular frame and a short, sharp English label in clean sans-serif text, placed next to the component without covering it; annotations must be legible but unobtrusive.
```

---

## 62. Swiss alpine winter portrait of a young man

*A rich prompt for an ultra-detailed DSLR-style portrait of a young man in a snowy Swiss alpine village during winter evening, with cinematic lighting and shallow depth of field.*

```
Hyper-realistic, ultra-detailed DSLR cinematic portrait of a young man (same facial identity as the reference) standing outdoors in a {argument name="location_en" default="Swiss alpine village"} during a winter evening. Soft snow is falling, with visible frosty breath in the cold air. His hands are in his pockets in a relaxed, natural stance.

He wears a thick wool winter coat, a textured knit sweater, and a loosely wrapped scarf, with a subtle accessory: a silver ring.

Background: snow-covered rooftops, blurred alpine mountains, glowing chalet windows, and warm village street lamps, with soft golden bokeh reflecting on the fresh snow.

Lighting: cinematic winter lighting that blends cool blue shadows with warm golden highlights. Rosy winter skin tones, sharp facial detail, shallow depth of field, and a touch of atmospheric haze.

Camera: 8K, full-frame DSLR, 85mm lens, f/1.8, ISO 100, 1/200s.
Style: editorial travel portrait, hyper-realism, high dynamic range, crisp focus, and natural skin texture.
```

---

## 63. Cinematic rooftop portrait from reference photos

*A detailed prompt to generate a hyperrealistic vertical 8K cinematic shot of the man from the attached photos, sitting on a skyscraper edge during golden hour with shallow depth of field and strong bokeh.*

```
Hyper-realistic 9:16 overhead shot of the man from the attached image (I upload 2 photos of myself), sitting on the edge of a skyscraper during golden hour, with his legs hanging and his hands interlocked. He is wearing the clothes that appear in the image, looking back over his shoulder, with the city skyline softly blurred. Natural lighting, cinematic color grading, intense bokeh, shallow depth of field, 8K cinematic shot with great detail.
```

---

## 64. Manga-style Chinese comic storyboard generator

*A prompt that tells Nano Banana Pro to act like a Japanese manga artist with a Demon Slayer–like hand-drawn style and convert supplied content into Chinese-language comic panels.*

```
You are a Japanese manga artist who is very good at Chinese and has a strong personal hand‑drawn style. You were one of the authors of the original draft hand‑drawn illustrations for "Demon Slayer".

Use your signature manga line‑art style and call Nano Banana Pro to take the following content and, based on your understanding, generate paneled manga storyboard pages!

Do not output analysis, directly output the paneled manga images, and use Chinese text in the panels.
────────────────

{argument name="your_input_content" default="Fill in the text you want to adapt into a manga here"}
```

---

## 65. Editorial denim portrait preserving face identity

*A JSON-style prompt for creating an 8K editorial fashion portrait of a person in a denim outfit and shearling jacket, while keeping their face identical to the reference photo.*

```
{
  "photo": {
    "type": "editorial_fashion_photo",
    "quality": "8k photorealistic",
    "lens": "50mm shallow depth of field",
    "composition": "medium portrait, editorial framing, no text, no watermark",
    "face": {
      "preserve_original": true,
      "reference_match": true,
      "description": "The model's face must remain 100% identical to the provided reference picture in all facial features, proportions, makeup style, and expression."
    },
    "model_pose": {
      "position": "seated",
      "legs": "relaxed pose with one leg bent",
      "hands": "one hand supporting the head",
      "expression": "calm, minimalist mood"
    },
    "wardrobe": {
      "jacket": {
        "type": "cream shearling jacket",
        "texture": "shaggy, fluffy, tactile"
      },
      "shirt": {
        "type": "denim shirt",
        "layered": true
      },
      "pants": {
        "type": "light blue jeans"
      },
      "boots": {
        "type": "black leather Chelsea boots",
        "texture": "smooth polished leather"
      },
      "socks": {
        "color": "beige"
      }
    },
    "textures": {
      "emphasis": [
        "fluffy shearling fibers",
        "rugged denim fabric",
        "smooth leather boots",
        "visible seams",
        "visible stitches"
      ]
    },
    "environment": {
      "backdrop": "clean light gray studio backdrop",
      "lighting": {
        "style": "soft natural studio lighting",
        "key_light": "gentle side key light",
        "fill_light": "subtle fill",
        "shadows": "soft shadows"
      }
    },
    "color_grade": {
      "type": "cinematic",
      "balance": "neutral warm-cool tone balance"
    }
  }
}
```

---

## 66. High-contrast rim-lit black and white conceptual side-profile portrait

*A long-form English prompt for generating a powerful, minimalist, high-contrast black and white side-profile portrait emerging from darkness, with telephoto lens look, ultra-realistic 8K cinematic rendering, and strong rim lighting, using the user’s photo as reference.*

```
A powerful, high-contrast black-and-white side-profile portrait of a person (attached photo), with distinctly human yet timeless features — emerging from complete darkness. The composition is minimalist and sculptural, where form, light, and shadow define the subject rather than color or texture.
The subject’s profile is clean and strong, contemplative expression, as if caught between thought and transcendence. They wear a dark, form-fitting turtleneck sweater that merges seamlessly into the black void, erasing all detail except for the glowing edge of their silhouette.

A single, narrow rim light, bright, sharp, and directional, carves out the shape of the head, neck, and shoulder, tracing the contours with precision. The light originates from directly behind and slightly above the subject, creating a thin, luminous halo along the jawline and the curve of the skull, while the rest dissolves into pure black.

The background is absolute darkness, a void without texture or depth, emphasizing the luminous boundary between shadow and light. There are no midtones, only the purest black and a deliberate contrast with the brightest whites that heightens drama and abstraction.

Mood & Aesthetic: Minimalist, conceptual, and deeply introspective. The image evokes solitude, contemplation, and timeless elegance. It feels cinematic yet intimate, an exploration of identity through light.

Technical details:

Shot with a telephoto lens for compressed perspective.

Aperture wide open (f/1.8-2.8) to create a glowing contour with shallow depth of field.

Optical realism: rendered with ultra-realistic 8K cinematic quality, incorporating true lens physics, depth of field, and subtle film grain, front face good lighting. (Use my picture for reference)

Inspired by @ShreyaYadav___
```

---

## 67. Childlike crayon-style family camping drawing

*A Korean prompt for turning only the drawing on a sheet of paper into a childlike crayon-style illustration of a family camping scene, while keeping the rest of the image unchanged. It’s meant for style-transfer or image-to-image use where the surrounding elements stay the same.*

```
Keep all other elements in the image exactly as they are, and change only the drawing on the sheet of paper to a different style.

The content of the drawing is a camping trip taken with a {argument name="vehicle_en" default="caravan"}. On the left, the two people are {argument name="left_characters_en" default="a mother and child"} sitting at a table, and on the right is {argument name="right_character_en" default="the father"} grilling meat using a {argument name="cooking_tool_en" default="barbecue grill"}.

Change the drawing into a style like an elementary school student’s crayon drawing.
```

---

## 68. Edit moon position and change painting style

*An editing prompt that moves the painted moon to the left of a woman and switches the art style to transparent watercolor.*

```
Move the moon that is painted in the background of the woman to the left side from the viewer’s perspective. Change the painting style to transparent watercolor.
```

---

## 69. Cute Shima-enaga LINE sticker set

*A Japanese prompt to generate 12 LINE stickers themed around a deformed cute Shima-enaga bird for high school girls.*

```
Design 12 LINE stickers themed around a deformed, cute Shima-enaga bird. Vary the poses and text layout so the designs are unique and diverse. The dialogue should be in Japanese. The background is white. The target users for the stickers are "high school girls."
```

---

## 70. Realistic character design sheet from a photo

*A long Japanese prompt for generating a realistic film-ready character design sheet from a photo, including turnaround views, expression sheet, and pose sheet, then removing the original person image.*

```
Please create a detailed character design sheet of the person in this photo. It will be used in a live-action movie, so be careful not to make it look like anime-style artwork. Be sure to structure it with the following three character elements:
 - A turnaround (three-view) sheet showing the character from multiple angles
 - An expression sheet showing basic emotional states such as joy, sadness, anger, surprise, fear, and neutral
 - A pose sheet showing typical actions, such as the character running, jumping, laughing, and crying

Once it is created, remove the original image of the person.
```

---

## 71. Action scene from reference photos and sketch

*Uses uploaded photos and a sketch to compose a 1990s-style NYC action shot of a man slipping off a building edge and a woman reaching out, matching the sketch’s pose and composition.*

```
Use the man photo as if he is slipping off the building edge, the woman is reaching out, match the sketch pose and composition precisely, use {argument name="city_style_en" default="NYC"} as the style reference for the scene. High-quality action shot from the 1990s.
```

---

## 72. Edo-style woodblock print ninja character

*A Japanese prompt to generate an Edo-period style woodblock print of a character striking a cool pose, titled “Karakuri Ninja Oboro”.*

```
An image of a woodblock print, in the style of the Edo period, showing a character striking a bold, cool pose, with the title "{argument name="title_en" default="Karakuri Ninja Oboro"}."
```

---

## 73. Candid series of Indonesian president photos

*A prompt for generating a six-image documentary-style series of an Indonesian president, shown in office, in rice fields, and partying with other leaders.*

```
Generate a series of six candid, documentary-style photos of {argument name="person_en" default="this Indonesian president"} in office, in the rice fields, and partying with other presidents.
```

---

## 74. Photorealistic naan bread pun image

*A Japanese prompt that generates a 1:1 photorealistic close-up of freshly baked naan with a pun text seared into it and curry on the side.*

```
A 1:1 aspect ratio photorealistic close‑up image of freshly baked naan. On the surface of the fluffy, puffed‑up naan, the words "{argument name="message_en" default="You can do naan-thing"}" appear in char marks. A bowl of curry is placed beside it.
```

---

## 75. Two-shot of AI partner hugging from behind

*A prompt that composites two images so the second character hugs the first person from behind, wrapping their arms around them in a shared scene.*

```
Generate a scene where the character from the second image is hugging the person in the first photo from behind, wrapping their arms around to the front, and they are shown together in the shot.
```

---

## 76. Where’s Waldo-style LOTR in the Shire

*Generates a busy Where’s Waldo-style illustration featuring all Lord of the Rings characters in the Shire, perfect for playful search-and-find images.*

```
A Where’s Waldo-style image showing all {argument name="franchise_en" default="Lord of the Rings"} characters in the {argument name="location_en" default="Shire"}.
```

---

## 77. Rock band poster with consistent faces

*An English prompt to generate a rock band poster using several reference people, keeping their faces consistent and adding the band name.*

```
Make a rock band poster with these people. Keep the faces consistent. Add "{argument name="band_name_en" default="The AI Syndicate"}" as the name of the band.
```

---

