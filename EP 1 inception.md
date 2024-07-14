1. VS code uses Emmet to generate some code.

2. Creating element is core of React, hence
        const heading = React.createElement("h1", {id: "heading"}, "hello world");
    But rendering in platform specific platfor, like browser to create root element
        const root = ReactDOM.createRoot(document.getElementById("root"));

3. React.createElement creates element object, with props, type and other object properties

4. root.render(heading) will convert element object to h1 tag and put into browser

5. React.createElement takes 3rd argument as it's children, if more than one children, then pass them in array 

● What is Emmet?
● Difference between a Library and Framework?
● What is CDN? Why do we use it?
● Why is React known as React?
● What is crossorigin in script tag?
● What is diference between React and ReactDOM
● What is difference between react.development.js and react.production.js files via CDN?
● What is async and defer? - see my Youtube video ;)
