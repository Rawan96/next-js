# Next.js
![alt text](https://cdn.sanity.io/images/xvodw9ez/pkj/c3960647beaefd47869952de5fc0ffdfb78bdfdf-1140x651.png?w=1000
)

## Introduction 
<br />
Building a modern JavaScript application powered by React is awesome until you realize that there are a couple problems related to rendering all the content on the client-side.

* First, the page takes longer to become visible to the user, because before the content loads, all the JavaScript must load, and your application needs to run to determine what to show on the page.

* Second, if you are building a publicly available website, you have a content SEO issue. Search engines are getting better at running and indexing JavaScript apps, but it's much better if we can send them content instead of letting them figure it out.
<br />

**So what is the solution for this probelm? :thinking:**

The solution to this  problems is server rendering, also called static pre-rendering. Next.js is one of the React frameworks that do all of this in a very simple way, but it's not limited to this. It has many other features which helps us through building our application.



<br /> <br />
## The main features of Next.js :star2:	
<br />

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
<br /> <br />

## Next.js vs Gatsby	:roll_eyes:	

Next.js and Gatsby are great tools, and you can use it to power your applications. **But When is Next.js better than Gatsby? :thinking:** 
<br />
<br />
If you have lots of content, then static generated web pages (Gatsby) are not the best solution for you. The reason is that it takes much time to build the site if you have lots of content. 
So if you have a site with content that you will expect to grow and grow over time, then **Next.JS is the best choice for you**. 
Also, if you want more freedom with how you access your data, Next.JS is worth a try. <br /> <br />
Next.js provides a backend that can server side render a response to request, allowing you to create a dynamic website, which means you will deploy it on a platform that can run Node.js. And guess what?! Next.js can generate a static site too :star_struck: :heart_eyes:
