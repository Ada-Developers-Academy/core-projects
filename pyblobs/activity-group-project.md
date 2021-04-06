
# Activity: Pyblob Extension

Now that we have a functioning animation, let's use what we learned about OOP to expand Pyblobs. Work with your partners to execute Wave 1 and Wave 2. Both waves can be executed a variety of ways and breaking down each feature into sub-problems is highly encouraged. Feel free to get as creative as you want with these next waves:

### Wave 1

**Make a New Child Class of Blob** This blob can be any color, size, or shape. Using method overriding, make this new class move differently than other blobs. 

Consider the following possible behaviors for the blobs: 
 - follow the [mouse](https://www.pygame.org/docs/ref/mouse.html#pygame.mouse.get_pos) or
 - randomly teleport when crossing an arbitrary x position.

### Wave 2
**Create a custom collision effect** 

This wave will be made in two steps: 

1) Add `is_touching()` and `handle_collisions()` to `main.py`. `is_touching` is a helper function that returns `True` when the distance between two blobs is less than the sum of the blobs' sizes. `handle_collision()` checks if a blob has collided with a blue_blob. 

``` Python
def is_touching(b1, b2):
  return math.sqrt((b2.x-b1.x)**2 + (b2.y-b1.y)**2) < (b1.size + b2.size)
  print(math.sqrt((b2.x-b1.x)**2 + (b2.y-b1.y)**2) < (b1.size + b2.size))

def handle_collisions(blob_list):
    blues, reds, greens = blob_list
    for blue_id, blue_blob in blues.copy().items():
        for other_blobs in blues, reds, greens:
            for other_blob_id, other_blob in other_blobs.copy().items():
                if blue_blob == other_blob:
                    pass
                else:
                    if is_touching(blue_blob, other_blob):
                      #insert collision event here
                            
    return blues, reds, greens
```

2) Create a collision effect to the new class made in Wave 1. The effect can involve blobs shrinking, growing, changing colors or increasing a counter variable. Feel free to refer to [Detecting collisions](https://pythonprogramming.net/detecting-collisions-intermediate-python-tutorial/) for an example.
