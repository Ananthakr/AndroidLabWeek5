# AndroidLabWeek5
This repository contains code for Week 5 in Android Lab on 8/7/17

<b>App flow</b>
Take a photo -> Save it -> Animate it(Click again to stop animation)

All pictures are stored in <b>Internal Storage -> Android -> data -> ml.ananthakumar.AndroidLabWeek5 -> files -> Pictures</b> 

Change animation styles if you like.
I have added 4 basic animations in the <b>res->anim</b> folder
Replace the name to get different animation.
<b>MainActivity:235</b>
Animation animation = AnimationUtils.loadAnimation(getApplicationContext(),R.anim.YOUR_ANIMATION_NAME);
                    

If you want to change the app name, follow this thread
https://stackoverflow.com/a/39092799/5424353

