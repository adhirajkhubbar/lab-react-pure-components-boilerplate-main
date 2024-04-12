Simple Component : On every Render, component does not check the prev state and props and directly renders the component based on whatever the state and props are received. In simple words, it will not memorize render for any props / state and it will always render a fresh new output everytime consuming time needed for every render. 

Pure Component : On Every Render, component will compare the current props / state with the previous ones (shallow comparison) and if the state / props are same as the previous ones, then it will render the output as prev. In simple words we can say that it will memorizing the render for some props / state and it again same props / state are seen, it will render the same output again saving the time.  


So the better one is pure component because , it is saving time by remembering the output for same props / state as compared to simple component. 