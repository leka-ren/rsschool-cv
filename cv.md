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