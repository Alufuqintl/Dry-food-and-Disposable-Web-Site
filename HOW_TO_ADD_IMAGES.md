# How to Add Your Own Images

It is very easy to add your own product images to the website. Follow these simple steps:

## Step 1: Prepare Your Images
1. Take photos of your products (or download them).
2. Rename the files to something simple and lowercase.
   *   **Example:** instead of `WhatsApp_Image_2024.jpg`, rename it to **`mayo.jpg`** or **`oil.jpg`**.
3. **Copy or Save these image files** into your website folder:
   *   Folder: `Desktop > ALUFUQ INTL`

## Step 2: Update the Code
1. Open the file **`products.html`**.
2. Scroll down to the bottom where you see the **`<script>`** section (around line 180).
3. You will see a list of products that looks like this:

```javascript
{ 
    name: "Premium Mayonnaise", 
    category: "condiments", 
    desc: "Creamy, rich texture...", 
    size: "1 Gallon / 5L", 
    image: "https://images.unsplash.com/photo-..." 
},
```

4. **Replace the web link** in the `image: "..."` part with your new filename.

**Example Change:**
*   **Old:** `image: "https://images.unsplash.com/photo-158523..."`
*   **New:** `image: "mayo.jpg"`

## Step 3: Refresh
1. Save the file.
2. Refresh your web browser. Your new image should appear!

## Tips
*   Make sure the filename in the code matches the file in the folder **exactly** (capital letters matter! `Mayo.jpg` is different from `mayo.jpg`).
*   Square images (1:1 ratio) look best in the design.
