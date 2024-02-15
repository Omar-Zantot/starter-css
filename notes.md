## Notes

- `backface-visibility` :

  - determines if the back part of the element when we transform it is visible or hidden for the user.

  - So imagine we have an element and we rotate it 180 degrees.So it would be logical that we then see the back part of that element, right? But if we use backface-visibility hidden, then that back part behind the element gets hidden.

  - Now in this case (adding to `heading-primary`), we're not rotating anything, we're not doing anything like that but we still use this fix here, like this hack in order to fix this little shaking that we see in the animation. And again, no one really seems to know why the shaking happens and why this fixes it, but as long as it works, it's okay.
    <br/>

- `animation-fill-mode` :

  - it will automatically apply the styles up to zero percent before the animation starts So, again, these styles will now be applied before the animation starts simply by using the animation fill mode and set it to backwards.
