# 📚 Nano Banana Pro - Hướng dẫn Viết Prompt

## Nguyên tắc Core

Nano Banana Pro là model "Thinking" - hiểu ngữ cảnh và ý định, không chỉ match keywords.

## Template theo Use Case

### 🖼️ Portrait/Chân dung
```
Create a photorealistic image of [subject description].
[Pose and expression]. [Location/setting].
[Lighting: golden hour/studio/natural].
Shot on [lens: 85mm/35mm], [aperture: f/1.8].
[Mood/atmosphere].
```

### 📦 Product Photography
```
Product: [name] - [shape], [material], [color]
Scene: [setting with props]
Lighting: [studio setup / natural]
Camera: [angle], [lens], shallow depth of field
Style: High-end commercial, [mood]
```

### 📊 Infographic/Slide
```
Create a [style: McKinsey/flat/hand-drawn] [type: infographic/slide].
Topic: [subject]
Include: [data points/sections]
Style: [color palette], professional typography
Layout: [structure description]
```

### 🎨 Anime/Illustration
```
[Anime style: Ghibli/Shinkai/Shonen/Chibi]
[Character description with details]
[Pose and action]
[Scene/background]
[Color palette]
[Effects: sparkles/speed lines/glow]
```

### ✏️ Photo Editing
```
[Action: Remove/Replace/Change/Add] [object/element].
[New state or replacement].
Match existing lighting and shadows.
Seamless integration, no artifacts.
```

## Camera & Composition Keywords

### Góc máy
- Eye level | Low angle (heroic) | High angle (vulnerable)
- Bird's eye | Dutch angle (tension) | POV shot

### Framing
- ECU (extreme close-up) | CU (close-up) | MCU (medium close-up)
- MS (medium shot) | FS (full shot) | WS (wide shot)

### Lens Effects
- 24mm wide (environmental) | 35mm (street)
- 50mm (natural) | 85mm (portrait bokeh)
- 135mm (compression) | Macro | Fisheye

## Lighting Keywords

### Natural
- Golden hour | Blue hour | Overcast (diffused)
- Backlit/rim lighting | Dappled light

### Studio
- Key light 45° | Fill light 25% | Rim/hair light
- Softbox | Ring light | Single source dramatic

### Mood
- High key (bright) | Low key (dark)
- Chiaroscuro | Rembrandt | Split lighting

## Style Keywords

### Photography
- Editorial | Commercial | Lifestyle | Documentary
- Fine art | Fashion | Street

### Art
- Oil painting | Watercolor | Digital illustration
- Vector | Pencil sketch | Mixed media

### Film/Cinematic
- Film noir | Wes Anderson | Cyberpunk
- Vintage 70s | Kodak Portra | Fuji colors

## Conversational Editing

Sau khi generate, dùng ngôn ngữ tự nhiên:
- "Change the background to sunset beach"
- "Make her dress red instead of blue"
- "Add more dramatic shadows"
- "Remove the person in background"
- "Change from day to night"

Model tự điều chỉnh lighting và reflections.

## JSON Structured Prompt (Advanced)

```json
{
  "subject": {
    "type": "person/product/scene",
    "description": "detailed description"
  },
  "composition": {
    "framing": "medium shot",
    "angle": "eye level",
    "lens": "85mm f/1.8"
  },
  "lighting": {
    "type": "natural/studio",
    "direction": "45° left",
    "mood": "warm golden"
  },
  "style": "photorealistic/anime/painterly",
  "negative": "things to avoid"
}
```

## Quick Reference

| Muốn tạo | Dùng keywords |
|----------|---------------|
| Ảnh thật | photorealistic, shot on [camera], [lens]mm |
| Ảnh studio | studio lighting, softbox, clean background |
| Golden hour | golden hour, warm tones, rim lighting |
| Cinematic | cinematic, 16:9, film grain, dramatic |
| Anime | anime style, [studio name], cel shading |
| Minimalist | minimalist, negative space, clean |
| Vintage | vintage, film grain, Kodak/Fuji colors |
