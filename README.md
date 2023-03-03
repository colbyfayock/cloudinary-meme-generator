# Meme Generator 🌭

Demo: <https://meme-generator-meme.vercel.app/>

## What is this?

Demo app built for the [Cloudinary CloudCreate Hackathon](https://cloudinary.com/blog/cloudinary-cloudcreate-tech-products-hackathon).


### Image Uploading

Uses the [CldUploadWidget](https://next-cloudinary.spacejelly.dev/components/clduploadwidget/examples) component from [Next Cloudinary](https://next-cloudinary.spacejelly.dev/) for an easy drop-in upload solution.

## Getting Started

* Install the dependencies with:

```
yarn install
```

* Create a new Upload Preset in your Cloudinary account that allows for unsigned uploads

* Add a `.env.local` file with your environment variables:

```
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME="<Your Cloud Name>"
NEXT_PUBLIC_CLOUDINARY_UPLOAD_PRESET="<Your Upload Preset>"
```

* Start your development server:

```
yarn dev
```

And your application should be available at http://localhost:3000!
