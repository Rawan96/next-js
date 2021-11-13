# Next.js
![alt text](https://cdn.sanity.io/images/xvodw9ez/pkj/c3960647beaefd47869952de5fc0ffdfb78bdfdf-1140x651.png?w=1000
)

## Introduction 
<br />
Building a modern JavaScript application powered by React is awesome until you realize that there are a couple problems related to rendering all the content on the client-side.

* First, the page takes longer to become visible to the user, because before the content loads, all the JavaScript must load, and your application needs to run to determine what to show on the page.

* Second, if you are building a publicly available website, you have a content SEO issue. Search engines are getting better at running and indexing JavaScript apps, but it's much better if we can send them content instead of letting them figure it out.
<br />

**So what is the solution for this problem?**
The solution to this  problems is server rendering :thinking:.
<br />

## Client-side rendering vs. Server-Side Rendering!
### Client-Side Rendering
Client-side rendering allows developers to make their websites entirely rendered in the browser with JavaScript. Instead of having a different HTML page per route, a client-side rendered website creates each route dynamically directly in the browser. This approach spread once JS frameworks made it easy to take.
#### Benefits/Drawbacks to Client Side Rendering
#### Pros
1- Ideal for dynamic, interactive sites
2- Faster load times — in the event that you want your user to be directed to different pages, it will load much quicker than server side frameworks
3- Wide selection of various JavaScript libraries — more on this later!

#### Cons
1- Not great for SEO — web crawlers can have a more difficult time, which may result in your website’s appearance in search results
2- Slower initial load time for landing page
3- May require additional libraries

### Server-Side Rendering
SSR is the original way information has been rendered and displayed in the browser. The server gets a request from a user, compiles the HTML and the styles, and then sends a ready to be rendered HTML page to the browser to be displayed. When the user interacts with the page like clicking on a link or submitting information, the entire process happens again.
Server-side rendering allows developers to pre-populate a web page with custom user data directly on the server. It is generally faster to make all the requests within a server than making extra browser-to-server round-trips for them. This is what developers used to do before client-side rendering.

#### Benefits/Drawbacks to Server Side Rendering
#### Pros
1- Better SEO — web crawlers have an easier time with server side rendering, which can improve your website’s appearance in search results
2- Great for static sites — not every website needs to have interactive media or animations. If this is the case for you, perhaps having a website composed of HTML and CSS will work fine.
3- Initial page will load faster, compared to client side rendering

#### Cons
1- Not ideal for dynamic sites
2- Pages that are not the landing page may load slower
3- Many reloads — with server side rendering, you have to make frequent requests to the server to display new and/or different pages.

<br />

**Next.js is a JavaScript framework created by Zeit. It lets you build server-side rendering and static web applications using React. It’s a great tool to build your next website. It has many great features and advantages, which can make Nextjs your first option for building your next web application.**
<br /> <br />
## The main features of Next.js :star2:	

1. **Hot Code Reloading**:

   It automatically reloads the application when changes in the code get saved.
 
2. **Server Rendering**:
  
    Easily render react component on server before sending HTML to client.
  
3. **Automatic Code Splitting**:
  
    By this feature, every import in the code get bundled and served with each page. It means that unnecessary code never get loaded on the page.
  
4. **Styled-JSX**:
  
    Styled-JSX allows you to write CSS directly inside JavaScript code.
  
5. **Ecosystem Compatibility**:
  
    Compatible with JavaScript, Node and react.
  
6. **Automatic Routing**:
  
    Any URL is mapped to the filesystem, to files put in the pages folder, and you don't need any configuration.
  
7. **Dynamic Components**:
  
    You can import JavaScript modules and React Components dynamically.
  
8. **Static Exports**:
  
    Using the next export command, Next.js allows you to export a fully static site from your app.
  
  <br /> 
    
  ### **Example**
  ```
  function Main() { 
    return ( 
        <div className="container"> 
        <p>Hello G8</p> 
        </div> 
    ) 
} 
  
export default Main 
```
<br />

## Next.js vs Gatsby	:roll_eyes:	
<br /> 

Next.js and Gatsby are great tools, and you can use it to power your applications. **But When is Next.js better than Gatsby? :thinking:** 
<br />
<br />
If you have lots of content, then static generated web pages (Gatsby) are not the best solution for you. The reason is that it takes much time to build the site if you have lots of content. 
So if you have a site with content that you will expect to grow and grow over time, then **Next.JS is the best choice for you**. 
Also, if you want more freedom with how you access your data, Next.JS is worth a try. <br /> <br />

On the other hand, Gatsby is great if you are just developing a smaller application or one that will be pulling directly from a CMS. Gatsby is easier to set up, which is a great fit if the project is on the smaller side.


Next.js provides a backend that can server side render a response to request, allowing you to create a dynamic website, which means you will deploy it on a platform that can run Node.js. And guess what?! Next.js can generate a static site too :star_struck: :heart_eyes:
