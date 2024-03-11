### Links:

[Live link](https://v24dao-fem-a3.netlify.app/) |
[Front End Mentor Challenge]() |
[All my Front End Mentor Solutions](https://github.com/v24dao/Front-End-Mentor-Challenges)

### What I've Learned:

#### 1. Avoiding overflowing content

```CSS
.grid-container{
    /*This ensures curved edges on the grid regardless of screen size. Without overflow:hidden, we would need to change the border-radius on our grid-items for every screen size.*/
    overflow: hidden;
}
```

#### 2. Using 'width' in conjunction with 'max-width'

```CSS
.grid-container {
          /* We set a width below 100% so that we always horizontal spacing between the grid container and the edge of the screen */
          width: 95%;
          max-width: 750px;
        }
```

### Challenge Screenshot:

<img src="challenge-screenshot-desktop.png" width="500">
<img src="challenge-screenshot-mobile.png" width="300">
