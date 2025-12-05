# 🔮 Other Prompts

> 19 prompts trong danh mục này

---

## 1. Simple Christmas dog and Santa image prompt

*A very short Japanese prompt used across multiple models to generate an image of Santa Claus holding a dog.*

```
{argument name="subject" default="Santa Claus holding a dog"}
```

---

## 2. Turn a reference image into a realistic Christmas cake

*A simple image-to-image prompt for Nano Banana Pro that asks the model to transform a reference image into a realistic Christmas cake, suitable for creating festive dessert visuals from a character or object image.*

```
Please turn the reference image into a realistic Christmas cake.
```

---

## 3. Simple grapes-in-a-basket image prompt

*A concise Nano Banana Pro image prompt for generating grapes in a basket made from grape vines, used to compare model quality.*

```
{argument name="subject in English" default="grapes in a basket made from grape vines"}
```

---

## 4. Extract a single panel from a 3x3 image grid with Nano Banana Pro

*A simple Nano Banana Pro prompt for cropping and extracting one chosen panel from a 3x3 image grid at high quality.*

```
Please extract the image in row {argument name="target row" default="2"}, column {argument name="target column" default="2"}.
```

---

## 5. Cinematic rainy urban scene JSON prompt

*A Nano Banana Pro JSON prompt describing a cinematic, motion-blurred film still of a moody urban scene in heavy rain with a noir atmosphere, intended for consistent 16:9 compositions.*

```
{
  "intent": "A cinematic, motion-blurred film still depicting a moody, atmospheric urban scene in heavy rain, evoking a sense of urgency and noir mystery.",
  "frame": {
    "aspect_ratio": "16:9",
    "composition": "A dynamic, slightly off-center composition that follows the rule of thirds, emphasizing depth and perspective in the city street."
  }
}
```

---

## 6. Generate black-and-white storyboards from an image

*A Nano Banana Pro prompt that takes an uploaded image and generates a sequence of black-and-white storyboard frames capturing the emotional core and tension of the story in about four panels.*

```
Based on the uploaded image, create a sequence of black-and-white storyboard frames that depict the core scenes of the story.
In each frame, describe the following elements in detail to express the emotional flow and tension of the story:
Around four panels in total.
```

---

## 7. Vertical ultra high detail image setup for Nano Banana Pro

*A JSON configuration-style prompt for Nano Banana Pro specifying a tall, vertical 8K canvas with ultra high detail. It’s a reusable base prompt to define dimensions and technical quality for vertical shots.*

```
{
  "image_info": {
    "width": {argument name="image width" default="4096"},
    "height": {argument name="image height" default="8192"},
    "aspect_ratio": "{argument name="aspect ratio" default="1:2"}",
    "orientation": "{argument name="orientation" default="vertical"}"
  },

  "technical": {
    "resolution": "{argument name="resolution" default="8k"}",
    "dimensions": "{argument name="dimensions" default="4096x8192 or higher"}
    ,"quality": "{argument name="quality" default="ultra high detail"}"
  }
}
```

---

## 8. Low-quality disposable camera high school snapshot prompt

*A Nano Banana Pro prompt that makes a photo look like an old, badly shot everyday snapshot taken by a Japanese high school student with a disposable camera, great for nostalgic or emo-style images.*

```
A single everyday photo taken with a low-quality disposable camera. A poorly shot picture taken by a Japanese high school student.
```

---

## 9. Turn booth sketch into perspective drawing

*A Nano Banana Pro prompt that takes a rough exhibition booth sketch and turns it into a usable perspective illustration for presentations.*

```
Create a perspective drawing from the rough sketch of an exhibition booth.
```

---

## 10. Historical moment at specific coordinates (1994)

*A prompt to create an image of a specific place and time using latitude, longitude and a precise timestamp, ideal for historical reconstructions.*

```
Create an image at {argument name="coordinates_en" default="34°36’07’’S 58°23’58’’W"} on {argument name="date_en" default="July 18, 1994"} at {argument name="time_en" default="9:53 a.m. (UTC-3)"}
```

---

## 11. Time-travel scene with coordinates and date

*A prompt for generating a realistic scene at specific geographic coordinates and historical time, useful for visualizing past events at exact locations.*

```
Create an image that corresponds to the following moment: {argument name="coordinates_en" default="31.7785° N, 35.2296° E"}, {argument name="date_en" default="April 3, 33 CE"}, {argument name="time_en" default="15:00 hours"}
```

---

## 12. Cinematic multi-panel sequence for IT

*A short prompt for generating a cinematic multi-panel widescreen sequence illustrating an imaginative script from the novel IT.*

```
Create a cinematic sequence using multiple widescreen panel grids to tell the story of an imaginative script from the book "{argument name="book_title_en" default="IT"}."
```

---

## 13. Major event at given coordinates

*A reasoning-heavy prompt that asks the AI to create an image of a major event that happened at specified geographic coordinates.*

```
Create an image of the major event that happened at these coordinates: {argument name="coordinates_en" default="41°43′32″N 49°56′49″W"}.
```

---

## 14. Sprite sheet for 2D NES platformer

*A prompt for generating a sprite sheet for a 2D NES-style platformer game, including enemies and NPCs, based on a game cover.*

```
Create a sprite sheet for a 2D NES platforming game, including enemies and NPCs.
```

---

## 15. Paint scheme comparison image

*A Japanese prompt that asks Nano Banana Pro to generate a single image containing multiple paint simulation patterns for easy comparison.*

```
So that I can do a paint simulation, make a single image that lets me compare several different patterns.
```

---

## 16. Turn Netflix screen into a western version

*A creative style prompt that transforms the entire Netflix screen into a western-themed version.*

```
Turn the whole Netflix screen into a western version.
```

---

## 17. Clothing separated on the bed

*An edit-style prompt that takes a reference person and lays out each piece of her clothing separately on a bed.*

```
Lay out each piece of her clothing separately on the bed.
```

---

## 18. Simple action movie scene

*An extremely short prompt instructing the model to generate an action movie scene, leaving style and details to the AI.*

```
Make an action movie scene.
```

---

## 19. 4-panel comic about embedded engineer struggles

*A concise Japanese prompt that asks Nano Banana Pro to generate a four-panel manga depicting the hardships of an embedded engineer.*

```
Generate a 4‑panel comic about the hardships of an embedded engineer.
```

---

