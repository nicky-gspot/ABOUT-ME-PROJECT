# ABOUT-ME-PROJECT
This is my final project README file

Nicky Glynos
[![Netlify Status](https://api.netlify.com/api/v1/badges/86e95467-84fb-44df-9869-45f453a7f2c1/deploy-status)](https://app.netlify.com/sites/about-me-nickyg24/deploys)

This About Me project showcases my interests, hobbies and jobs on a webpage. On the first assignment About Me: Your First Local Website talks about my business that I created where I sell 1:400 model aicraft and a fictional bio and phone number since my business is only online and put a little bio about the business in the h1 section. I knew a little about hmtl from a class I took in high scool but that was three years ago and we only did minor activites having to do with it so this project was a refresher for me and pretty simple to figure out. About Me: Adding HTML, Images, & Links was awesome because I was able to create an avattar that looked like me and I did not know that the code was very specific and you had to put that file in the same folder as your index.html n order for it to appear on the page and my passions that were below did not happn expect one that did happen I created a logo for my businesss after that. I got used to how important it was to commit your changes after you wrre finished with each assignment. Unforantley the third assigmnent which required to publish your site on Netfly was not working so that was fustrating becaise I ke[t on trying to figure out what I did wrong and watched the tutoral video numerous times. About Me: Initial Setup on GitHub & Netlify. Getting my files in my README in Github was simple and easy. About Me: Adding Some Style tought me how to use css which I did not learn before and I got to play around with the codes often to see how certin color schemes work an that was pretty fun. I picked colors that were easy to read and were my favriotes personally. Also the font and padding which made the site look better. About Me: Tell Me More was my favriote assignment for this project because I got to select three photos that describe me and create a photo gallery which was pretty cool to look at and use. I also how to use figcaptins which made he phptos stand out. The additionion of adding a blob pof text from Dr. Jyde and Mr Hyde was pretty uniquie and diffremt and it added interst in the site. I learned that adding a article is another standout. About Me: Embedded Media was cool because you got to record and put in the code to insert a short clip of yourself talking about anything. People viewing the site could now see yur actual face:)))). About Me: Web Forms was fun because it is extermently important on any webpage to have a Contact Form. You got to design it the way you liked which I had fun with via css. I learned on this project that you can view on Chrome how the wepbsite would look on difffrent screen divices which is important to make sure your site looks good and aligned from the smallest device to the biggest device. The last asssignment for the project About Me: Nav Bar seprated sections of the webpage to make it look better and more readable. Overall, I gained knowelege on HTML based on this project and will use theese tools for the future. 

My color scheme consits of sky blue as the background since my wepage is mostly about my business based on model airplanes and the color is easy to read darker text which is mostly muy text colors. I wanted tp sepreate each section with a diffrent color for the title I did purple and my name, place of resdidence in orange, my passions, figcaptions, in a darker red, m story text in black since I wanted a plain color for that and the Contact Form, has a purple border with a orange send button. I used most of my favriote colors for this project on css and design.


Here is a link from my website that I got some pictures from: https://nickygcollectables.com/ other pictures were from my phone. The Lipsum text that was not written or created by me: https://litipsum.com/ but other than that no other sources that werent created by me.


The license I would like to achevie from GitHub is Academic Free License v3.0 since my content is not considred intersting to most and my webpage is to simple for the higher licenses based on my expreince with HTML being a beginner still.

NavBar
I updated my NavBar by adding the hamburger icon which was fdiffuclt to figfure out the code at first but eventullay I fured it out. I linked each page to the correct section and added some styling to the bar with a solid red background color. I also added my business logo on thw ebsite just to include it.

Netfly Large Media 
Netlify Large Media is a Git LFS implementation for repositories connected to other Netlify websites. This concept means that users can use GitHub to work with large files like images, audio, and video, without filling up your repository. It works by replacing the asset files un your repository with text pointer files, then uploading the assets to the storage service. If you have a Netlify site with Large Media inside, the CMS version of 2.6.0 and above will handle the larger asset files in the same way the files that were stored directly in the repository. 

To use Netlify Large Media with Netlify CMS, you need to do:
1. Upgrade Netlify CMS to version 2.6.0 or newer<li>
2. Configure Netlify CMS to use the Git Gateway backend with indemnity and proof from Netlify
3. Configure the Netlify website and the repository that is connected to use Large Media<li>

 When these steps are completed, you can now use Netlify CMS as normal, and the configured asset will automatically be handled by Netlify Large Media


All JPEG, PNG, and GIF files that are dealt with Netlify Large Media have access to Netlify’s on demand image transformation service. This service allows anyone to request an image to match the dimensions to specify in a query parameter added to the image URL

Any repositoriy enabled with Netlify Large Media, Netlify CMS will use the image transformation query parameters to load thumbnail-sized images to the media gallery view which makes the images in the gallery load quicker

 You can disable the automatic image transformations with the use_large_media_transforms_in_media_libarary configuration setting, nested under backend in the CNS config.yml file
 
Exp: 
backend:
                name: git-gateway
                ## Set to false to prevent transforming images in media gallery view
                use_large_media_transforms_in_media_library: false


 Once you configured your large media files, you will need to configure your media library on Forestry to use it 

To do this, Go to Settings > Media on your Forestry Site, and change your Media Storage Provider setting to Netlify Large Media 


 Your upload directory should stay the same, so re-enter the director you were using before. The public path should by the URL to the media file on your Netlify site. This will be your public path prepended to your site. 

Below the path fields, click the Connect to Netlify button to connect Forestry to Netlify in order to authenticate the media library 

Once you have connected to Netlify you will see the Connected message on the settings page

To resize the image on-the-fly to the size I want, I can do it through URL params:

<img 
  src="slides/Oops.003.jpeg?nf_resize=fit&w=1000"
  alt="Screenshots of CSS-Tricks and CodePen homepages"
/>
Which is superpowered by a responsive images syntax. For example…

<img srcset="img.jpg?nf_resize=fit&w=320 320w,
             img.jpg?nf_resize=fit&w=480 480w,
             img.jpg?nf_resize=fit&w=800 800w"
      sizes="(max-width: 320px) 280px,
             (max-width: 480px) 440px,
             800px"
        src="img.jpg?nf_resize=fit&w=800" alt="Elva dressed as a fairy">




Sources:
https://www.netlifycms.org/docs/netlify-large-media/
https://forestry.io/docs/media/netlify-large-media/
https://css-tricks.com/getting-netlify-large-media-going/

