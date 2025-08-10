# ShoeFlip — Simple Website

This is a **one-file** website you can put on **GitHub Pages**. Edit the words and picture links in `index.html` to add your shoes.

## How to publish (very simple)
1) Make a **GitHub** account at https://github.com (ask an adult to help if you are under 13).
2) Click **New repository** → name it `shoeflip-site` → choose **Public** → click **Create repository**.
3) Click **Add file** → **Upload files** → upload the `index.html` from this folder, then **Commit changes**.
4) Turn on **GitHub Pages**: go to **Settings** → **Pages** → in “Build and deployment” choose **Deploy from a branch** with **main / root**. Click **Save**.
5) Wait 1–2 minutes. Your site will be at `https://YOURNAME.github.io/shoeflip-site/`.

## How to edit your shoes
- On your repo page, click `index.html`, then the **✏️ pencil**.
- Change the `CATALOG` list (brand/model/size/price/img/desc).
- Press **Commit changes**. Done!

## Contact links
At the top of `index.html`, change:
```js
const SETTINGS = {
  instagram: "https://instagram.com/your_handle_here",
  email: "mailto:you@example.com"
};
```

## Tips
- Use your own photo links. You can upload images to your repo (`/images/shoe1.jpg`) and set `img: "./images/shoe1.jpg"`.
- Be honest about condition. Use the authenticity checklist on the page.
- Don't promise “authentic” unless you truly guarantee it.
