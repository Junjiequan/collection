# Javascript
Frequently used
[drag drop](http://jsfiddle.net/2Kgvh/)
```
https://www.w3schools.com/howto/howto_js_scroll_to_top.asp <<< scroll to top button

if(no margin on body tag) use below  
document.body.scrollHeight    // <<<  get entire page height
else use below
document.documentElement.scrollHeight

element.querySelectorAll(`.div[data-value]:not([data-value = "${e.target.textContent}"])`)
 
const text = ` <div class="handsome"> <p> ABCDEFG</p> <button> Click </button></div>`
element.insertAdjacentHTML(position, text);

element.innerHTML = "<div><p> Awesome </p></div>"
element.innerText = "text only"
const parent = child.parentElement || item.closest('.list-item').classList.toggle('fall')
const child = parent.childNodes
element.appendChild
```
# HTML

```
dropdown effects with only html
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



# Color 
- #070308 

![image](https://user-images.githubusercontent.com/78078898/112045354-0c4b4680-8b4b-11eb-9c01-384782f895dc.png)
- #ffd79d 

![image](https://user-images.githubusercontent.com/78078898/112045440-25ec8e00-8b4b-11eb-86bc-4d51e926246f.png)
- #7D3EC1 

![image](https://user-images.githubusercontent.com/78078898/112045565-49173d80-8b4b-11eb-8baf-7821f4d5e408.png)

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
Remove Icon pointer
```
pointer-events:none;
```
Add image in ReactJS condition use `` instead of ''
```
background: ${({whitebg}) => (whitebg ? `url(${imageUrl})`: '#170c1a')};
```

# check browser compatibility

```
<script type="text/javascript">
        var version = detectIE();
        if (version && version < 11) {
            document.getElementById('browser-not-supported').innerHTML =
                '<h4>' + '您的浏览器不支持访问本站，建议使用Chrome或360浏览器' + '</h4>';
        }

        function detectIE() {
            var ua = window.navigator.userAgent;
            var msie = ua.indexOf('MSIE ');
            if (msie > 0) {
                return parseInt(ua.substring(msie + 5, ua.indexOf('.', msie)), 10);
            }
            var trident = ua.indexOf('Trident/');
            if (trident > 0) {
                var rv = ua.indexOf('rv:');
                return parseInt(ua.substring(rv + 3, ua.indexOf('.', rv)), 10);
            }
            var edge = ua.indexOf('Edge/');
            if (edge > 0) {
                return parseInt(ua.substring(edge + 5, ua.indexOf('.', edge)), 10);
            }
            return false;
        }

        function navigateLink(url) {
            var hash = "/".replace(".", "");
            url = url.replace(hash + "https", "https").replace(hash + "bbs", "https://bbs");
            url = url.replace("dnvod.eu", "ifvod.tv");
            if (url.indexOf("http") > -1) {
                window.open(url, "_blank");
            } else {
                window.location.hash = '#navurl_' + url + (url.indexOf("?") > -1 ? "&r=" : "?r=") + Math.random();
            }
            // console.log(url)
        }

    </script>
```
