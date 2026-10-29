
18. Why must the number of input channels match the first convolutional layer? Ans- Each convolutional filter is configured to operate across the input channels, so the filter's input-channel dimension must match the tensor's channel dimension.

19. How is a grayscale image converted into a three-channel image? Ans- Its single intensity channel can be replicated three times to create a three-channel tensor, although this does not add new color information.

20. How does a CNN process multiple images of different original sizes? Ans- Images are commonly resized or cropped to a compatible size before batching, or processed individually or with an architecture that supports variable spatial dimensions.
