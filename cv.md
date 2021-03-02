# Curriculum vitae
1. Polina Ren
2. 
    1. telegram: @LekaRen (ノモ) (better to me)
    2. Discord on channel RS: Leka (@leka-ren)
    3. Mail 
3. I've been coding for a year and a half, сurrently I'm working on a specialty Junior Web Programming. My good quality is to help others, I love to study, I think that to become a good programmer you need to program a lot, so I am looking for opportunities where I can improve my knowledge and share knowledge with others. By myself, I am sociable and the soul of the company.
4. JavaScript, Node, PostgreSQL, MongoDB, Express.js, Webpack, HTML, CSS, ReactJS, Redux, Vue, Git, little-bit C :), BEM, REST, work in VScode, IDEA.
5. A "get" function that gets an object and the path to a nested property of the object and returns the value of that property (or undefined if the property does not exist): 
```
    function get(obj, path, defaultValue) {
        let pointer = obj;
        const newPath = path.split(".");
        for (let i = 0; i < newPath.length; i++) {
            if(!pointer[newPath[i]] && !defaultValue)  return undefined;
            if(!pointer[newPath[i]] && i !== newPath.length - 1) pointer[newPath[i]] = {};
            if(i === newPath.length - 1 && defaultValue) pointer[newPath[i]] = defaultValue;

            pointer = pointer[newPath[i]];
        }
        return pointer;
    }
```
6. Work experience:
    ____
    ### Yandex Praktikum
    #### Student, senior student

    Studied web development technologies, interaction with the server, working with Git and the basics of Backend development with node.js + express.js, HTML5 / CSS3 & BEM, adaptive and cross-browser layout, javascript, webpack.

    NewsExplorer ([Frontend](https://github.com/leka-ren/frontend-NewsExplorer) & [Backend](https://github.com/leka-ren/backend-NewsExplorer)) - thesis, developing a responsive web application. Backend uses mongoDB database, implemented in node.js + express.js, REST. On the frontend - layout according to the figma layout, HTML5 / CSS3 & BEM, ES6 are used.

    [#РАКЛЕЧИТСЯ(RAKLECHITSYA)](https://github.com/Raklechitca-Team/raklechitca) - development of an adaptive web application for the Konstantin Khabensky charitable foundation, layout based on Figma layout, working with HTTP requests via axios, VueJS, Vuex, Nuxtjs.
    ____
    ### Bambook
    #### Web-developer

    Software development, active participation in development, solo projects, work on the Agile system. Product development on ReactJS + Redux.
    ____

7. Basic education in web programming in Yandex.Praktikum, and other.
8. Based on the results of several tests on the Internet, the level of English is from A1 to A2(Soon I plan to sign up for courses);