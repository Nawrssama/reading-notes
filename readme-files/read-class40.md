1. Dynamic routes in Next.js allow for handling variable URLs, where the page content can change based on the value in the URL. They are defined using brackets ([]) in the page file name and are accessed through the `useRouter` hook. Static routes, on the other hand, pre-render pages at build time, and the content remains the same until the next build.

2. Deploying a Next.js application involves these key steps: 
   >a) Build the application using `npm run build` or `yarn build`. 
   
   >b) Choose a deployment platform, such as Vercel, Netlify, or custom setups with services like AWS, DigitalOcean, or Heroku. 
   
   >c) Configure the platform to run the built application. 
   
   >d) Deploy the application either manually or through continuous integration (CI) pipelines.

3. Next.js handles static file serving using the `/public` folder. Files placed in this folder are directly accessible by the client without going through the Next.js server. For example, a file `/public/images/logo.png` can be accessed at `http://yourdomain.com/images/logo.png`. This folder structure allows you to store assets like images, fonts, and other static files in a straightforward manner. In Next.js components, you can reference these assets using the `basePath` as `/` (root). For example, `<img src="/images/logo.png" alt="Logo" />`.