# Next JS
- Next Js is a Framework for React js.Next.js is built on top of React.js, adding features and optimizations specifically designed for server-side rendering (SSR), static site generation (SSG), and other advanced capabilities.

## Create a Project (Commands):-
```
npx create-next-app@latest
```
### you will than get several prompts which get information from you regarding the app creation. Those prompts are:-
`
? What is your project named? > projectName
? Would you like to use TypeScript? > No / **Yes**
? Would you like to use EsLint? > No / **Yes**
? Would you like to use Tailwind CSS? > No / **Yes**
? Would you like your code inside a `src/` directory? > No / **Yes**
? Would you like to use App Router?(recommended) > No / **Yes**
? Would you like to use Turbopack for `next dev`? > **No** / Yes
? Would you like to customize the import alias (`@/*` by default)? > **No** / Yes
`


## File Structure :-
```
-> <AppName>
        -> .next (folder)
            -> cache (folder)
            -> server (folder)
            -> static (folder)
            -> types (folder)
            -> trace (folder)
            -> app-build-manifest.json
            -> build-manifest.json
            -> package.json
            -> react-loadable-manifest.json
        -> node_modules (folder)
        -> public (folder)
        -> src\app (folder)
            -> globals.css
            -> layout.tsx
            -> page.tsx
        -> .gitignore
        -> package-lock.json
        -> package.json
        -> tsconfig.json
        -> README.md
        -> eslint.config.mjs
        -> postcss.config.mjs
        -> next-env.d.ts
        -> next.config.ts
        -> tailwind.config.ts
```


## Advantages of using Next Js over React Js:-

1. Server-Side Rendering (SSR) and Static Site Generation (SSG)
- React.js: React is a client-side library, meaning it renders components on the client-side after the browser downloads JavaScript. It requires additional configurations to support SSR/SSG.
- Next.js: Provides built-in support for SSR and SSG, enabling faster load times and better SEO. Pages can be pre-rendered at build time (SSG) or on-demand (SSR) with minimal setup.

2. Better SEO
- React.js: SEO is challenging with React because search engine bots struggle with JavaScript-rendered content.
- Next.js: Offers server-rendered pages, allowing search engines to index fully-rendered HTML, improving SEO performance.

3. File-Based Routing
- React.js: Requires a routing library like React Router. Developers need to manually define routes and manage configurations.
- Next.js: Comes with a file-based routing system out of the box. Simply create a file in the /pages directory, and Next.js automatically creates a route for it.

4. Image Optimization
- React.js: Does not include image optimization tools; developers need to use external libraries.
- Next.js: Built-in image optimization (via the <Image /> component), offering automatic resizing, lazy loading, and support for modern formats like WebP.

5. API Routes
- React.js: API integration requires setting up a separate backend or using libraries like Express.
- Next.js: Allows you to create API endpoints directly in the /pages/api directory, simplifying the setup for full-stack development.

6. Static and Dynamic Page Generation
- React.js: Only supports client-side rendering unless combined with tools like Gatsby.
- Next.js: Combines static and dynamic page generation. Use getStaticProps, getServerSideProps, or getStaticPaths to control data-fetching strategies.

7. Performance Optimizations
- React.js: Performance depends on developer configurations and additional libraries.
- Next.js: Automatically optimizes bundles, provides code-splitting, and lazy loads JavaScript and CSS.

8. Built-in CSS and Styling Support
- React.js: Requires third-party libraries like styled-components or CSS Modules.
- Next.js: Supports CSS Modules, SCSS, and styled-components out of the box with zero configuration.

9. Deployment
- React.js: React apps are typically deployed as static assets, requiring manual setup for optimization.
- Next.js: Integrates seamlessly with platforms like Vercel (its creators), offering fast, hassle-free deployment with advanced features like edge functions and incremental static regeneration.

10. Developer Experience
- React.js: Offers flexibility but requires more configuration and additional libraries to achieve advanced functionality.
- Next.js: Provides a batteries-included framework that reduces setup time and complexity, focusing on productivity.
