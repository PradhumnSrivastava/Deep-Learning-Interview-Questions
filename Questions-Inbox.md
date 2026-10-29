
13. What is the batch input shape for 32 RGB images of size 64 × 64 in TensorFlow? Ans- The shape is (32, 64, 64, 3), where 32 is the batch size and the final dimension represents RGB channels.

14. What is the difference between channels-last and channels-first formats? Ans- Channels-last stores channels after height and width, such as (64, 64, 3), while channels-first stores channels before them, such as (3, 64, 64).

15. What happens to an image after it enters the first convolutional layer? Ans- Learnable filters slide across the image and compute feature maps that capture patterns such as edges, textures, and simple shapes.

16. Does a CNN directly understand an image like a human? Ans- No. A CNN processes numerical pixel values and learns statistical patterns from training data to perform tasks such as classification or detection.

17. What is the difference between an image's shape and its size? Ans- Shape describes its dimensions, such as (64, 64, 3), while size refers to the total number of elements, which is 64 × 64 × 3 = 12,288 in this example.

18. Why must the number of input channels match the first convolutional layer? Ans- Each convolutional filter is configured to operate across the input channels, so the filter's input-channel dimension must match the tensor's channel dimension.

19. How is a grayscale image converted into a three-channel image? Ans- Its single intensity channel can be replicated three times to create a three-channel tensor, although this does not add new color information.

20. How does a CNN process multiple images of different original sizes? Ans- Images are commonly resized or cropped to a compatible size before batching, or processed individually or with an architecture that supports variable spatial dimensions.
