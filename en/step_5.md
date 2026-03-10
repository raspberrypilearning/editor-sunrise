## Infinite animation

Let's make the animation keep repeating forever.

+ If you want the sun to rise and then set, just add more keyframes to your animation:

    ```
    @keyframes sunrise {
        0%  
        33% 
        66% 
        100%
    }
    ```

    This means that the animation starts and ends with the sun at the bottom of the sky, and stays at the top from 33% until 66% of the animation.

+ Now you just need to add the word `infinite` to the `#sun` animation to make it loop forever:

    ![screenshot](images/sunrise-infinite.png)

+ Test out your animation. Does the sun keep rising and setting? 