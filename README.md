[coding standard - js](https://github.com/airbnb/javascript)

## The most important thing by far - deep copy vs shallow copy 
[explanation](https://blog.alexdevero.com/shallow-deep-copy-in-javascript/)

## Prettier setting
[link](https://www.digitalocean.com/community/tutorials/how-to-format-code-with-prettier-in-visual-studio-code)
![image](https://user-images.githubusercontent.com/78078898/185477790-91044521-d19b-4aac-8604-65b4da0ea129.png)

## ES-lint

`npx eslint --init`

[Config Link](https://www.geeksforgeeks.org/how-to-configure-eslint-for-react-projects/)

## Some APIs & Codes used in previous vanilla javascript projects
- [drag drop](http://jsfiddle.net/2Kgvh/)
- [DnD pure JS](https://github.com/SortableJS/Sortable/wiki/Sorting-with-the-help-of-HTML5-Drag'n'Drop-API) 
- [Arrays reorder](https://stackoverflow.com/questions/2440700/reordering-arrays/2440723)
- [SortableJS](https://github.com/SortableJS/Sortable) 
- [EmailJS](https://www.emailjs.com/)
- [Grid-sort](https://vestride.github.io/Shuffle/)
- [Slider-Flickity](https://flickity.metafizzy.co/)
- [SmoothScroll](https://github.com/tsuyoshiwada/sweet-scroll)

## Libraries for REACT 
- [Cost-of-modules package cost check](https://www.npmjs.com/package/cost-of-modules) 
- [React-helmet /For HTML meta TAgs/](https://www.npmjs.com/package/react-helmet)
- [Styled-components](https://dev.to/paulclindo/everything-you-need-to-know-about-styled-components-2a6a)
- [react-burger-menu](https://www.npmjs.com/package/react-burger-menu)
- [react-burger-toggle-animation](https://hamburger-react.netlify.app/)
- [react-mob-navMenu-toggle-animation](http://negomi.github.io/react-burger-menu/)
- [react-responsive](https://www.npmjs.com/package/react-responsive)
- [hashRouter](https://reactrouter.com/web/api/HashRouter)
- [browserRouter](https://reactrouter.com/web/api/BrowserRouter)
- [react-page-transition](https://github.com/Steveeeie/react-page-transition)
- [framer-motion](https://www.framer.com/api/motion/)
- [react-animation](https://formidable.com/open-source/react-animations/)
- [react-lazy-load-image-component](https://www.npmjs.com/package/react-lazy-load-image-component) 
- [lazy-load-image](https://www.npmjs.com/package/react-lazyload)
- [React-msg-popup](https://www.npmjs.com/package/react-toastify)
- [React-Spinner](https://www.npmjs.com/package/react-spinners)
- [React-scroll-nav](https://gist.github.com/whoisryosuke/72d9979a44e01e95400760d98ca519e8)
- [React-use-cart](https://www.npmjs.com/package/react-use-cart)
- [React-transition-group](https://dev.to/terrierscript/styled-component--react-transition-group--very-simple-transition-jja)
- [React-hook-form](https://react-hook-form.com/) | [Examples](https://codesandbox.io/s/react-hook-form-controller-pz8oj?file=/src/index.js:93-103)
- [React-body-scroll-lock](https://www.npmjs.com/package/body-scroll-lock)
- [Dicebear - Random avatar generator](https://www.npmjs.com/package/@dicebear/avatars)
- [react-indiana-drag-scroll](https://github.com/Norserium/react-indiana-drag-scroll)


## Custom hooks
[usehooks-ts](https://usehooks-ts.com/react-hook/use-counter)
[usehooks](https://usehooks.com/useWindowSize/)

## React events
- [events](https://reactjs.org/docs/events.html)
- [TypeScript](https://create-react-app.dev/docs/adding-typescript/)

## Redux
window.__REDUX_DEVTOOLS_EXTENSION__ && window.__REDUX_DEVTOOLS_EXTENSION__()

`import { createStore } from 'redux;`

//ACTION

`
const increment = () => {
    return { type:'INCREMENT' }
}`

//REDUCER

```
const counter = (state=0; action)=>{
     switch(action.type){
          case "INCREMENT":
               return state + action.payload 
     }
}

```

`let store = createStore(counter) 
`

//Display in console

`
store.subscribe(() => console.log(store.getState()));
`

//DISPATCH

`
store.dispatch(increment());
`

## LocalStorage vs SessionStorage vs cookies
For most cases, we use the localStorage object if we want some data to be on the browser. <br/>
If we want it on the server, then we use cookies, and the sessionStorage is used when we want to <br/>
destroy the data whenever that specific tab gets closed or the season is closed by the user.

![image](https://user-images.githubusercontent.com/78078898/172065063-5c54b371-839b-46c2-a802-23b86bc74b45.png)





## Frequently used codes
```
https://www.w3schools.com/howto/howto_js_scroll_to_top.asp <<< scroll to top button

if(no margin on body tag) use below  
document.body.scrollHeight    // <<<  get entire page height
else use below
document.documentElement.scrollHeight

element.querySelectorAll(`.div[data-value]:not([data-value = "${e.target.textContent}"])`)
 
const text = ` <div class="handsome"> <p> ABCDEFG</p> <button> Click </button></div>`
element.insertAdjacentHTML(position, text);

const parent = child.parentElement || item.closest('.list-item').classList.toggle('fall')
const child = parent.childNodes
element.appendChild
```
# HTML

## FORM
[stakoverflow](https://stackoverflow.com/questions/44062024/submit-form-using-button-in-parent-component-in-react/44062192%20%20____FORM%20INPUT)

```
<Form id="check-this"> 
    <label>
        <input />
    </label>
</Form>

<button form="check-this" content='Submit' value='Submit'/>
```
## dropdown effects with only html

```

<details>
    <summary>Details</summary>
    Something small enough to escape casual notice.
</details>
```


# Font 
- font-family: 'Cedarville Cursive', cursive; 

![image](https://user-images.githubusercontent.com/78078898/112046156-f7bb7e00-8b4b-11eb-8e74-f4617c4fafbd.png)
- font-family: 'Kanit', sans-serif; 

![image](https://user-images.githubusercontent.com/78078898/112045985-c04cd180-8b4b-11eb-8ff5-9bf204a3af96.png)
- font-family: 'Encode Sans', sans-serif; 

![image](https://user-images.githubusercontent.com/78078898/112046068-dc507300-8b4b-11eb-9888-4158fd64e143.png)
- font-family: 'Poppins', sans-serif;

![image](https://user-images.githubusercontent.com/78078898/112513784-f92bb700-8d94-11eb-9997-c1743aec82a2.png)
- font-family: 'Barlow Condensed', sans-serif;

![image](https://user-images.githubusercontent.com/78078898/113646841-ec0ea200-9689-11eb-9f99-95646145a994.png)



# Color gradient

- [UI gradient](https://uigradients.com/#MegaTron)

# Design

- [Dribbble](https://dribbble.com/)
- [Behance](https://www.behance.net/)

# Some code 
## CSS
Parent hover change child style **styled component**
```
  ${Link}:hover & {
    fill: rebeccapurple;
  }
```
Give text paragraph in curly bracket 
```
white-space: pre-wrap; // css property

{I am.\nJay}
```
Replace letters with ...
```
.demo-1 {
  overflow: hidden;
  display: -webkit-box;
  -webkit-line-clamp: 3;
  -webkit-box-orient: vertical;
}
```
# Vite deloy
```
npm run build
git add dist -f
git commit -m "..."
git subtree push --prefix dist origin gh-pages
```

# Heroku
[sub-directory push to the heroku] (https://stackoverflow.com/questions/26241683/heroku-deploy-a-sub-directory)
 git subtree push --prefix client heroku master
 
 
# GIT

```
Pure Git command pull process
1. git clone https://github.com/userID/forked-repo.git
2. cd forked-repo
3. code .    < open VS code
4. git status    < check whether if something has changed
5. git add README.md     < push to stage step( add comment || delete change)
6. git commit -m 'description'     < -m is message command 
7. git push origin master      < master can be main sometimes.
/////////////////////////////////////////////////////////////////////////////////////////////////////////////

git reset --hard <commit here>   <<- Set specific commit to top and delete all the commits before the commit
git push --force
mkdir components  <- create folder
touch index.js <- create file

If entered VIM
Press i to enter insert mode (start typing your commit message)
Press esc to exit insert mode
Press :w to save the file
Press :q to close the file
Press :wq as a shortcut for the above

```
# Typescript 

```
The key point is using the -p flag to inform npx that the tsc binary belongs to the typescript package

npx -p typescript tsc --init

In case 'ts-node' is not recognized, ts-node is needed to be installed with npx
"start": "nodemon --exec npx ts-node ./index.ts",
```

# ExpressJS

[What does next() do in Express](https://stackoverflow.com/questions/10695629/what-is-the-parameter-next-used-for-in-express)
[Express doc](http://qnimate.com/express-js-middleware-tutorial/)
```
function loadUser(req, res, next) {
  if (req.params.userId) {
    Users.findOne({ id: req.params.userId }, function(err, user) {
      if (err) {
        next(new Error("Couldn't find user: " + err));
        return;
      }

      req.user = user;
      next();
    });
  } else {
    next();
  }
}

// ...

app.get('/user/:userId', loadUser, function(req, res) {
  // do something with req.user
});

app.get('/users/:userId?', loadUser, function(req, res) {
  // if req.user was set, it's because userId was specified (and we found the user).
});

// Pretend there's a "loadItem()" which operates similarly, but with itemId.
app.get('/item/:itemId/addTo/:userId', loadItem, loadUser, function(req, res) {
  req.user.items.append(req.item.name);
});
```
