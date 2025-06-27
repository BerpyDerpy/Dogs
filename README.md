# 🐕‍🦺

### This is a web application that uses the [Dog CEO Dog API](https://dog.ceo/dog-api/) to display random dog images.

---

## 📡 API Used

**Dog CEO's Dog API** - [https://dog.ceo/dog-api/](https://dog.ceo/dog-api/)

This is a free and public API that provides random dog images and breed-specific images.

### Endpoint Used

```
GET https://dog.ceo/api/breeds/image/random/15
```

**What it returns:**
A JSON object with an array of 15 random dog image URLs:

```json
{
  "message": [
    "https://images.dog.ceo/breeds/hound-afghan/n02088094_1007.jpg",
    "https://images.dog.ceo/breeds/papillon/n02086910_3304.jpg",
    "...more image URLs..."
  ],
  "status": "success"
}
```

## 🖥️ How the App Works

1. **Initial Load:**

   * When the page loads, it fetches 15 random dog images from the API.
   * Each image is displayed in a "card" with the breed name shown below the image.

2. **Refresh Button:**

   * Clicking the **"Refresh Dogs"** button triggers a new fetch request.
   * The page updates with a fresh set of 5 random dog images.

3. **Filter/Search:**

   * A search box allows users to filter the displayed images by breed name.
   * Typing text in the filter will instantly hide images that don't match.
     
---

## 📂 Files Included

* `index.html` → Complete app with HTML, CSS, and JavaScript.








