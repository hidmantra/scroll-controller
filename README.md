scroll-controller is another tool allowing the controll of "animations" based on the windows scroll position. Unlike other scroll utilities this one changes the state of attributes of registered elements. This approach was taken mainly for two specific use cases:
1. To release the coupling of visual element presentation from the mechanism of scrolling into the screen. This way each screen can be designed independently and easily re-ordered.
2. To allow complete control of a screen's state to the user.