# THE CHAMBERS OF SECRET

### INTRO TO APP
Image Steganography is widely used for hiding a message image into a cover image. This research domain is deployed at the commercial level at both government and private sector to exhaust its opportunities.This Application encode and decode secret text message and image into and from the cover image. To encode text message and image into cover image, user need to first load cover image into application from their gallary. Then user can write text message in text area to encode/hide it in the cover image. If user want to hide image into cover image then user can add image from gallery into application and by pressing encode button text message and image will be successfully encode into cover image. Remember that only one secret either text message or image can be encoded into cover image at a time. For decoding stego or encoded image will need to be loaded in the application then by pressing decode button encoded secret text message or image will be display to user.

### Algorithm for Encoding:
1. Read a cover image and a text message.
2. Convert cover image into base 64 format.
3. Delete last 4 bits of the base 64 format data of cover image.
4. Calculate number of rest of the bits of base 64 format data of the cover image. Name it Pj
5. Add the text message there at the end of the base 64 format data of image.
6. Write stego image

### Algorithm for Decoding:
1. Read the base 64 format string of stego image.
2. Calculate the number of the bits of base 64 bit format data of stego image.Name it Qj.
3. Subtract Pj from Qj. Name it Msglen.
4. After knowing the Msglen we can easily retrieve the secret message from Qj. Thus we perform the encoding and decoding process in our image steganography application.

## THANK YOU!!
