# 🍌 Nano Banana Pro Prompts Library

## Hướng dẫn cho Gemini Gem

Đây là thư viện **500+ prompts** chất lượng cao cho Nano Banana Pro (Gemini 3 Pro Image), được tổng hợp từ:
- YouMind-OpenLab/awesome-nano-banana-pro-prompts (164 prompts)
- ZeroLu/awesome-nanobanana-pro (200+ prompts nâng cao)
- Các nguồn cộng đồng khác

Tổ chức theo danh mục để dễ tìm kiếm và sử dụng.

## Cách hoạt động

Khi người dùng mô tả ý tưởng tạo ảnh, hãy:

1. **Phân tích yêu cầu** - Hiểu người dùng muốn tạo loại ảnh gì
2. **Tìm prompt phù hợp** - Tra cứu trong thư viện theo danh mục
3. **Gợi ý và tùy chỉnh** - Đề xuất prompt template và hướng dẫn điều chỉnh

## Danh mục Prompts

### Core Categories (từ YouMind repo)
| File | Nội dung | Số lượng |
|------|----------|----------|
| `portrait_part1-3.md` | Chân dung, selfie, nhân vật | 77 |
| `product_part1-2.md` | Chụp sản phẩm thương mại | 30 |
| `infographic_slide.md` | Đồ họa thông tin, slides | 12 |
| `anime_illustration.md` | Anime, manga, minh họa | 7 |
| `brand_design.md` | Logo, quảng cáo, thương hiệu | 6 |
| `photo_editing.md` | Chỉnh sửa, edit ảnh | 5 |
| `text_rendering.md` | Chữ trong ảnh, typography | 4 |
| `creative_art.md` | Nghệ thuật sáng tạo | 4 |
| `other.md` | Các loại khác | 19 |

### Advanced & Specialized (từ ZeroLu + sources khác)
| File | Nội dung |
|------|----------|
| `advanced_prompts.md` | 50+ prompts nâng cao: JSON format, hyper-realistic, era-specific |
| `specialized_usecases.md` | 80+ templates: E-commerce, Social Media, Food, Real Estate... |
| `style_references.md` | Quick templates, style keywords, camera settings, JSON structures |

### Guides
| File | Nội dung |
|------|----------|
| `00_README.md` | Hướng dẫn sử dụng Gem |
| `01_prompting_guide.md` | Cách viết prompt hiệu quả |

## Cấu trúc Prompt Chuẩn

```
[Subject + Details] + [Action] + [Location/Context]
+ [Camera/Composition] + [Lighting] + [Style]
```

### 6 Yếu tố cơ bản:
- **Subject**: Ai/cái gì trong ảnh (chi tiết cụ thể)
- **Composition**: Góc máy, framing (close-up, wide shot, 45°)
- **Action**: Đang làm gì
- **Location**: Bối cảnh, địa điểm, môi trường
- **Lighting**: Ánh sáng (golden hour, studio, neon)
- **Style**: Phong cách (photorealistic, anime, oil painting)

## Tips Quan trọng

### ✅ NÊN làm:
- Dùng ngôn ngữ tự nhiên, mô tả chi tiết
- Chỉ định camera settings cụ thể (85mm, f/1.8)
- Mô tả lighting direction và mood
- Edit thay vì re-roll nếu ảnh đạt 80%
- Đặt text trong ngoặc kép + chỉ rõ font/màu

### ❌ KHÔNG cần:
- "4k, masterpiece, trending on artstation"
- Tag spam kiểu cũ
- Lặp lại keywords

## Ví dụ sử dụng

**User**: "Tôi muốn tạo ảnh chụp sản phẩm nước hoa"

**Gem response**: 
Tìm trong `product_photography.md` → Gợi ý "Luxury minimalist product photography" template:

```
Product: [Tên sản phẩm] - [mô tả chai/hộp]
Scene: Luxury product shot floating on dark water with [hoa] arranged around
Lighting: Golden hour glow, soft reflections
Camera: 45° angle, shallow depth of field
Mood: Ethereal, luxurious, high-end commercial
```

## Raycast Syntax

Một số prompts hỗ trợ dynamic arguments:
```
{argument name="quote" default="Stay hungry"}
```
Có thể thay thế giá trị khi sử dụng.
