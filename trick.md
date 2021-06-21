Transition between 2 component->

1. To have both components in the same file
2. Each of the components should be motion components
3. we need import {AnimatePresence} from framer motion
4. Wrap the component you wanna transition to with AnimatePresence.
5. Component which u wrap with AnimatePresence should have some TOGGLE to it.
6. import AnimateSharedLayout, wrap component you wanna transition
7. Give some kind of ID to both components like layoutId={id}

both of the component should have same transition

in this case we faced an issue where one id was a string and other number
