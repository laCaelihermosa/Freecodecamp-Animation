transform-origin
# The transform-origin property is used to set the point around which a CSS transformation is applied. For example, when performing a rotate, the transform-origin determines around which point the element is rotated. ex: transform-origin: 50% 0%; is will set the origin point to be offset 50% from the left and 0% from the top, placing it in the middle of the top edge of the element.

@keyframes
# The @keyframes at-rule is used to define the flow of a CSS animation. Within the @keyframes rule, you can create selectors for specific points in the animation sequence, such as 0% or 25%, or use from and to to define the start and end of the sequence.
# @keyframes rules require a name to be assigned to them, which you use in other rules to reference. For example, the @keyframes freeCodeCamp { } rule would be named freeCodeCamp.
        @keyframes freecodecamp {      
        X% {
            RULE: attribute;
        }
        }

        @keyframes wheel {      animation in wheel to rotate completely
        0% {
            transform: rotate(0deg);
        }
        100% {
            transform: rotate(360deg);
        }
        }

animation-name: wheel;
# The animation-name property is used to link a @keyframes rule to a CSS selector. The value of this property should match the name of the @keyframes rule. Give your .wheel selector an animation-name property set to wheel.

animation-duration: 10s;
# The animation-duration property is used to set how long the animation should sequence to complete. The time should be specified in either seconds (s) or milliseconds (ms). Set your .wheel selector to have an animation-duration property of 10s.

animation-iteration-count: infinite;
# The animation-iteration-count property sets how many times your animation should repeat. This can be set to a number, or to infinite to indefinitely repeat the animation. Your Ferris wheel should never stop, so set the .wheel selector to have an animation-iteration-count of infinite.

animation-timing-function: linear;
# The animation-timing-function property sets how the animation should progress over time. There are a few different values for this property, but you want the Ferris wheel animation to run at the same rate from start to finish. Set the animation-timing-function to linear in your .wheel selector.

ease-in-out timing function
# This setting will tell the animation to start and end at a slower pace, but move more quickly in the middle of the cycle.