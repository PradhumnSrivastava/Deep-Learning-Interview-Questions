
3. How is an RGB image represented in a CNN? Ans- An RGB image has three channels: Red, Green, and Blue. Its shape is commonly (Height, Width, 3).

4. What do height, width, and channels mean in an image tensor? Ans- Height represents the number of pixel rows, width represents the number of pixel columns, and channels represent the image components, such as RGB.

5. What is a pixel in an image? Ans- A pixel is the smallest addressable element of a digital image and stores an intensity value or multiple color-channel values.

6. What are the typical pixel values of an 8-bit image? Ans- Each channel typically contains integer values from 0 to 255, where 0 represents the minimum intensity and 255 represents the maximum intensity.

7. Why do we normalize image pixel values before feeding them into a CNN? Ans- Normalization scales pixel values to a suitable range, such as [0, 1], which can improve numerical stability and help model training.

8. How do we normalize pixel values from 0–255 to 0–1? Ans- Divide every pixel value by 255.0, converting the range from [0, 255] to [0, 1].

9. Why do CNNs often resize input images? Ans- Resizing ensures that images have a consistent spatial size, making it easier to process them in batches and match the model's expected input dimensions.

10. What happens if an image has the wrong input dimensions for a CNN? Ans- The model may raise a shape error or reject the input if its architecture requires a specific size; compatible models may accept variable spatial dimensions.

11. What is the input shape of a CNN for a 64 × 64 RGB image? Ans- The image shape is (64, 64, 3) in channels-last format, or (3, 64, 64) in channels-first format.

12. What is a batch of images in CNN? Ans- A batch is a group of images processed together during a model operation. Its shape commonly includes a batch dimension, such as (Batch Size, Height, Width, Channels).

13. What is the batch input shape for 32 RGB images of size 64 × 64 in TensorFlow? Ans- The shape is (32, 64, 64, 3), where 32 is the batch size and the final dimension represents RGB channels.

14. What is the difference between channels-last and channels-first formats? Ans- Channels-last stores channels after height and width, such as (64, 64, 3), while channels-first stores channels before them, such as (3, 64, 64).

15. What happens to an image after it enters the first convolutional layer? Ans- Learnable filters slide across the image and compute feature maps that capture patterns such as edges, textures, and simple shapes.

16. Does a CNN directly understand an image like a human? Ans- No. A CNN processes numerical pixel values and learns statistical patterns from training data to perform tasks such as classification or detection.

17. What is the difference between an image's shape and its size? Ans- Shape describes its dimensions, such as (64, 64, 3), while size refers to the total number of elements, which is 64 × 64 × 3 = 12,288 in this example.

18. Why must the number of input channels match the first convolutional layer? Ans- Each convolutional filter is configured to operate across the input channels, so the filter's input-channel dimension must match the tensor's channel dimension.

19. How is a grayscale image converted into a three-channel image? Ans- Its single intensity channel can be replicated three times to create a three-channel tensor, although this does not add new color information.

20. How does a CNN process multiple images of different original sizes? Ans- Images are commonly resized or cropped to a compatible size before batching, or processed individually or with an architecture that supports variable spatial dimensions.
