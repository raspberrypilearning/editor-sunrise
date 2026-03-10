--- challenge ---

## Challenge: More animation

Can you animate another image? You can animate the position, colour, shape, size, opacity (seethroughness) or anything else you can think of. Also try changing the amount of time your animations run for. 

For each item you want to animate, you will need to:

+ Include it in your HTML with an id
+ Add a style for the id
+ Create an @keyframes rule
+ Use `animation:` in the style to use the animation you defined with @keyframes 

Click on the image icon to see the images that are included in the project:

![screenshot](images/sunrise-images.png)

You can also upload your own images if you like. 

Don't forget you can put items in the sea as well as the sky:

![screenshot](images/sunrise-boat.png)

In the example the rainbow uses opacity for a fade effect:

```
@keyframes fade {
  0%  
  50% 
  66% 
  100%  
}
```

The boat uses a negative starting position so that you can't see it for part of the animation:

```
 @keyframes left-right {
  0%   
  100% 
}
```

--- /challenge ---