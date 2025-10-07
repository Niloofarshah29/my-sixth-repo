# my-sixth-repo
testing
from PIL import Image

img = Image.open("input.jpg")
resized = img.resize((400, 400))
resized.save("output.jpg")

print("Image resized and saved as output.jpg")

