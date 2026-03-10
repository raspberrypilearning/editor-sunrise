## Animating the sky

Animation isn't just for movement. Let's animate the sky to turn dark at night.

+ Add an animation called `sky` to your CSS:

    ```
    @keyframes sky {
        0%
        100%
    }
    ```

    Notice that this time you're animating the colour of the sky, and not the position.

+ Add code to your sky, to tell it to use your new animation:

    ```
    animation: sky 10s;
    ```

    ![screenshot](images/sunrise-sky.png)

+ Click **Autorun** to test your animation. 
