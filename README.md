Meta-help is a resource created to help you figure out all of the rules for managing your digital metadata. This is a collection of information created as we learn how to cope with all of the different ways you can mark up your digital life.

## Facebook

### Standard Tags

  <meta property="og:site_name" content="">
  <meta property="og:title" content="">
  <meta property="og:image" content="">
  <meta property="og:url" content="">
  <meta property="og:description" content="">
  <meta property="article:author" content="" />
  <meta property="article:publisher" content="" />
  <meta property="og:type" content="" />

### Images

Use images that are at least 1200 x 630 pixels for the best display on high resolution devices. At the minimum, you should use images that are 600 x 315 pixels to display link page posts with larger images. The minimum image size is 200 x 200 pixels.

## Twitter

### Standard Markup

  <meta name="twitter:card" content="">
  <meta name="twitter:site" content="">
  <meta name="twitter:image" content=""><!-- Image must be less than 1MB in size -->
  <meta name="twitter:creator" content="">
  <meta name="twitter:title" content=""><!-- Max 70 chars -->
  <meta name="twitter:description" content=""><!-- max 200 chars -->

### Card Types
* summary
* summary_large_image
* app
* player

## Schema.org your brand

### Tip #1. Use ld+json

We used to bake metadata into our HTML and found that gets messy fast. Using the ld+json syntax is a much better solution. It's easier to edit, maintain, and read. 

Our experience shows that you can embed this anywhere in your code. We typically put it in the footer directly after where we put the address.

### Tip #2. Elements to include

* Name
* URL
* Logo
* Address

### Tip #3. Logo Size

This one is important. The logo you set is displayed by Google when you are found in a search. Your logo should be square. 

Wide, short logos, which we see and use a lot, don't work well in the way Google displays them in the knowledge graph. They get shrunk down to be almost invisible.

The solution if you have a non-square logo is to use one of your fav / touch icons -- Typically the largest that you produce.

### Tip #4. Pick the right organization type

Pick the type that best describes your organization. Some types, such as [LocalBusiness](http://schema.org/LocalBusiness), provide additional fields that you can set to improve your apperance.

Look for "More specific Types" towards the bottom of the [Organizatoin](http://schema.org/Organization) page to dig into this list.

## Resources

* [Facebook Sharing Best Practices](https://developers.facebook.com/docs/sharing/best-practices)
* [Facebook Open Graph URL Debugger](https://developers.facebook.com/tools/debug)
* [Twitter Markup Reference](https://dev.twitter.com/cards/markup)
* [Twitter Card Validator](https://cards-dev.twitter.com/validator)
* [Schema.org](http://schema.org/)
